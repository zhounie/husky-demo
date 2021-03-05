<template>
  <div>
    <div class="test">
      hhhhhh
      {{ msg }}
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      msg: 'hhhhhh'
    };
  },
  methods: {
    click() {
      this.msg = 'uuu';
    }
  }
};
</script>

<style>
.test {
  width: 200px;
  height: 200px;
}
</style>
