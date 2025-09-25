<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	centered={false}
	title="Effortless style for modern wardrobes"
	subtitle="Curated essentials that actually sell through. We partner with contemporary boutiques to identify seasonless pieces that drive sales and delight customers."
	imageSrc="/generated/image-a-group-of-professional-fashion-stylists.webp"
/>
<LogoScroller 
	label="Trusted by leading fashion retailers"
	logoUrls={[
		'https://cdn.brandfetch.io/net-a-porter.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/ssense.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/matchesfashion.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/farfetch.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Mei-Lin Chen",
			position: "Fashion Buyer",
			company: "Nordstrom Contemporary",
			quote:
				"ONE OF OTHERS cut our seasonal buying time by 40%. Their curated selections consistently sell through at 85% rates, compared to our previous 60% average.\nNo more risky gambles on trends that don't translate to sales.",
			image: "/generated/image-professional-headshot-of-a-confident-asi.webp"
		},
		{
			name: "Keisha Williams",
			position: "Head Stylist",
			company: "Revolve Group",
			quote:
				"Their seasonless pieces solved our biggest challenge - creating versatile looks that work year-round. We've reduced our styling prep time by 50%.\nClients love the investment pieces that work across multiple seasons and occasions.",
			image: "/generated/image-professional-headshot-of-a-confident-bla.webp"
		},
		{
			name: "Isabella Rodriguez",
			position: "Buying Director",
			company: "Net-A-Porter Contemporary",
			quote:
				"The quality-to-price ratio is unmatched. We've seen 30% higher margins and virtually zero returns on their pieces.\nOur inventory moves faster, and customers keep coming back for more from these collections.",
			image: "/generated/image-professional-headshot-of-a-confident-his.webp"
		}
	]}
/>

<Features
	title="Why buyers choose us"
	subtitle="Strategic advantages that drive sales and delight customers"
	features={[
		{
			title: "Curated seasonless essentials",
			description: "Our expert buyers identify versatile pieces that transcend trends, ensuring every item moves through inventory quickly while building customer loyalty.",
			imageSrc: "/generated/image-a-fashion-buyer-thoughtfully-examining-m.webp"
		},
		{
			title: "Proven sales performance",
			description: "Each piece is selected based on data-driven insights from successful retailers, guaranteeing higher sell-through rates and reduced markdowns.",
			imageSrc: "/generated/image-a-clean-organized-retail-space-with-cont.webp"
		},
		{
			title: "Expert styling guidance",
			description: "Our stylists provide complete outfit coordination and merchandising recommendations that help your customers visualize complete looks.",
			imageSrc: "/generated/image-a-fashion-stylist-arranging-a-selection-.webp"
		},
		{
			title: "Premium quality assurance",
			description: "Every garment meets strict quality standards for fabric, construction, and fit, ensuring customer satisfaction and minimizing returns.",
			imageSrc: "/generated/image-a-contemporary-fashion-buyer-reviewing-q.webp"
		},
		{
			title: "Trend forecasting insights",
			description: "Access early trend intelligence and market analysis that keeps your inventory ahead of customer demand while maintaining timeless appeal.",
			imageSrc: "/generated/image-a-professional-fashion-trend-analysis-wo.webp"
		},
		{
			title: "Flexible ordering terms",
			description: "Minimum orders designed for boutiques with seasonal payment terms and exchange policies that reduce financial risk.",
			imageSrc: "/generated/image-a-modern-boutique-interior-featuring-a-c.webp"
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
