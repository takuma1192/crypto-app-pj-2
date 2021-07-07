<template>
      <div class="detail">
        <div class="lists">
          <div class="item" v-for="(data,index) in items" :key="index">
            <div class="logo">
              <img src="{{data.img}}" alt />
              <p>{{data.item}}</p>
            </div>
            <a @click="router.push({ name: 'About' , param: {brand: brand } })">詳細</a>
          </div>  
        </div>
      </div>
</template>

<script>

</script>

<style scoped>
.logo {
  width: 100%;
  display: flex;
  background: #ffffff;
  margin: 10px;
  padding: 10px 200px 10px 20px;
}

.logo img {
  width: 100%;
  height: 100px;
}

.logo p {
  font-size: 40px;
  font-weight: bold;
  margin: 30px;
  padding-left: 45px;
}

.item {
  display: flex;
}

.item button {
  white-space: nowrap;
  font-size: 30px;
  margin: 10px 40px;
  padding: 0 50px;
  background: #ffffff;
  border: none;
  border-radius: 30px;
  
}
</style>