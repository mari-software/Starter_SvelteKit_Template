<script>
	import DaisyUiButton from "$lib/component/library/daisyui/button/DaisyUiButton.svelte";
	import DaisyUiDropdownContent from "$lib/component/library/daisyui/dropdown/content/DaisyUiDropdownContent.svelte";
	import DaisyUiDropdown from "$lib/component/library/daisyui/dropdown/DaisyUiDropdown.svelte";
	import DaisyUiDropdownSummary from "$lib/component/library/daisyui/dropdown/button/DaisyUiDropdownButton.svelte";
	import LucideX from "$lib/component/library/lucide/LucideX.svelte";

</script>
<DaisyUiDropdown>
    <DaisyUiDropdownSummary className="d-btn-circle" >
        <LucideX />
    </DaisyUiDropdownSummary>
    <DaisyUiDropdownContent>
        <li>
            Hello
        </li>

        <li>
            Hello
        </li>
    </DaisyUiDropdownContent>
</DaisyUiDropdown>