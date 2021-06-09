<template>
  <div class="services">
    <Service
      title="Frond-end"
      description=" Lorem ipsum, dolor sit amet consectetur adipisicing elit. Tempore quidem qui doloribus dolor voluptates beatae necessitatibus deleniti! Dignissimos rerum aspernatur, quasi optio exercitationem officia dicta, tenetur neque quod adipisci repellat?"
    />

    <Service
      title="Back-end"
      description=" Lorem ipsum, dolor sit amet consectetur adipisicing elit. Tempore quidem qui doloribus dolor voluptates beatae necessitatibus deleniti! Dignissimos rerum aspernatur, quasi optio exercitationem officia dicta, tenetur neque quod adipisci repellat?"
    />

    <Service
      title="Manutenção"
      description=" Lorem ipsum, dolor sit amet consectetur adipisicing elit. Tempore quidem qui doloribus dolor voluptates beatae necessitatibus deleniti! Dignissimos rerum aspernatur, quasi optio exercitationem officia dicta, tenetur neque quod adipisci repellat?"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'
export default defineComponent({
  components: {
    Service
  }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>