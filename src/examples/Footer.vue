<script setup>
</script>
<template>
  <footer class="py-3 footer">
    <div class="container-fluid">
      <div class="row align-items-center justify-content-lg-between">
        <div class="mb-4 col-lg-6 mb-lg-0">
          <div
            class="text-sm text-center copyright text-muted"
            :class="'text-lg-start'"
          >
            ©
            {{ new Date().getFullYear() }}, made with
            <i class="fa fa-heart"></i> by
            <a
              href="https://thevine.netlify.app/"
              class="font-weight-bold"
              target="_blank"
              >Divine Ikechukwu</a
            >
            for a better web.
          </div>
        </div>
      
      </div>
    </div>
  </footer>
</template>
