<template>
  <div class="">
    <titleHeader :title="title" :subTitle="subTitle" />
    <animateExamples/>
  </div>
</template>

<script>
  import titleHeader from '@/components/titleHeader'
  import animateExamples from '@/pages/home/components/animate-example'

export default {
    components: {
      titleHeader,
      animateExamples
    },
    data () {
      return {
        title: 'Flexbox Grid',
        subTitle: 'Atomic design, bootstrap compatible, pure flexbox atomic design, pure flexbox.'
      }
    }
  }
</script>

<style lang="scss">
</style>
