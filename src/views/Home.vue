<template>
<body>
  <div class="primbox">
    <div id="overline">
      <img src="@/assets/headline.png" width="40%" height="">
    </div>

    <div id="underline">an mmd student.</div>

    <img src='@/assets/landscape.png' alt="background wallpaper" width="100%" height="623">

    <div id="hi">
      <img alt="overline" src="@/assets/hi.png" width="10%" height="10%">
    </div>

    <div class="secbox">                                             
      <div id="aboutme">I'm a multimediadesigner based in Esbjerg, Denmark. I love being creative, hence my choice of education.
        I am currently learning editing, graphical design and coding. I love art so next I wanna learn music production, animation and 3d modelling.
      </div>  
    </div>
  </div>                                     
</body>
</template>

<script>

</script>

<style lang="scss">
body{
margin: 0;

}

.primbox{
    background-color: #e0ebe8;
    width: 100%;
    height: 922px;   
}

.secbox{
    background-color: #fff;
    width: 100%;
    height: 1200px;
    display: flex;
    justify-content: space-between;
    justify-content: center;
    flex-wrap: wrap;

    
}

#overline{
    color: #313131;
    text-align: center;
    font-size: 50px;
    padding: 100px 0 0;

}

#underline{
    color: #45b29a;
    font-family: "Nexa", Courier, monospace;
    text-align: center;
    font-size: 30px;

}

#hi{ 
  text-align: center;
  margin-top: 125px;   
}

#aboutme{
    color: #545454;
    font-family: "Nexa", Courier, monospace;
    font-size: 20px;
    width: 30%;
    height: 100px;
    margin-top: 50px;
    line-height: 150%;
    text-align: center;
}
</style>