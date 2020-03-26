<template>
  <div class="home">
    <ImgCropper ref="cropper" :src="src" />
  </div>
</template>

<script>
import ImgCropper from '@/components/ImgCropper.vue'
const url = 'http://s02.lmbang.com/M00/CA/E1/ecloD1x1VISAGMIqAAA_NA0XMO8010.jpg'
export default {
  name: 'Home',
  components: { ImgCropper },
  data() {
    return {
      src: url
      // src:
      //   'https://public.data.dev.dt-pf.com/upload/jpg/c1/fa/c1faf97625e1b2d142fedc10d1440082/src/c1faf97625e1b2d142fedc10d1440082.jpg'
    }
  },
  methods: {}
}
</script>
<style lang="less" scoped></style>
