<script lang="ts">
	import MariLogoSvg from "$lib/asset/image/svg/MariLogoSvg.svelte";
	import DaisyUiBadge from "$lib/component/library/daisyui/badge/DaisyUiBadge.svelte";
	import DaisyUiBreadcrumbs from "$lib/component/library/daisyui/breadcrumbs/DaisyUiBreadcrumbs.svelte";
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
	import DaisyUiCollapseContent from "$lib/component/library/daisyui/collapse/content/DaisyUiCollapseContent.svelte";
	import DaisyUiCollapse from "$lib/component/library/daisyui/collapse/DaisyUiCollapse.svelte";
	import DaisyUiCollapseTitle from "$lib/component/library/daisyui/collapse/title/DaisyUiCollapseTitle.svelte";
	import DaisyUiCountdown from "$lib/component/library/daisyui/countdown/DaisyUiCountdown.svelte";
	import DaisyUiDropdownContent from "$lib/component/library/daisyui/dropdown/content/DaisyUiDropdownContent.svelte";
	import DaisyUiDropdown from "$lib/component/library/daisyui/dropdown/DaisyUiDropdown.svelte";
	import DaisyUiDropdownSummary from "$lib/component/library/daisyui/dropdown/summary/DaisyUiDropdownSummary.svelte";
	import DaisyUiKbd from "$lib/component/library/daisyui/kbd/DaisyUiKbd.svelte";
	import DaisyUiList from "$lib/component/library/daisyui/list/DaisyUiList.svelte";
	import DaisyUiListRow from "$lib/component/library/daisyui/list/row/DaisyUiListRow.svelte";
	import DaisyUiModalBox from "$lib/component/library/daisyui/modal/box/DaisyUiModalBox.svelte";
	import DaisyUiModal from "$lib/component/library/daisyui/modal/DaisyUiModal.svelte";
	import DaisyUiStats from "$lib/component/library/daisyui/stats/DaisyUiStats.svelte";
	import DaisyUiStatsStat from "$lib/component/library/daisyui/stats/stat/DaisyUiStatsStat.svelte";
	import DaisyUiStatsStatDesc from "$lib/component/library/daisyui/stats/stat/desc/DaisyUiStatsStatDesc.svelte";
	import DaisyUiStatsStatFigure from "$lib/component/library/daisyui/stats/stat/figure/DaisyUiStatsStatFigure.svelte";
	import DaisyUiStatsStatTitle from "$lib/component/library/daisyui/stats/stat/title/DaisyUiStatsStatTitle.svelte";
	import DaisyUiStatsStatValue from "$lib/component/library/daisyui/stats/stat/value/DaisyUiStatsStatValue.svelte";
	import DaisyUiStatus from "$lib/component/library/daisyui/status/DaisyUiStatus.svelte";
	import DaisyUiSwap from "$lib/component/library/daisyui/swap/DaisyUiSwap.svelte";
	import DaisyUiSwapOff from "$lib/component/library/daisyui/swap/off/DaisyUiSwapOff.svelte";
	import DaisyUiSwapOn from "$lib/component/library/daisyui/swap/on/DaisyUiSwapOn.svelte";
	import DaisyUiTableBody from "$lib/component/library/daisyui/table/body/DaisyUiTableBody.svelte";
	import DaisyUiTable from "$lib/component/library/daisyui/table/DaisyUiTable.svelte";
	import DaisyUiTableHeader from "$lib/component/library/daisyui/table/head/DaisyUiTableHeader.svelte";


	let showChat = false;
</script>

<DaisyUiBreadcrumbs>
	<li>
      <a>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          class="h-4 w-4 stroke-current">
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"></path>
        </svg>
        Home
      </a>
	  </li>
	  <li>
      <a>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          class="h-4 w-4 stroke-current">
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"></path>
        </svg>
        Home
      </a>
	  </li>
</DaisyUiBreadcrumbs>


<div class="overflow-x-auto">
<DaisyUiTable>
    <!-- head -->
	 <DaisyUiTableHeader>

		 <tr>
			 <th></th>
			 <th>Name</th>
			 <th>Job</th>
			 <th>Favorite Color</th>
			</tr>
		</DaisyUiTableHeader>
		<DaisyUiTableBody>

			<!-- row 1 -->
			<tr>
				<th>1</th>
				<td>Cy Ganderton</td>
				<td>Quality Control Specialist</td>
        <td>Blue</td>
      </tr>
      <!-- row 2 -->
      <tr>
        <th>2</th>
        <td>Hart Hagerty</td>
        <td>Desktop Support Technician</td>
        <td>Purple</td>
	</tr>
	<!-- row 3 -->
	<tr>
		<th>3</th>
        <td>Brice Swyre</td>
        <td>Tax Accountant</td>
        <td>Red</td>
	</tr>
</DaisyUiTableBody>
</DaisyUiTable>
</div>

<DaisyUiStatus effect="ping" className="d-status-error" />

<DaisyUiStats>
<DaisyUiStatsStat>
	<DaisyUiStatsStatFigure>
		<svg
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        class="inline-block h-8 w-8 stroke-current"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M13 16h-1v-4h-1m1-4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
        ></path>
      </svg>
	</DaisyUiStatsStatFigure>
	<DaisyUiStatsStatTitle>
		Downloads
	</DaisyUiStatsStatTitle>
	<DaisyUiStatsStatValue>
		31K
	</DaisyUiStatsStatValue>
	<DaisyUiStatsStatDesc>
		Jan 1st - Feb 1st
		</DaisyUiStatsStatDesc>
</DaisyUiStatsStat>
	</DaisyUiStats>	

<DaisyUiList>
	<DaisyUiListRow>
		<div class="text-4xl font-thin opacity-30 tabular-nums">01</div>
    <div><img class="size-10 rounded-box" src="https://img.daisyui.com/images/profile/demo/1@94.webp"/></div>
    <div class="d-list-col-grow">
      <div>Dio Lupa</div>
      <div class="text-xs uppercase font-semibold opacity-60">Remaining Reason</div>
    </div>
    <button class="d-btn d-btn-square d-btn-ghost">
      <svg class="size-[1.2em]" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g stroke-linejoin="round" stroke-linecap="round" stroke-width="2" fill="none" stroke="currentColor"><path d="M6 3L20 12 6 21 6 3z"></path></g></svg>
    </button>
	</DaisyUiListRow>
</DaisyUiList>

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

<button onclick={() => showChat = !showChat}>
            Toggle Chat Bubble ({showChat ? 'Hide' : 'Show'})
        </button>
{#if showChat}
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
{/if}

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
	<DaisyUiDropdownSummary className="d-btn-accent">
		Hello
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

<DaisyUiKbd>Ctrl</DaisyUiKbd>

<DaisyUiCollapse checked='false'  groupName="one">
	<DaisyUiCollapseTitle>
		HEllo
	</DaisyUiCollapseTitle>
	<DaisyUiCollapseContent>
		Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sint quaerat, nihil perferendis mollitia suscipit, blanditiis similique exercitationem tempora voluptate, incidunt quidem molestiae quo qui repellat laborum aliquid minima eum id!
	</DaisyUiCollapseContent>
</DaisyUiCollapse>

<DaisyUiCollapse checked='true' groupName="one">
	<DaisyUiCollapseTitle>
		HEllo
	</DaisyUiCollapseTitle>
	<DaisyUiCollapseContent>
		Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sint quaerat, nihil perferendis mollitia suscipit, blanditiis similique exercitationem tempora voluptate, incidunt quidem molestiae quo qui repellat laborum aliquid minima eum id!
	</DaisyUiCollapseContent>
</DaisyUiCollapse>

<!-- The button to open modal -->
<label for="my_modal_6" class="d-btn">open modal</label>

<!-- Put this part before </body> tag -->
<input type="checkbox" id="my_modal_6" class="d-modal-toggle" />
<div class="d-modal" role="dialog">
  <div class="d-modal-box">
    <h3 class="text-lg font-bold">Hello!</h3>
    <p class="py-4">This modal works with a hidden checkbox!</p>
    <div class="d-modal-action">
      <label for="my_modal_6" class="d-btn">Close!</label>
    </div>
  </div>
</div>

<label for="modal_1" class="d-btn">open modal</label>
<DaisyUiModal groupName="modal_1">
	<DaisyUiModalBox groupName="modal_1"> 
		<h3>Hello This is title</h3>
		<p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Cum minima animi, aliquam voluptatum aspernatur nemo tempore accusamus possimus ad id voluptatibus molestias provident voluptates impedit tempora soluta quae sunt ullam.</p>	
<DaisyUiButton className="d-btn-primary" onClick={() => console.log("Hello")}>Button</DaisyUiButton>
	      <label for="modal_1" class="d-btn d-btn-sm ">Cancel</label>
	</DaisyUiModalBox>
</DaisyUiModal>


<DaisyUiSwap >
	<DaisyUiSwapOn>😈</DaisyUiSwapOn>
	<DaisyUiSwapOff>😇</DaisyUiSwapOff>
</DaisyUiSwap>


<DaisyUiCountdown number="21" />

<span class="d-countdown font-mono text-2xl">
  <span style="--d-value:10;" aria-live="polite" aria-label="10">10</span>
  h
  <span style="--d-value:24;" aria-live="polite" aria-label="24">24</span>
  m
  <span style="--d-value:59;" aria-live="polite" aria-label="59">59</span>
  s
</span>

<span class="d-countdown font-mono text-2xl">
  <span style="--d-value:10;" aria-live="polite" aria-label="10">10</span>
  h
  <span style="--d-value:24;" aria-live="polite" aria-label="24">24</span>
  m
  <span style="--d-value:59;" aria-live="polite" aria-label="59">59</span>
  s
</span>