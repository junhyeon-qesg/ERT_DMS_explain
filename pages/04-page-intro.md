---
layout: center
class: text-center
transition: fade
---

<div v-motion :initial="{ opacity: 0, scale: 0.9 }" :enter="{ opacity: 1, scale: 1, transition: { duration: 600 } }">

# 페이지별 기능 소개

<div class="mt-12 text-2xl opacity-80">
  ERT DMS의 주요 페이지와 기능
</div>

<div v-click class="mt-16 grid grid-cols-3 gap-8 max-w-4xl mx-auto">
  <div class="flex flex-col items-center">
    <mdi:folder-multiple-outline class="text-5xl mb-4" />
    <span class="text-lg">스페이스</span>
  </div>
  <div class="flex flex-col items-center">
    <mdi:ruler class="text-5xl mb-4" />
    <span class="text-lg">단위 관리</span>
  </div>
  <div class="flex flex-col items-center">
    <mdi:file-document-edit-outline class="text-5xl mb-4" />
    <span class="text-lg">지표 템플릿</span>
  </div>
  <div class="flex flex-col items-center">
    <mdi:table-edit class="text-5xl mb-4" />
    <span class="text-lg">데이터 시트</span>
  </div>
  <div class="flex flex-col items-center">
    <mdi:view-dashboard-outline class="text-5xl mb-4" />
    <span class="text-lg">대시보드</span>
  </div>
</div>

</div>

