<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Unified by design",
			description: "We built our platform from the ground up to connect every customer touchpoint, because fragmented experiences serve no one."
		},
		{
			title: "Customer obsessed",
			description: "Every feature we build starts with a simple question: will this make the customer's experience better?"
		},
		{
			title: "Agent empowered",
			description: "We believe great customer service comes from empowered agents who have the right context and tools to succeed."
		}
	];
</script>

<SecondaryHero
	title="Make every customer feel known"
	subtitle="One platform. Every conversation."
	imageSrc="/generated/image-a-professional-team-of-diverse-adults-co.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"Contact center directors know the frustration all too well: agents scrambling between disconnected tools, customers forced to repeat their stories across channels, and mounting pressure to deliver consistent experiences while controlling costs. In a $240 billion market drowning in fragmented systems, every inefficiency translates to lost revenue and frustrated customers. The human cost is real—agents burning out from context-switching, customers abandoning calls, and leaders struggling to maintain service quality with tools that work against each other instead of together.",
		"When Tomas Gorny founded Nextiva, he saw this challenge and chose to build differently from day one. While competitors were stitching together disparate solutions, Nextiva architected unified customer experience infrastructure from the ground up. Starting with small business VoIP, we methodically expanded our platform to consolidate every communication channel—voice, email, chat, and SMS—into one AI-powered system. This wasn't about adding features; it was about reimagining how customer interactions should flow when technology actually serves both agents and customers.",
		"Today, Nextiva processes over 100 million customer interactions, transforming what were once fragmented touchpoints into unified experiences that drive real business results. Mid-market companies choose us not just for cost reduction, but for the competitive advantage that comes from truly connected customer experiences. Our vision remains clear: every customer interaction should feel seamless, every agent should have complete context, and every business should be able to scale exceptional service without complexity. We're not just solving today's contact center challenges—we're defining what customer experience looks like in an AI-powered world."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Our team."
	subtitle="Your partners in innovation."
	stakeholders={[
		{
			name: "Alex Morgan",
			position: "Founder & CEO",
			bio: "Started the company with a vision to transform the industry through innovative solutions.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Jamie Chen",
			position: "Chief Design Officer",
			bio: "Award-winning designer with a passion for creating intuitive and beautiful experiences.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Taylor Wright",
			position: "Head of Engineering",
			bio: "Technology enthusiast focused on building scalable systems that make a difference.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<StakeholderGrid
	stakeholderType="investor"
	title="Backed by the best."
	subtitle="Point Nine, TSIC and others"
	stakeholders={[
		{
			name: "Point Nine Capital",
			image: "https://cdn.brandfetch.io/pointnine.com/w/400/h/400/logo?c=1id_elLz2Bd5Ej-dWo7"
		},
		{
			name: "TSIC Ventures",
			image: "https://cdn.brandfetch.io/tiny.vc/w/400/h/400/logo?c=1a2b3c4d5e"
		},
		{
			name: "Sequoia Capital",
			image: "https://cdn.brandfetch.io/sequoiacap.com/w/400/h/400/logo"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Stop switching between systems"
	subtitle="Start delivering unified experiences"
	description="Join 100,000+ businesses that chose Nextiva to eliminate agent context-switching, reduce customer effort, and scale exceptional service without complexity. See why contact center directors call us their competitive advantage."
	imageSrc="/generated/image-a-professional-contact-center-agent-dres.webp"
/>
