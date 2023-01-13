<script setup>
defineProps({
  href: String,
});
</script>

<template>
  <a
    :href="href"
    target="_blank"
    rel="noreferrer"
    class="underline hover:text-green-800 decoration-green-800 dark:hover:text-green-500 dark:decoration-green-500"
  >
    <slot />
  </a>
</template>
