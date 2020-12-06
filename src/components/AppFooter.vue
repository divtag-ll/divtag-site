<template>
  <footer class="main-footer">
    <h2 class="text-base text-black font-semibold tracking-wide uppercase">DivTag Microservices/ API</h2>
    <ul>
      <li>
        <a href="#" class="font-medium text-green-600 hover:text-green-500"  target="_blank" rel="noopener">
          Events</a>
      </li>
      <li>
        <a href="#" class="font-medium text-green-600 hover:text-green-500"  target="_blank" rel="noopener">
          Members</a>
      </li>
      <li>
        <a href="#" class="font-medium text-green-600 hover:text-green-500"  target="_blank" rel="noopener">
          Blog</a>
      </li>
      <li>
        <a href="#" class="font-medium text-green-600 hover:text-green-500"  target="_blank" rel="noopener">
          Organization</a>
      </li>
      <li><a href="#" class="font-medium text-green-600 hover:text-green-500"  target="_blank" rel="noopener">
        Showcase</a>
      </li>
    </ul>
    <p>
      <!-- TODO: Add github visibility -->
      <a href="https://github.com/divtag-ll" title="GitHub">
        <i class="fa fa-github"></i>
        <span class="sr-only">GitHub</span>
      </a>
      &nbsp;
      <!-- TODO: Add medium visibility for DivTAG members to add blog posts/ tutorials -->
      <a href="#" title="Medium">
        <i class="fa fa-medium"></i>
        <span class="sr-only">Medium</span>
      </a>
    </p>
    <p class="copyright">
      Copyright © 2020 DivTag
    </p>
  </footer>
</template>

<script>
export default {
  name: "AppFooter"
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