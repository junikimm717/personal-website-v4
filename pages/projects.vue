<template>
  <h1 class="text-4xl font-extrabold">Projects</h1>
  <main class="my-5">
    <Card
      href="https://search.maatester.com"
      title="Search.MAATester.com"
      v-bind:tags="['Go', 'Redis', 'React']"
    >
      An Instant Search Engine for Math Olympiads written over Winter 2022.
      Powered by the AoPS Forums and supports virtually all significant
      mathematical olympiads.
    </Card>
    <Card
      href="https://maatester.com"
      title="MAATester.com"
      v-bind:tags="['Math', 'Firebase', 'React']"
    >
      An Integrated Testing Environment for Math Contests for taking mock
      contests and saving progress. Powered by the AoPS Wiki.
    </Card>
    <Card
      href="https://texbld.com"
      title="TeXbld"
      v-bind:tags="['Docker', 'Python', 'Reproducibility']"
    >
      A build tool for reproducible markdown. Capable of scaffolding, building,
      and testing templates and projects.
    </Card>
    <Card
      href="https://ohsmathc.club"
      title="OHS Math Club Website"
      v-bind:tags="['Django', 'Postgres']"
    >
      A simple site for keeping track of contests, announcements, and
      registrations.
    </Card>
    <Card
      href="https://github.com/junikimm717/mt"
      title="mt"
      v-bind:tags="['Rust']"
    >
      A minimalistic meeting launcher for a weekly schedule, configurable and
      usable in scripts.
    </Card>

    <Card
      href="https://github.com/junikimm717/problemportal"
      title="ProblemPortal"
      v-bind:tags="['Node', 'Mongo', 'Oauth']"
    >
      A website designed for efficiently handing out custom problemsets. Full
      KaTeX support.
    </Card>
  </main>
</template>
