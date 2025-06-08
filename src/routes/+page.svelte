<script lang="ts">
	import DaisyUiAlert from '$lib/component/library/daisyui/DaisyUIAlert.svelte';
	import DaisyUiAvatar from '$lib/component/library/daisyui/DaisyUIAvatar.svelte';
	import { LucideXCircle } from '@lucide/svelte';

	let showAlert = false;

	function toggleAlert() {
		showAlert = !showAlert;
	}
</script>

<h1>Welcome to SvelteKit</h1>
<p>
	Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to
	read the documentation
</p>
<button onclick={toggleAlert}>Toggle Alert</button>

<DaisyUiAlert show={showAlert} className="d-alert-error">
	<LucideXCircle />
	<p>Error On Line Number 32.</p>
</DaisyUiAlert>

<DaisyUiAvatar></DaisyUiAvatar>
