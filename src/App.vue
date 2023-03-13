<template>
 <div>Hello {{ name }} </div>  
 <h1 v-bind:class="{red: isRed, italic: isItalic}"> Hi </h1>
 
</template>

<script>

export default {
  name: 'App',
  data() {
    return {
      name: "Mohammed",
      isRed: true,
      isItalic: true,

    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.red{
  color: red;

}

.italic{
  font-style: italic;
}
</style>
