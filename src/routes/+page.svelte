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
	import IconTrendingDown from "~icons/lucide/trending-down";
	import IconZap from "~icons/lucide/zap";
	import IconNetwork from "~icons/lucide/network";
	import IconLayers from "~icons/lucide/layers";
	import IconCalendarClock from "~icons/lucide/calendar-clock";
	import IconShield from "~icons/lucide/shield";
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
	title="Unlocking liquidity in DeFi treasury markets"
	text="Harbor Protocol transforms locked-token bonds into instantly tradable assets through algorithmic market making on Uniswap V4. We serve DAO treasury managers at mid-to-large protocols who need to liquidate vested tokens without losing 25-45% to traditional OTC discounts. Our platform delivers transparent, on-demand pricing that reduces typical discounts from 35% down to 8-12%, unlocking access to the $18.4B DAO treasury market."
/>

<Testimonials
	testimonials={[
		{
			name: "Mei Chen",
			position: "Treasury Lead",
			company: "Quantum DAO",
			quote:
				"We needed to liquidate $4.2M in vested tokens for operational expenses. Harbor cut our discount from 38% to just 11%, saving us over $1.1M that stayed in our treasury.",
			image: "/generated/image-medium-shot-of-a-professional-asian-woma.webp"
		},
		{
			name: "Marcus Thompson",
			position: "Head of Finance",
			company: "Nexus Protocol",
			quote:
				"Traditional OTC deals took weeks to negotiate and locked us into unfavorable terms. Harbor's transparent pricing gave us instant liquidity and eliminated counterparty risk entirely.",
			image: "/generated/image-medium-shot-of-a-professional-black-man-.webp"
		},
		{
			name: "Layla Rahman",
			position: "Treasury Operations",
			company: "Cascade Finance",
			quote:
				"Before Harbor, we were losing 42% on locked token sales. Now we access liquidity at 9% discount while maintaining full control over our vesting schedules.",
			image: "/generated/image-medium-shot-of-a-professional-middle-eas.webp"
		}
	]}
/>

<Features
	title="Built for efficiency and scale"
	subtitle="Harbor Protocol transforms locked-token bonds into liquid assets through algorithmic innovation and strategic infrastructure"
	features={[
		{
			title: "Transparent algorithmic pricing",
			description:
				"Our proprietary market-making algorithms reduce typical OTC discounts from 35% down to 8-12%, delivering unprecedented pricing efficiency for locked-token bonds.",
			icon: IconTrendingDown
		},
		{
			title: "Instant liquidity access",
			description:
				"Transform illiquid vested tokens into tradable assets on-demand, eliminating the friction and delays of traditional OTC markets.",
			icon: IconZap
		},
		{
			title: "Multi-chain infrastructure",
			description:
				"Built on Uniswap V4 with EVM compatibility, Harbor Protocol deploys seamlessly across multiple blockchain networks for maximum reach and flexibility.",
			icon: IconNetwork
		},
		{
			title: "Strategic ecosystem integrations",
			description:
				"Native integrations with Sablier, Superfluid, and Hedgy provide access to $1.6B combined TVL, positioning Harbor at the center of DeFi's locked-token ecosystem.",
			icon: IconLayers
		},
		{
			title: "Standardized maturity pools",
			description:
				"Monthly and quarterly maturity standards concentrate liquidity and eliminate fragmentation, creating deeper markets and better pricing for all participants.",
			icon: IconCalendarClock
		},
		{
			title: "Hedged yield products",
			description:
				"Harbor vaults deliver 15% APY through sophisticated hedging strategies, attracting capital providers and ensuring consistent liquidity depth.",
			icon: IconShield
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
