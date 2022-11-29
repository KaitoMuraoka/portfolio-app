<script setup lang="ts">
const links = [{
  url:'/about',
  text: 'このサイトについて'
}, {
  url: '/profile',
  text: 'プロフィール'
}, {
  url: '/products',
  text: '作品集'
}
];
</script>
<template>
  <div class="p-8 grid gap-y-8">
    <PageContainer>
    <AppH2>トップページ</AppH2>
    <AppLink v-bind:links="links"/>
    </PageContainer>
  </div>
</template>
