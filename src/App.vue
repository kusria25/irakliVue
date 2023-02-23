<script >
import List from './List.vue'
export default {
  components: {
    List
  },
  data() {
    return {
      pagTitle: 'my first list',
      myList: [
        {
          id: 1,
          title: 'pirveli listi'
        },
        {
          id: 2,
          title: 'meore listi'
        },
        {
          id: 3,
          title: 'mesame listi'
        }
      ]
    }
  }
}
</script>
<template>
  <div class="">
    <h1>{{ pagTItle }}</h1>
    List: list_item=myList

  </div>
</template>