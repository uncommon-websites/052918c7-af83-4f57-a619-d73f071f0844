<script lang="ts">
	import SectionHeader from "$lib/components/layout/SectionHeader.svelte";

	let {
		title,
		subtitle,
		imageSrc = "https://www.unc.mn/image-placeholder.svg",
		...rest
	}: {
		title: string;
		subtitle: string;
		imageSrc: string;
		[key: string]: any;
	} = $props();
</script>

<header class={["relative overflow-hidden", "bg-gradient-to-r from-pink-500 via-purple-500 via-orange-500 to-blue-500"]} {...rest}>
	<div class="relative z-10 py-16 px-4 sm:px-5 md:px-8 lg:px-10 container mx-auto grid gap-16 gap-y-0 text-white">
		<SectionHeader {title} {subtitle} size="lg" />
		<div class="aspect-video overflow-clip rounded-xl bg-white/10 backdrop-blur-sm">
			<img
				class="h-full w-full object-cover"
				src={imageSrc}
				alt="Professional team collaborating in modern contact center workspace"
			/>
		</div>
	</div>
</header>
