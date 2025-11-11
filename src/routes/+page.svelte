<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";
</script>

<CenteredTextOnlyHero
	title="Cultivating collective intelligence on AI's future"
	subtitle="Join a curated community of AI engineers and founders for intimate salons and thoughtful discourse that goes beyond shallow tech conversations."
	imageSrc="/generated/image-editorial-documentary-style-photograph-o.webp"
/>
<LogoScroller 
	label="Engaging minds from"
	logoUrls={[
		'https://cdn.brandfetch.io/openai.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/anthropic.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/deepmind.com/w/400/h/400/logo'
	]}
/>

<Summary
	text="Curious Circle hosts intimate salons where AI engineers and founders explore the meaningful questions shaping artificial intelligence. We create space for the kind of thoughtful, nuanced discourse that gets lost in the noise of tech Twitter and conference keynotes. Through curated conversations and a carefully selected community, we help builders think more deeply about the technology they're creating."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Anand",
			position: "ML Engineer",
			company: "Anthropic",
			quote:
				"Curious Circle saved me 8 hours a week I was wasting on shallow tech podcasts and Twitter discourse. The salon discussions with other AI engineers building real products gave me frameworks I immediately applied to our alignment research. Worth every minute.",
			image: "/generated/image-editorial-documentary-style-headshot-of-.webp"
		},
		{
			name: "Marcus Chen",
			position: "Founder",
			company: "Latent Labs",
			quote:
				"Before Curious Circle, I was making product decisions in an echo chamber. The diverse perspectives from AI founders facing similar challenges helped me avoid a costly pivot that would've set us back 6 months. The ROI is impossible to calculate but absolutely real.",
			image: "/generated/image-editorial-documentary-style-headshot-of-.webp"
		},
		{
			name: "Dr. Yuki Tanaka",
			position: "AI Research Lead",
			company: "Google DeepMind",
			quote:
				"The intellectual depth here is unmatched. Instead of surface-level takes, I'm engaging with people who actually understand the nuances of capabilities research. It's cut my time searching for signal in the noise by 70% and accelerated our team's thinking significantly.",
			image: "/generated/image-editorial-documentary-style-headshot-of-.webp"
		}
	]}
/>

<Features
	title="What makes us different"
	subtitle="Cultivating collective intelligence through curated experiences that go beyond shallow tech discourse."
	features={[
		{
			title: "Curated community",
			description:
				"Join a selective network of AI engineers and founders from leading labs. Quality conversations require quality participants."
		},
		{
			title: "Intimate salon discussions",
			description:
				"Small-group formats foster deep intellectual exchange where every voice matters and ideas can breathe."
		},
		{
			title: "AI-focused discourse",
			description:
				"Navigate the future of artificial intelligence with peers who are building it, not just talking about it."
		},
		{
			title: "Thought leadership platform",
			description:
				"Shape the conversation around AI's trajectory through rigorous dialogue that values insight over hot takes."
		},
		{
			title: "Expert networks",
			description:
				"Connect with founders and engineers who understand the technical depth and strategic implications of AI development."
		},
		{
			title: "Beyond surface level",
			description:
				"Escape content fatigue with substantive discussions that honor your expertise and intellectual curiosity."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Ready to elevate your thinking?"
	subtitle="Join the circle"
	description="Applications are reviewed monthly. We're currently welcoming AI engineers and founders from leading labs and startups who are ready to move beyond shallow discourse and engage with the meaningful questions shaping our field."
	imageSrc="/generated/image-editorial-documentary-style-photograph-o.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Apply for membership",
			variant: "primary"
		},
		{
			href: "/about",
			label: "Learn more",
			variant: "secondary"
		}
	]}
/>
