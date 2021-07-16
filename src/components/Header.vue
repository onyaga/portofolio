<template>
  <header class="header">
    <div class="header__inner">
      <Nav></Nav>
    </div>
  </header>
</template>

<script>
import Nav from '@/components/Nav.vue'

export default {
  name: 'Header',
  components: {
    Nav
  }
}
</script>
