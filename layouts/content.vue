<template>
  <div class="bg-slate-50 dark:bg-slate-600 flex flex-col min-h-screen">
    <LayoutMainHeader />
    <section class="overflow-y-auto flex grow z-0">
      <slot />
    </section>
    <LayoutMainFooter />
  </div>
</template>

<script lang="ts" setup></script>
