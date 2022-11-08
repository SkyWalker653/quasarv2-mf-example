<template>
  <q-page class="flex flex-center">
    <basic-component></basic-component>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'
import BasicComponent from 'RemoteApp1/BasicComponent'

export default defineComponent({
  name: 'IndexPage',
  components: { BasicComponent }
})
</script>
