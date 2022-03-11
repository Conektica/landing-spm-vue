<template>
  <ul class="list-red">
    <li v-for="(item, index) in itemsList" :key="index">
      {{ item }}
    </li>
  </ul>
</template>

<script>
export default {
  name: 'ItemsList',
  // eslint-disable-next-line vue/require-default-prop
  props: { itemsList: Array }
}
</script>

<style scoped>
ul {
  list-style: none;
}
.list-red > li::before{
  content: "\2022";
  color: #DF0101;
  padding: .2rem;
  line-height: 17px;
  font-size: 35px;
  vertical-align: -4px;
}
</style>
