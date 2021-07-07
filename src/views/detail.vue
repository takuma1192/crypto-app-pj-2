<template>
  <div class="chart-page">
    <Header />
      <div class="title">
        <h2>・銘柄一覧</h2>
        <h2>【現物取引】</h2>
        <CardA />
        <h2>【レバレッジ取引】</h2>
        <CardB />
      </div>
  </div>
</template>

<script>
import Header from "./components/Header";
import CardA from "./components/CardA";
import CardB from "./components/CardB";
export default {
  components: {
    Header,
    CardA,
    CardB
  }
};
</script>

<style scoped>
.chart-page {
  height: 100%;
  min-width: 800px;
  background: #E5E5E5;
}

.header-wrap {
  display: flex;
  justify-content: space-between;
}

.header-wrap h1 {
  font-size: 60px;
  font-weight: bold;
  text-decoration: underline;
  padding: 20px;
}

.header-wrap p {
  font-size: 20px;
  font-weight: bold;
  text-decoration: underline;
  padding: 40px;
}
  
.title h2{
  font-size: 40px;
  padding: 20px;
}

</style>