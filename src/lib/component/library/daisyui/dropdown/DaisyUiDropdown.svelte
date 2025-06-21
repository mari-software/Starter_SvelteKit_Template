<script lang="ts">
	let {   children, className } = $props<{
		className?: string;
		children: () => void;
	}>();
</script>

<details class="d-dropdown  {className}" open>
  {@render children()}
</details>