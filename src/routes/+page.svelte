<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";
</script>

<CustomerCardHero
	centered={true}
	title="Transform fragmented customer interactions into unified experiences"
	subtitle="Join thousands of contact center directors who've reduced operational costs while dramatically improving customer satisfaction with Nextiva's AI-powered platform."
	customers={[
		{
			name: "Sarah Martinez",
			position: "Contact Center Director",
			imageSrc: "/generated/image-a-professional-woman-contact-center-dire.webp"
		},
		{
			name: "Michael Chen",
			position: "Customer Experience Manager", 
			imageSrc: "/generated/image-a-male-customer-experience-manager-in-a-.webp"
		},
		{
			name: "Jennifer Williams",
			position: "Operations Director",
			imageSrc: "/generated/image-a-female-operations-director-in-a-sleek-.webp"
		},
		{
			name: "David Rodriguez",
			position: "VP Customer Success",
			imageSrc: "/generated/image-a-male-business-executive-in-a-professio.webp"
		},
		{
			name: "Lisa Thompson",
			position: "Technology Director",
			imageSrc: "/generated/image-a-professional-woman-technology-leader-i.webp"
		}
	]}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/shopify.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/mailchimp.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/hubspot.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/salesforce.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="One platform. Every conversation."
	text="Nextiva brings all your customer interactions into a single AI-powered workspace—so agents stop switching tabs and start solving problems.

<<<<<<< HEAD
Turn chaos into clarity. Phone, chat, email, and SMS all in one place. No more juggling tools or repeating questions. Just smooth, consistent customer experiences that reduce costs and raise satisfaction."
=======
Turn chaos into clarity. Phone, chat, email, and SMS all in one place. No more juggling tools or repeating questions. Just smooth, consistent customer experiences every time."
>>>>>>> 84158a742ba02d6eeae69758a88fd9ad958cba33
/>

<Testimonials
	testimonials={[
		{
			name: "Yasmin Okafor",
			position: "Director of Customer Operations",
			company: "HealthBridge",
			quote:
				"With Nextiva, we reduced agent ramp time by 40%. Everything they need is finally in one place.",
			image: "/generated/image-professional-african-businesswoman-stand.webp"
		},
		{
			name: "Kai Nakamura",
			position: "VP Contact Center Technology",
			company: "ArcherPay",
			quote:
				"Migrating from five disconnected systems to Nextiva cut our monthly costs by $22,000 and gave us better reporting than we ever had.",
			image: "/generated/image-japanese-business-executive-male-seated-.webp"
		},
		{
			name: "Lina Torres",
			position: "Customer Experience Lead",
			company: "Montera Travel",
			quote:
				"Our CSAT jumped 18% after switching to Nextiva. Customers don't have to repeat themselves anymore. That alone made the shift worth it.",
			image: "/generated/image-latina-business-professional-woman-in-a-.webp"
		}
	]}
/>

<Features
	title="Unified customer experience platform"
	subtitle="Transform fragmented contact centers into efficient, AI-powered operations that deliver exceptional customer experiences while reducing costs."
	features={[
		{
			title: "Unified communications hub",
			description: "Consolidate all customer touchpoints—voice, chat, email, social—into one intelligent platform that eliminates agent confusion and reduces response times by 45%.",
			imageSrc: "/generated/image-a-lively-office-environment-where-a-dive.webp"
		},
		{
			title: "AI-powered customer intelligence",
			description: "Transform every interaction into actionable insights with real-time sentiment analysis and predictive routing that increases first-call resolution rates.",
			imageSrc: "/generated/image-a-thoughtful-team-of-analysts-in-a-brigh.webp"
		},
		{
			title: "Intelligent multi-channel routing",
			description: "Automatically connect customers to the right agent with the right skills through advanced algorithms that optimize for both efficiency and satisfaction.",
			imageSrc: "/generated/image-a-contemporary-office-scene-showing-seve.webp"
		},
		{
			title: "Real-time performance analytics",
			description: "Monitor contact center KPIs with executive dashboards that provide instant visibility into agent productivity and customer satisfaction trends.",
			imageSrc: "/generated/image-a-group-of-professionals-gathered-around.webp"
		},
		{
			title: "Streamlined agent experience",
			description: "Empower your team with an intuitive workspace that surfaces customer context and next-best actions, reducing training time by 60%.",
			imageSrc: "/generated/image-a-clean-organized-workspace-where-a-focu.webp"
		},
		{
			title: "Enterprise security & compliance",
			description: "Maintain the highest security standards with end-to-end encryption, SOC 2 compliance, and automated data governance that keeps your business protected.",
			imageSrc: "/generated/image-a-secure-office-environment-with-a-vigil.webp"
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
