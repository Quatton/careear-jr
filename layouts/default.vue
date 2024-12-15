<template>
  <header
    class="left-1/2 -translate-x-1/2 w-5/6 max-w-6xl rounded fixed top-8 z-40 border border-gray-300 bg-background/80 backdrop-blur-sm"
  >
    <NuxtLink class="flex h-16 items-center px-4" to="/">
      <div class="text-2xl font-semibold text-primary-700">careear</div>
    </NuxtLink>
  </header>
  <main class="flex flex-col items-center h-screen overflow-y-auto pt-40">
    <slot />
  </main>
</template>
