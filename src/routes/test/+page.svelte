<script lang="ts">
	import DaisyUiDropdownButton from "$lib/component/library/daisyui/dropdown/button/DaisyUiDropdownButton.svelte";
	import DaisyUiDropdownContent from "$lib/component/library/daisyui/dropdown/content/DaisyUiDropdownContent.svelte";
	import DaisyUiDropdown from "$lib/component/library/daisyui/dropdown/DaisyUiDropdown.svelte";


</script>

fdsf



<div class="d-dropdown d-dropdown-start">
  <div tabindex="0" role="button" class="d-btn m-1">Click ⬇️</div>
  <ul class="d-dropdown-content d-menu bg-base-100 z-1 w-52 p-2 shadow-sm">
    <li><a href="/">Item 1</a></li>
    <li><a href="/">Item 2</a></li>
  </ul>
</div>

<DaisyUiDropdown className="d-dropdown-start">
    <DaisyUiDropdownButton className="m-1">
        open
    </DaisyUiDropdownButton>
    <DaisyUiDropdownContent>
       <li><a href="/">Item 1</a></li>
    <li><a href="/">Item 2</a></li>
       <li><a href="/">Item 1</a></li>
    <li><a href="/">Item 2</a></li>
    </DaisyUiDropdownContent>
</DaisyUiDropdown>