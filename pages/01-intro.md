---
layout: cover
class: text-center
transition: fade
---

<style>
.slidev-layout.cover {
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  position: relative;
}

.slidev-layout.cover::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-image: url('./assests/01.intro_bg.png');
  background-size: cover;
  background-position: center;
  filter: blur(1px);
  z-index: 0;
  transform: scale(1.1);
}

.slidev-layout.cover::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: rgba(0, 0, 0, 0.5);
  z-index: 0;
}

.slidev-layout.cover > * {
  position: relative;
  z-index: 1;
}
</style>

<div v-motion :initial="{ opacity: 0, y: 20 }" :enter="{ opacity: 1, y: 0, transition: { duration: 800 } }">

# ERT DMS

<div class="text-2xl mt-8 opacity-80">
  ERT Data Management System 기능 소개
</div>

</div>

