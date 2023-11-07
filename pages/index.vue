<template>
  <div>
    <h1 id="top">Scroll allllll the way down</h1>
    <div v-for="i in 100" :key="i" class="filler">Filler Div</div>
    <div>
      <NuxtLink to="#top">
        <button>To top with NuxtLink to="#top"</button>
      </NuxtLink>
    </div>
    <div>
      <NuxtLink to="/">
        <button>Click to test scroll to top on same page</button>
      </NuxtLink>
    </div>
  </div>
</template>
