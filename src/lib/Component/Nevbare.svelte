<header class=" bg-gray-100 sm:flex justify-between sm:px-4 sm:py-3 border-b-4">
	<div class="flex items-center justify-between  bg-gray-100 px-4 py-3 sm:p-0">	
		<a href="/">
		<div class="flex justify-center items-center text-base text-gray-700 hover:text-black font-bold">
		<p class="pl-2 text-base hover:text-blue-300 font-bold">MS Hygiene Solution</p>
		</div>
	</a>
	<div class="sm:hidden">
		<button type="button" class="text-gray-700" on:click={() => isC = !isC} >
			<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="h-7 fill-current hover:text-black">
				{#if isC}
				<path stroke-linecap="round" stroke-linejoin="round" d="M3.75 5.25h16.5m-16.5 4.5h16.5m-16.5 4.5h16.5m-16.5 4.5h16.5" />
				{:else}
				<path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
				{/if}
			</svg>  
		</button>
	</div>
</div>
	<div  class:hidden ={isC}
	class="px-2 pt-2 pb-4 sm:flex" >
		<a href="/about" class="block text-gray-700 hover:bg-gray-400 rounded px-2 font-semibold">Product</a>
		<a href="/about" class="block text-gray-700 hover:bg-gray-400 rounded px-2 font-semibold sm:ml-2">Services</a>
		<a href="/about" class="block text-gray-700 hover:bg-gray-400 rounded px-2 font-semibold sm:ml-2">About Us</a>
		<a href="/about" class="block text-gray-700 hover:bg-gray-400 rounded px-2 font-semibold sm:ml-2">Contect Us</a>
	</div>
</header>



<script>
	let isC = true;
</script>