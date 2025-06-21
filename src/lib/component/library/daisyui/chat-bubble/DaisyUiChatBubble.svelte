<script lang="ts">
	let { position , children, className } = $props<{
        position: 'start' | 'end';
		className?: string;
		children: () => void;
	}>();
</script>

<div  class="d-chat d-chat-{position} {className}">
	{@render children()}
</div>