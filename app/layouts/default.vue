<template>
  <div>
    <UHeader>
      <template #title>
        <NuxtImg src="~/assets/images/nuxt-starter-logo.png" alt="Your Logo" class="h-12 my-1" />
      </template>

      <template #right>
        <UColorModeButton />
      </template>
    </UHeader>

    <UMain>
      <slot />
    </UMain>

    <UFooter />
  </div>
</template>
