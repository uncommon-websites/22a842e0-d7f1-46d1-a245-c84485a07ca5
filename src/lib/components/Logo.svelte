<script lang="ts">
	import type { HTMLAttributes } from "svelte/elements";
	const props: HTMLAttributes<SVGSVGElement> = $props();
</script>

<svg viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg" class="" {...props}>
	<!-- H lettermark with modern geometric style -->
	<path d="M8 6v20M24 6v20M8 16h16" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
	<!-- Accent dot representing AI/precision -->
	<circle cx="26" cy="8" r="2" fill="currentColor" opacity="0.6"/>
</svg>
