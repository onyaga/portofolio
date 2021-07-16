<template>
  <footer class="footer">
    <div class="footer__inner">
      <Nav/>
      <Sns/>
      <p class="copy"><small>&copy; Nagamatsu.</small></p>
    </div>
  </footer>
</template>

<script>
import Nav from '@/components/Nav.vue'
import Sns from '@/components/Sns.vue'

export default {
  name: 'Footer',
  components: {
    Nav,
    Sns
  }
}
</script>
