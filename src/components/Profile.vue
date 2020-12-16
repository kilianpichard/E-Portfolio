<template>
  <v-container class="container">
      <div class="flexRow profile">
          <v-avatar size="250"><v-img src="@/assets/pp.jpg"></v-img> </v-avatar>
        <div class="test">
          <h1 class="thin">IT</h1><h1>STUDENT</h1>
          <h3>Caen, France.</h3>
        </div>
      </div>
  </v-container>
</template>

<script>
export default {
  name: "Profile",
};
</script>

<style scoped>
.avatar{
  padding:5px;
  border: 5px solid white;
  border-radius: 500px;
  margin-right: 40px;
  width: 270px;
  height: 270px;
}
.container{
  margin-top:50px;
  display: flex;
  align-items: center;
  justify-content: center;
}
*{
  color:white;
}
h1{
  margin-top:-20px;
}
h3{
  font-weight: normal;
}
.profile{
  border-radius: 20px;
  background: rgba(100,100,100,0.3);
  padding:20px;
  width: auto;
  width: 650px;
  display: flex;
  align-items: center;
  justify-content: center;
}
h2{
  border-bottom: 1px solid white;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 10px;
}
</style>
