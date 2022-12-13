<template>
  <div id="Testview">
    <button @click="createroom">Create</button>
    <div class="container">
      <Test/>
    </div>
  </div>
</template>

<script>
import Test from '@/components/test.vue'

export default {
  name: 'testview',
  components: {
    Test
  },
  data() {
    return {
      roominfo: [
        {
          name: '',
          content: '',
          private: false,
        }

      ]
    }
  },

  methods: {
    createroom() {
      
    }
  }
}
</script>

<style scoped>
#Testview {
  display: auto;
}
.container {
  border: 1px solid black;
  width: 700px;
  height: 500px;
}

</style>