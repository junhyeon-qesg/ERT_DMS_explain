---
layout: center
class: text-center
transition: fade
---

<div v-motion :initial="{ opacity: 0, y: 20 }" :enter="{ opacity: 1, y: 0, transition: { duration: 800, delay: 200 } }">

# 감사합니다

<div class="mt-12 text-3xl opacity-80">
  ERT DMS
</div>

<div class="mt-8 text-xl opacity-60">
  질문이 있으시면 언제든지 말씀해 주세요
</div>

<div class="mt-16">
  <mdi:hand-wave class="text-6xl opacity-50" />
</div>

</div>

<style>
.slidev-layout.center {
  background: linear-gradient(135deg, #006277 0%, #004d5c 100%);
  color: white;
}
</style>

