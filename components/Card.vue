<script setup lang="ts">
defineProps({
  href: String,
  title: String,
  tags: Array<String>,
});
</script>

<template>
  <div class="p-3 my-2 border border-gray-300 rounded-2xl">
    <a
      v-bind:href="href"
      class="text-2xl font-bold underline hover:text-green-800 decoration-green-800 dark:hover:text-green-500 dark:decoration-green-500"
      target="_blank"
      rel="noreferrer"
    >
      {{ title }}
    </a>
    <div class="flex flex-row flex-wrap">
      <span
        class="p-[5px] m-1 bg-gray-200 rounded-full dark:bg-gray-600 text-sm first:ml-0 last:mr-0"
        v-for="tag in tags"
      >
        {{ tag }}
      </span>
    </div>
    <p>
      <slot />
    </p>
  </div>
</template>
