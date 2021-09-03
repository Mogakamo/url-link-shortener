<template>
  <div class="input">
    <b-input-group>
      <template #prepend>
        <b-input-group-text class="prepend">link</b-input-group-text>
      </template>
      <div class="form-input">
        <b-form-input></b-form-input>
      </div>
      <template #append>
        <b-input-group-append>
          <b-button variant="info" class="append text-white">shorten</b-button>
        </b-input-group-append>
      </template>
    </b-input-group>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.input {
  grid-column-start: 2;
  grid-column-end: span 2;
  grid-row-start: 1;
  text-transform: uppercase;
}
.text-white {
  color: #fff;
}
.form-input {
  border-radius: 45px;
  padding-left: 10px;
  padding-right: 10px;
  display: flex;
  flex-direction: column;
  width: 75%;
}
.append {
  border-radius: 50px;
  background-color: rgb(56, 209, 36);
}
.prepend {
  color: #000;
}
</style>
