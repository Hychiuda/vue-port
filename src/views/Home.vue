<template>
<body>
  <div class="primbox">
    <div id="overline">
      <img src="@/assets/headline.png" width="40%" height="">
    </div>

    <div id="underline">a multimediadesign student.</div>

    <img src='@/assets/landscape2.png' alt="background wallpaper" width="100%" height="auto">

    <div id="hi">
      <img alt="overline" src="@/assets/hi.png" width="10%" height="10%">
    </div>

    <div class="secbox">                                             
      <div id="aboutme">I'm a multimediadesigner based in Esbjerg, Denmark. I love being creative, hence my choice of education.
        I am currently learning editing, graphical design and coding. I love art so next I wanna learn music production, animation and 3d modelling.
      </div> 
       
    </div>
    <div class="cv">
      <img alt="overline" src="@/assets/business.png" width="25%" height="25%">
      <img alt="overline" src="@/assets/business2.png" width="25%" height="25%">
  </div>
    <div class="cv">
      <img alt="overline" src="@/assets/cv.png" width="40%" height="50%">
  </div>
    <div class="video">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/gbzXv6G9LCA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
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
    background-color: #d4dce8;
    width: 100%;
    height: 500px;   
}

.secbox{
    background-color: #fff;
    width: 100%;
    height: 400px;
    display: flex;
    justify-content: space-between;
    justify-content: center;
    flex-wrap: wrap;

    
}

#overline{
    color: #313131;
    text-align: center;
    font-size: 0px;
    padding: 0px 0 0;

}

#underline{
    color: #4d648d;
    font-family: "Nexa", Courier, monospace;
    text-align: center;
    font-size: 25px;

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
.video{
  margin-top: 50px;
  margin-bottom: 50px;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}
.cv{
  margin-top: 50px;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}
</style>