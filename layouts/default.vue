<template>
  <div>
    <UHorizontalNavigation :links="links" :ui="ui" />
    <slot />
  </div>
</template>

<script setup lang="ts">
import type { HorizontalNavigationLink } from "#ui/types";

const links: HorizontalNavigationLink[] = [
  {
    label: "Furniro",
    click: () => null,
  },
];

const ui = /* ui */ {
  wrapper: "bg-white",
};
</script>

<style></style>
