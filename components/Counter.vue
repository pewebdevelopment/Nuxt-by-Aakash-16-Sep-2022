<template>

  <div>
    <button @click="increament">Increament</button>
  
    <p>{{count }}</p>
  
    <button @click="decreament">Decreament</button>
  </div>
</template>   
  
  <script>
    
    export default {
      data() {
        return {
          count: 0,
        };
      },
      methods: {
        increament() {
          this.count++;
        },
        decreament() {
          this.count--;
        },
      },
    };
  
  // const count = ref(0);
  
  // function increament() {
  //   count.value++;
  // }
  
  // function decreament() {
  //   count.value--;
  // }
  </script>