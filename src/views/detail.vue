<template>
  <div class="chart-page">
      <div class="header-wrap">
        <h1>Crypto App</h1>
        <p>ログアウト</p>
      </div>
      <div class="title">
        <h2>・銘柄一覧</h2>
        <h2>【現物取引】</h2>
        <card-a />
        <h2>【レバレッジ取引】</h2>
        <card-b />
      </div>
  </div>
</template>

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