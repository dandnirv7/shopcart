<script setup>
import { initFlowbite } from "flowbite";
onMounted(() => {
  initFlowbite();
});
</script>
<template>
  <div>
    <Head>
      <Title>Shopcart | Shop with Ease</Title>
    </Head>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
