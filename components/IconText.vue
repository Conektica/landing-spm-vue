<template>
  <div>
    <b-img :src="'/'+coverImg" class="mx-auto d-flex" fluid alt="SPM" />
    <div v-if="titleValid" class="title-red my-3">
      {{ titleText }}
    </div>
    <div class="text-center my-2 text-icon">
      {{ pText }}
    </div>
  </div>
</template>

<script>
export default {
  name: 'IconText',
  // eslint-disable-next-line vue/require-default-prop
  props: { coverImg: String, titleValid: Boolean, titleText: String, pText: String }
}
</script>

<style scoped>
.title-red{
  color:#DF0101;
  text-align: center;
  font-size: 26px;
}
.text-icon{
  font-size: 21px;
}
</style>
