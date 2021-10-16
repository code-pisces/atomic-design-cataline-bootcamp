<template>
  <div class="services">
    <Service
      title="Front End"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur cupiditate tempore perferendis quidem! Possimus quibusdam doloribus ex voluptas. Tempore dolor quod nemo error ut architecto facilis fugiat consequatur veniam. Nisi!"
    />
    <Service
      title="Back End"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur cupiditate tempore perferendis quidem! Possimus quibusdam doloribus ex voluptas. Tempore dolor quod nemo error ut architecto facilis fugiat consequatur veniam. Nisi!"
    />
    <Service
      title="Manutenção"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur cupiditate tempore perferendis quidem! Possimus quibusdam doloribus ex voluptas. Tempore dolor quod nemo error ut architecto facilis fugiat consequatur veniam. Nisi!"
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
