<template>
  <h1 class="text-4xl font-extrabold">Juni Kim</h1>
  <main class="grid grid-flow-row grid-cols-1 gap-5 my-5 md:grid-cols-2">
    <nuxt-img
      src="/profile.jpg"
      width="300"
      class="w-40 rounded-xl"
      alt="Profile Photo"
    />
    <p>
      Welcome to the fourth version of my website! I am a junior at Stanford
      Online High School, a web development enthusiast, and a researcher
      computationally exploring human communication.
    </p>
  </main>
  <hr class="my-5 dark:border-gray-700" />
  <h1 class="text-4xl font-extrabold">Contacts</h1>
  <main class="my-5">
    <ul class="list-disc list-inside">
      <li><CustomLink href="/files/Resume.pdf"> Resume </CustomLink></li>
      <li>
        <CustomLink href="mailto:junikimm717@gmail.com"> Email </CustomLink>
      </li>
      <li>
        <CustomLink href="https://github.com/junikimm717"> GitHub </CustomLink>
      </li>
      <li>
        <CustomLink href="https://gitlab.com/junikimm717"> GitLab </CustomLink>
      </li>
      <li>
        <CustomLink href="https://www.linkedin.com/in/junickim/">
          LinkedIn
        </CustomLink>
      </li>
    </ul>
  </main>
</template>
