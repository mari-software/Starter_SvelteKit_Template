<script lang="ts">
	import MariLogoSvg from "$lib/asset/image/svg/MariLogoSvg.svelte";
	import DaisyUiBadge from "$lib/component/library/daisyui/badge/DaisyUiBadge.svelte";
	import DaisyUiButton from "$lib/component/library/daisyui/button/DaisyUiButton.svelte";
	import DaisyUiCardAction from "$lib/component/library/daisyui/card/body/action/DaisyUiCardBodyAction.svelte";
	import DaisyUiCardBody from "$lib/component/library/daisyui/card/body/DaisyUiCardBody.svelte";
	import DaisyUiCardBodyTitle from "$lib/component/library/daisyui/card/body/title/DaisyUiCardBodyTitle.svelte";
	import DaisyUiCardTitle from "$lib/component/library/daisyui/card/body/title/DaisyUiCardBodyTitle.svelte";
	import DaisyUiCard from "$lib/component/library/daisyui/card/DaisyUiCard.svelte";
	import DaisyUiCarousel from "$lib/component/library/daisyui/carousel/DaisyUiCarousel.svelte";
	import DaisyUiCarouselItem from "$lib/component/library/daisyui/carousel/item/DaisyUiCarouselItem.svelte";
	import DaisyUiChatBubbleContent from "$lib/component/library/daisyui/chat-bubble/content/DaisyUiChatBubbleContent.svelte";
	import DaisyUiChatBubble from "$lib/component/library/daisyui/chat-bubble/DaisyUiChatBubble.svelte";
	import DaisyUiChatBubbleFooter from "$lib/component/library/daisyui/chat-bubble/footer/DaisyUiChatBubbleFooter.svelte";
	import DaisyUiChatBubbleHeader from "$lib/component/library/daisyui/chat-bubble/header/DaisyUiChatBubbleHeader.svelte";
	import DaisyUiChatBubbleImage from "$lib/component/library/daisyui/chat-bubble/image/DaisyUiChatBubbleImage.svelte";
	import DaisyUiDropdownContent from "$lib/component/library/daisyui/dropdown/content/DaisyUiDropdownContent.svelte";
	import DaisyUiDropdown from "$lib/component/library/daisyui/dropdown/DaisyUiDropdown.svelte";
	import DaisyUiDropdownSummary from "$lib/component/library/daisyui/dropdown/summary/DaisyUiDropdownSummary.svelte";

</script>
<DaisyUiButton className="d-btn-primary" onClick={() => console.log("Hello")}>Button</DaisyUiButton>

<MariLogoSvg className="size-10" />

Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi laudantium ab illo esse ratione rerum enim facere reiciendis ut, sapiente corporis quas laborum, voluptates, neque veritatis fugiat voluptas veniam fugit!

<DaisyUiBadge className="d-badge-outline d-badge-error">Hello</DaisyUiBadge>


<DaisyUiCard>
	<DaisyUiCardBody>
		<DaisyUiCardTitle>Hello</DaisyUiCardTitle>
		<DaisyUiCardAction>
			<DaisyUiButton className="d-btn-primary" onClick={() => console.log("Hello")}>Button</DaisyUiButton>
		</DaisyUiCardAction>
	</DaisyUiCardBody>
</DaisyUiCard>

<DaisyUiCarousel className="w-full">
	<DaisyUiCarouselItem id="item1" className="w-full">
		<img
      src="https://img.daisyui.com/images/stock/photo-1625726411847-8cbb60cc71e6.webp"
      class="w-full" />
	</DaisyUiCarouselItem>
	<DaisyUiCarouselItem id="item2" className="w-full">
		<img
      src="https://img.daisyui.com/images/stock/photo-1414694762283-acccc27bca85.webp"
      class="w-full" />
	</DaisyUiCarouselItem>
</DaisyUiCarousel>

<DaisyUiChatBubble position="end">
	<DaisyUiChatBubbleImage>
		<img
        alt="Tailwind CSS chat bubble component"
        src="https://img.daisyui.com/images/profile/demo/kenobee@192.webp"
      />
	</DaisyUiChatBubbleImage>
	<DaisyUiChatBubbleHeader>
		Zarni Hlawn
	</DaisyUiChatBubbleHeader>
	<DaisyUiChatBubbleContent>
		Hello there
	</DaisyUiChatBubbleContent>
	<DaisyUiChatBubbleFooter>
		Delivered
	</DaisyUiChatBubbleFooter>
</DaisyUiChatBubble>

<div class="d-chat d-chat-end">
  <div class="d-chat-image d-avatar">
    <div class="w-10 rounded-full">
      <img
        alt="Tailwind CSS chat bubble component"
        src="https://img.daisyui.com/images/profile/demo/kenobee@192.webp"
      />
    </div>
  </div>
  <div class="d-chat-header">
    Obi-Wan Kenobi
    <time class="text-xs opacity-50">12:45</time>
  </div>
  <div class="d-chat-bubble">You were the Chosen One!</div>
  <div class="d-chat-footer opacity-50">Delivered</div>
</div>

<div class="chat chat-end">
  <div class="chat-image avatar">
    <div class="w-10 rounded-full">
      <img
        alt="Tailwind CSS chat bubble component"
        src="https://img.daisyui.com/images/profile/demo/anakeen@192.webp"
      />
    </div>
  </div>
  <div class="chat-header">
    Anakin
    <time class="text-xs opacity-50">12:46</time>
  </div>
  <div class="chat-bubble">I hate you!</div>
  <div class="chat-footer opacity-50">Seen at 12:46</div>
</div>

<DaisyUiDropdown>
	<DaisyUiDropdownSummary>
		<DaisyUiButton className="d-btn-primary" onClick={() => console.log("Hello")}>Button</DaisyUiButton>
	</DaisyUiDropdownSummary>
	<DaisyUiDropdownContent>
		<li><a>Item 1</a></li>
    	<li><a>Item 2</a></li>
	</DaisyUiDropdownContent>
</DaisyUiDropdown>

<details class="d-dropdown">
  <summary class="d-btn m-1">open or close</summary>
  <ul class="menu dropdown-content bg-base-100 rounded-box z-1 w-52 p-2 shadow-sm">
    <li><a>Item 1</a></li>
    <li><a>Item 2</a></li>
  </ul>
</details>