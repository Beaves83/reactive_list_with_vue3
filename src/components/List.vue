<template>
  <div>{{ elements }}</div>
  <!-- <div class="lista_elementos">No hay elementos.</div> -->
</template>

<script>
export default {
  name: 'List',
  props: {
    elements: String,
  },
  // setup(props) {
  //   return () => {
  //     props.elements;
  //   };
  // },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
