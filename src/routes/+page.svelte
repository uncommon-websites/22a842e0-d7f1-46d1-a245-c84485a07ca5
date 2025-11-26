<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";

	// Icons
	import IconBrain from "~icons/lucide/brain";
	import IconTarget from "~icons/lucide/target";
	import IconUsers from "~icons/lucide/users";
	import IconBadgeDollarSign from "~icons/lucide/badge-dollar-sign";
	import IconZap from "~icons/lucide/zap";
	import IconRocket from "~icons/lucide/rocket";
</script>

<Hero
	title="Hire pre-vetted talent in days, not months"
	subtitle="AI-powered screening and behavioral assessments deliver instant access to qualified candidates for growing startups."
	imageSrc="/generated/image-documentary-editorial-photograph-of-a-di.webp"
	centered={false}
	callsToAction={[
		{
			href: "/contact",
			label: "Start hiring"
		},
		{
			href: "/about",
			label: "Learn more"
		}
	]}
/>
<LogoScroller
	label="Trusted by growing teams"
	logoUrls={[
		'https://cdn.brandfetch.io/vercel.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/notion.so/w/400/h/400/logo',
		'https://cdn.brandfetch.io/linear.app/w/400/h/400/logo',
		'https://cdn.brandfetch.io/retool.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Fast hiring for growing teams"
	text="Hero delivers instant access to pre-vetted candidates through AI-powered screening and behavioral assessments. We serve growing startups and small businesses who need to hire quickly but lack dedicated recruiting resources. Our platform eliminates months of searching and vetting, so you can focus on building your business instead of filling roles."
/>

<Testimonials
	testimonials={[
		{
			name: "Maya Chen",
			position: "CEO",
			company: "Flux Technologies",
			quote:
				"We hired our first two engineers in 6 days instead of the 3 months it took us last time. The pre-vetted candidates were phenomenal—every interview was with someone we'd actually consider hiring.",
			image: "/generated/image-1-documentary-editorial-style-profession.webp"
		},
		{
			name: "Marcus Williams",
			position: "Co-founder",
			company: "Prism AI",
			quote:
				"Hero saved us over $30,000 compared to traditional recruiters. The 10% placement fee is transparent and fair, and the quality of candidates was actually higher than what we got from expensive agencies.",
			image: "/generated/image-2-documentary-editorial-style-profession.webp"
		},
		{
			name: "Sofia Rodriguez",
			position: "Head of People",
			company: "Vertex Labs",
			quote:
				"The behavioral assessments gave us confidence we were making the right hires. We've brought on four people through Hero and every single one is still with us and exceeding expectations six months later.",
			image: "/generated/image-3-documentary-editorial-style-profession.webp"
		}
	]}
/>

<Features
	title="Built for speed and precision"
	subtitle="Everything you need to hire top talent without the traditional recruiting overhead."
	features={[
		{
			title: "AI-powered candidate screening",
			description:
				"Eliminate weeks of manual resume review with intelligent screening that surfaces qualified candidates instantly. Our AI evaluates skills, experience, and potential fit so you can focus on interviewing the best.",
			icon: IconBrain
		},
		{
			title: "Behavioral assessment engine",
			description:
				"Go beyond technical skills to understand culture fit and working style. Reduce mis-hires with psychological assessments that predict long-term success.",
			icon: IconTarget
		},
		{
			title: "Pre-vetted talent database",
			description:
				"Access a curated pool of ready-to-interview candidates who have already passed our rigorous screening process. Skip sourcing entirely and move straight to conversations.",
			icon: IconUsers
		},
		{
			title: "Transparent 10% placement fee",
			description:
				"No hidden costs or expensive agency retainers. Pay a flat 10% fee only when you hire, making quality recruiting accessible to growing teams.",
			icon: IconBadgeDollarSign
		},
		{
			title: "Lightning-fast matching",
			description:
				"Receive qualified candidate shortlists in days instead of months. Our platform delivers speed without compromising on quality or cultural alignment.",
			icon: IconZap
		},
		{
			title: "Startup-optimized process",
			description:
				"Purpose-built for lean teams who need to hire quickly but lack dedicated recruiting resources. No recruiting expertise required to find exceptional talent.",
			icon: IconRocket
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Your next hire is ready now"
	subtitle="Stop waiting, start building"
	description="While you're reading this, qualified candidates are slipping through to competitors who move faster. Hero delivers pre-vetted talent in days with transparent 10% placement fees. No agency retainers, no months of searching, no costly mis-hires."
	imageSrc="/generated/image-a-happy-startup-founder-subtly-smiling-w.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Start hiring",
			variant: "primary"
		},
		{
			href: "/about",
			label: "See how it works",
			variant: "secondary"
		}
	]}
/>
