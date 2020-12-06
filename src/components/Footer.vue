<template>
  <footer class="main-footer">
    <h3>DivTag Microservices/ API</h3>
    <ul>
      <li><a href="#" target="_blank" rel="noopener">Events</a></li>
      <li><a href="#" target="_blank" rel="noopener">Members</a></li>
      <li><a href="#" target="_blank" rel="noopener">Blog</a></li>
      <li><a href="#" target="_blank" rel="noopener">Organization</a></li>
      <li><a href="#" target="_blank" rel="noopener">Showcase</a></li>
    </ul>
    <p>
      <!-- TODO: Add github visibility -->
      <a href="https://github.com/divtag-ll" title="GitHub" class="social-icon inverted" data-v-2dac9808>
        <i class="fa fa-github" data-v-2dac9808></i>
        <span class="sr-only" data-v-2dac9808>GitHub</span>
      </a>
      &nbsp;
      <!-- TODO: Add medium visibility for DivTAG members to add blog posts/ tutorials -->
      <a href="#" title="Medium" class="social-icon inverted" data-v-2dac9808>
        <i class="fa fa-medium" data-v-2dac9808></i>
        <span class="sr-only" data-v-2dac9808>Medium</span>
      </a>
    </p>
    <p class="copyright">
      Released under the <a href="https://opensource.org/licenses/MIT" target="_blank" rel="noopener">MIT License</a>
      <br>
      Copyright © 2020 DivTag
    </p>
  </footer>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>
.main-footer {
  background: #475050;
  text-align: center;
  color: #fff;
  padding: 40px 0;
  font-size: .9rem;
}
</style>