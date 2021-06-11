<script lang="ts">
 export let title="hogehoge" ;
 export let category="hogehoge" ;
 export let description="hogehoge" ;
</script>

<div class="p-4 md:w-1/3">
  <div class="bg-white rounded-lg h-full overflow-hidden">
    <img class="object-cover object-center w-full lg:h-48 md:h-36" src="https://dummyimage.com/720x400" alt="blog">
    <div class="p-6">
      <h2 class="font-medium text-xs mb-1 tracking-widest text-gray-400 title-font">{category}</h2>
      <h1 class="font-medium text-lg mb-3 text-gray-900 title-font">{title}</h1>
      <p class="leading-relaxed mb-3">{description}</p>
      <div class="flex flex-wrap items-center">
        <a href="/" class="text-indigo-500 inline-flex items-center hover:opacity-60 md:mb-2 lg:mb-0">Learn More
          <svg class="h-4 ml-2 w-4" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round">
            <path d="M5 12h14"></path>
            <path d="M12 5l7 7-7 7"></path>
          </svg>
        </a>
        <span class="ml-auto border-r-2 border-gray-200 mr-3 text-sm leading-none py-1 pr-3 text-gray-400 inline-flex items-center lg:ml-auto md:ml-0">
          <svg class="h-4 mr-1 w-4" stroke="currentColor" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round" viewBox="0 0 24 24">
            <path d="M1 12s4-8 11-8 11 8 11 8-4 8-11 8-11-8-11-8z"></path>
            <circle cx="12" cy="12" r="3"></circle>
          </svg>1.2K
        </span>
        <span class="text-sm leading-none text-gray-400 inline-flex items-center">
          <svg class="h-4 mr-1 w-4" stroke="currentColor" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round" viewBox="0 0 24 24">
            <path d="M21 11.5a8.38 8.38 0 01-.9 3.8 8.5 8.5 0 01-7.6 4.7 8.38 8.38 0 01-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 01-.9-3.8 8.5 8.5 0 014.7-7.6 8.38 8.38 0 013.8-.9h.5a8.48 8.48 0 018 8v.5z"></path>
          </svg>6
        </span>
      </div>
    </div>
  </div>
</div>