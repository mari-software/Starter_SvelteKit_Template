<!-- How To -->
<!-- 

-->

<script lang="ts">
	let { className, children } = $props<{
		className?: string;
		children: () => void;
	}>();
</script>

<div class="d-avatar">
	<div class="d-mask {className}">
		{@render children()}
	</div>
</div>
