<template>
  <header>
    <p>Header content</p>
    <ul>
      <li><nuxt-link to="/about">About</nuxt-link></li>
      <li><nuxt-link to="/inform">Inform</nuxt-link></li>
      <li><NuxtLink to="/about">About 1</NuxtLink></li>
      <li><NuxtLink to="/users/123">User</NuxtLink></li>
    </ul>
  </header>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
  <footer>Footer content</footer>
</template>
