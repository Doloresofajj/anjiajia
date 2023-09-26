<template>  
  <div id="app">  
    <img alt="Vue logo" src="./assets/1111.png" class="avatar">  
    <div class="info">    
      <h1 class="nickname">Hi,I'm Dolores</h1>    
      <h2 class="student-id">学号：2310273045，联系方式：AJJ8560538@gmail.com</h2>  
      <h3 class="want">生有热烈，藏于俗常</h3>  
    </div>  
  </div>  
</template>  
  
  
<style>  
#app {  
  font-family: Avenir, Helvetica, Arial, sans-serif;  
  -webkit-font-smoothing: antialiased;  
  -moz-osx-font-smoothing: grayscale;  
  text-align: center;  
  color: #2c3e50;  
  margin-top: 60px;  
}  
  
.avatar {  
  border-radius: 50%; /* 这行代码会将头像设为圆形 */  
}  
.student-id {
  font-size:medium;
  font-weight: lighter;
  color: darkslategray;
}
.want {
  font-size:medium;
  font-weight: lighter;
  color: darkslategray;
}
</style>