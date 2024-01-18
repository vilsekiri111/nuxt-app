<script setup lang="ts">
const { data: values } = await useFetch("http://localhost:3000/api/category");
const datas = values.value;
console.log(datas[0].image_link);
</script>

<template>
  <div class="bannerstart">
    <div v-for="item in datas">
      <div
        class="categorybanner"
        :style="{backgroundImage:`url(assets/images/category-1.jpg)`}"
      >
        <p>{{ item.beverage_name }}</p>
        <span>{{ item.number_of_items }} items</span>
      </div>
    </div>
  </div>
</template>

<style scoped>
.categorybanner {
  height: 200px;
  width: 200px;
}

.categorybanner:hover {
  width: 240px;
}

.category-content {
  text-align: center;
}

.bannerstart {
  display: flex;
  flex-direction: row;
  gap: 2rem;
  padding-left: 20px;
}
</style>
