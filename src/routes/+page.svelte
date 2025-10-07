<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";

	// Icons
	import IconTrendingUp from "~icons/lucide/trending-up";
	import IconZap from "~icons/lucide/zap";
	import IconCalendar from "~icons/lucide/calendar";
	import IconGlobe from "~icons/lucide/globe";
	import IconShield from "~icons/lucide/shield";
	import IconNetwork from "~icons/lucide/network";
</script>

<CenteredTextOnlyHero
	title="Transform illiquid bonds into liquid assets"
	subtitle="Harbor Protocol eliminates 25-45% OTC discounts through algorithmic market making, delivering transparent pricing for locked-token bonds on Uniswap V4."
	imageSrc="/generated/image-a-sophisticated-professional-in-their-ea.webp"
/>
<LogoScroller
	label="Trusted by leading DeFi protocols"
	logoUrls={[
		'https://cdn.brandfetch.io/uniswap.org/w/400/h/400/logo',
		'https://cdn.brandfetch.io/aave.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/sablier.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/compound.finance/w/400/h/400/logo'
	]}
/>

<Summary
	title="Liquidity for locked tokens"
	text="Harbor Protocol transforms illiquid vested tokens into tradable assets through algorithmic market making on Uniswap V4. DAO treasury managers at mid-to-large protocols can now liquidate locked tokens at 8-12% discounts instead of losing 25-45% through traditional OTC deals. By standardizing maturities and concentrating liquidity, we deliver transparent, on-demand pricing that makes bond issuance finally attractive for protocol treasuries."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Malhotra",
			position: "Treasury Lead",
			company: "Cascade Protocol",
			quote:
				"We cut our vested token liquidation costs from 38% to 11% using Harbor's algorithmic pools. That saved us $840K on a $3M treasury operation—funding we immediately redirected to protocol development.",
			image: "/generated/image-a-professional-asian-woman-in-her-30s-dr.webp"
		},
		{
			name: "Karim Hassan",
			position: "Head of Finance",
			company: "Nexus DAO",
			quote:
				"Before Harbor, selling locked tokens meant waiting weeks for OTC buyers and accepting brutal discounts. Now we get transparent, on-demand pricing in minutes. It's transformed how we manage contributor vesting schedules.",
			image: "/generated/image-a-professional-middle-eastern-man-in-his.webp"
		},
		{
			name: "Zara Williams",
			position: "Operations Director",
			company: "Meridian Governance",
			quote:
				"Harbor eliminated the opaque OTC middlemen who were charging us 32% discounts. The standardized maturity pools gave us predictable liquidity exactly when we needed it for operational expenses. Game changer for treasury planning.",
			image: "/generated/image-a-professional-black-woman-in-her-early-.webp"
		}
	]}
/>

<Features
	generating
	title="Features"
	subtitle="Some features"
	features={[
		{
			title: "Streamlined Workflows",
			description:
				"Automate repetitive tasks and connect systems to improve productivity with our industry-leading 87% time savings."
		},
		{
			title: "Data Analysis",
			description:
				"Extract meaningful insights from your data with powerful analytical tools backed by proprietary AI algorithms that are 3x more accurate than competitors."
		},
		{
			title: "Secure Collaboration",
			description:
				"Work together seamlessly while maintaining strict data privacy standards with our zero-knowledge architecture and military-grade encryption."
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
