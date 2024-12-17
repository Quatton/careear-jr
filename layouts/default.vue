<template>
  <header
    class="left-1/2 -translate-x-1/2 w-5/6 max-w-6xl rounded fixed top-8 z-40 border border-gray-300 bg-background/80 backdrop-blur-sm"
  >
    <NuxtLink class="flex h-16 items-center px-4" to="/">
      <div class="text-2xl font-semibold text-primary-600">Careear</div>
    </NuxtLink>
  </header>
  <main class="flex flex-col items-center h-screen overflow-y-auto pt-40">
    <slot />
  </main>
  <footer
    class="flex justify-center items-center h-16 bg-background/80 text-white"
  >
    <!-- <div>© 2024 Careear</div> -->
  </footer>
</template>
