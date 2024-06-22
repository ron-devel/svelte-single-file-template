<script>
  import "./app.css";
  import { AppBar } from "@skeletonlabs/skeleton";
  import { LightSwitch, SlideToggle } from "@skeletonlabs/skeleton";
</script>

<main>
  <AppBar
    gridColumns="grid-cols-3"
    slotDefault="place-self-center"
    slotTrail="place-content-end"
  >
    <svelte:fragment slot="lead">(icon)</svelte:fragment>
    (title)
    <svelte:fragment slot="trail">(actions)</svelte:fragment>
  </AppBar>
  <LightSwitch />
  <SlideToggle name="slider" checked active="bg-primary-500" size="sm" />
</main>
