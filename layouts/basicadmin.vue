<template>
  <Default>
    <Toolbar />
    <slot />
  </Default>
</template>
<script>
import Default from "@/layouts/default"
import Toolbar from "@/components/Toolbar"
export default {
  components: {
    Default,
    Toolbar,
  },
}
</script>
