<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">
      <img class="logo" alt="logo" src="./assets/logo.png">
      </router-link>
      <ul>
        <li><router-link to="/" class="active">About</router-link></li>
        <li><router-link to="work">Work</router-link></li>
      </ul> 
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#nav{
    background-color: #d4dce8;
    top: 0;
    left: 0;
    width: 100%;
    height: 125px;
    padding: 0 100px;
    box-sizing: border-box;
    transition: .5s;
     
}

#nav .logo {
    float: left;
    line-height: 0px;
    margin-top: 12px; 
    margin-left: 0px;
    transition: .5s;
    height: 75%;
    width: auto;
    
     
}

#nav .logo img{
  transition: .5s;
    
}

#nav ul{
    float: right;
    padding: 0;
    display: flex;
    
}

#nav ul li{
    list-style: none;
}

#nav ul li a{
    line-height: 80px;
    color: #4d648e;
    padding: 5px 20px;
    text-decoration: none;
    transition: .5s;
    font-family: "Nexa", Courier, monospace;
    font-size: 20px;
}

#nav ul li a:hover{
    color: #1e1f26;
}
</style>
