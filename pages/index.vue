<script setup lang="ts">

</script>

<template>
  <main class="flex flex-col items-center justify-center gap-5 bg-gray-900 text-white min-h-screen w-full p-4 text-center">
    <h1 class="text-3xl">Nuxt3 + Tailwind + Nerdfonts (icons)</h1>
    <p class="text-lg">This is a simple example of how to use Tailwind CSS and Nerdfonts in a Nuxt3 project along with some button themes.</p>
    <div class="flex flex-col items-center justify-center gap-2">
      <h2 class="text-2xl">Icon group</h2>
      <div class="flex flex-wrap flex-row items-center justify-center gap-2 text-3xl text-blue-300">
        <Icon name="nf-cod-github" class="duration-200 hover:text-blue-600"></Icon>
        <Icon name="nf-fa-discord" class="duration-200 hover:text-blue-600"></Icon>
        <Icon name="nf-oct-link" class="duration-200 hover:text-blue-600"></Icon>
      </div>
    </div>
    <div class="flex flex-col items-center justify-center gap-2">
      <h2 class="text-2xl">Primary Variant</h2>
      <div class="flex flex-wrap flex-row gap-2 items-center justify-center">
        <Button variant="primary" size="sm">Small</Button>
        <Button variant="primary" size="md">Medium</Button>
        <Button variant="primary" size="lg">Large</Button>
        <Button variant="primary" size="md" disabled>Disabled</Button>
      </div>
    </div>
    <div class="flex flex-col items-center justify-center gap-2">
      <h2 class="text-2xl">Secondary Variant</h2>
      <div class="flex flex-wrap flex-row gap-2 items-center justify-center">
        <Button variant="secondary" size="sm">Small</Button>
        <Button variant="secondary" size="md">Medium</Button>
        <Button variant="secondary" size="lg">Large</Button>
        <Button variant="secondary" size="md" disabled>Disabled</Button>
      </div>
    </div>
    <div class="flex flex-col items-center justify-center gap-2">
      <h2 class="text-2xl">Warning Variant</h2>
      <div class="flex flex-wrap flex-row gap-2 items-center justify-center">
        <Button variant="danger" size="sm">Small</Button>
        <Button variant="danger" size="md">Medium</Button>
        <Button variant="danger" size="lg">Large</Button>
        <Button variant="danger" size="md" disabled>Disabled</Button>
      </div>
    </div>
    <div class="flex flex-col items-center justify-center gap-2">
      <h2 class="text-2xl">Danger Variant</h2>
      <div class="flex flex-wrap flex-row gap-2 items-center justify-center">
        <Button variant="warning" size="sm">Small</Button>
        <Button variant="warning" size="md">Medium</Button>
        <Button variant="warning" size="lg">Large</Button>
        <Button variant="warning" size="md" disabled>Disabled</Button>
      </div>
    </div>
    <div class="flex flex-col items-center justify-center gap-2">
      <h2 class="text-2xl">Icon Button</h2>
      <div class="flex flex-wrap flex-row gap-2 items-center justify-center">
        <Button variant="icon" size="md"><Icon name="nf-oct-link" /></Button>
        <Button variant="icon" size="md" disabled><Icon name="nf-oct-link" /></Button>
      </div>
    </div>
  </main>
</template>