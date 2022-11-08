<template>
  <q-page class="flex flex-center">

    <basic-component></basic-component>

  </q-page>
</template>

<script>
import { defineComponent } from 'vue'
import BasicComponent from '../components/BasicComponent.vue'

export default defineComponent({
  components: { BasicComponent },
  name: 'IndexPage'
})
</script>
