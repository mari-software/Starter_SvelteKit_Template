<!-- How To -->
<!--
<DaisyUiAvatar className="d-mask-heart">
	<img
		src="https://img.daisyui.com/images/profile/demo/distracted3@192.webp"
		alt="example"
	/>
</DaisyUiAvatar>
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
