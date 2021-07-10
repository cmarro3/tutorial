<template>
  <div id="app">
    {{msg}}
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  },
  data(){
    return {
      todos: [
        {
          
        }
      ]
    }
  }
}
</script>

<style>
 * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  body {
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.4;
  }
  /* .btn {
    display: inline-block;
    border: none;
    background: #555;
    color: #fff;
    padding: 7px 20px;
    cursor: pointer;
  }
  .btn:hover {
    background: #666;
  } */
</style>
