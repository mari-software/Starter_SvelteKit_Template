<!-- How To -->
<!-- 
<DaisyUiAlert show={showAlert} className="d-alert-error">
	<LucideXCircle />
	<p>Error On Line Number 32.</p>
</DaisyUiAlert> 
-->

<script lang="ts">
	import { fade, fly } from 'svelte/transition';

	let {
		show = false,
		className,
		children
	} = $props<{
		show: boolean;
		className?: string;
		children?: () => void;
	}>();
</script>

{#if show}
	<div
		role="alert"
		class="d-alert {className} absolute top-20 left-1/2 mx-auto w-[70vw] -translate-x-1/2"
		in:fly={{ y: -100, duration: 100 }}
		out:fade={{ duration: 100 }}
	>
		{@render children()}
	</div>
{/if}