<script lang="ts" setup></script>

<template>
  <Html :lang="dynamic > 50 ? 'en-us' : 'en-gb'">

  <Head>
    <Title>RestaurantY</Title>
    <Meta name="description" content="Restaurant is amazing" />
  </Head>

  </Html>
  <div class="max-w-screen-xl flex flex-col items-center mx-auto mt-20">
    <h1 class="text-2xl font-bold">Welcome to RestaurantY</h1>
    <a href="/restaurants">Go to Restaurants</a>
  </div>
</template>

<style scoped></style>
