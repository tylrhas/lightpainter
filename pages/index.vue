<template>
    <div>
      <appHeader />
      <b-container>
        <h1>Content</h1>
      </b-container>
      <appFooter />
    </div>
</template>

<script>
import appHeader from '~/components/header.vue'
import appFooter from '~/components/footer.vue'
export default {
  components: {
    appHeader,
    appFooter
  }
}
</script>
