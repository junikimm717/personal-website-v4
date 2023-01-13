<script setup lang="ts">
const links = [
  { href: "/", title: "Home" },
  { href: "/projects", title: "Projects" },
  { href: "/academic", title: "Academics" },
  { href: "/volunteering", title: "Volunteering" },
];
</script>
<template>
  <div
    class="flex flex-row flex-wrap items-center gap-3 py-2 text-base font-bold sm:text-lg"
  >
    <NuxtLink
      v-for="link in links"
      :href="link.href"
      class="font-bold hover:text-teal-800 hover:decoration-teal-800 dark:hover:text-teal-500 dark:hover:decoration-teal-500 hover:underline"
      exact-active-class="underline decoration-teal-800 dark:decoration-teal-500"
    >
      {{ link.title }}
    </NuxtLink>
  </div>
  <hr class="my-5 dark:border-gray-700" />
</template>
