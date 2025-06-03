<template>
  <header>
    <div class="logo">
      <img src="@/assets/Лого-80_3 1.png">
    </div>
    <div class="txt">
      <p><b>Музей Боевой и Трудовой Славы</b><br>город Александров</p>
    </div>
  </header>
  <main>
    <div class="main">
      <div class="hoho">
        <button class="search">
          <img src="@/assets/Component 3.png">
          <p>ПОИСК ГЕРОЯ</p>
        </button>
        <button class="filter">
          <img src="@/assets/Property 1=filter.png">
          <p>ФИЛЬТР</p>
        </button>
        <div class="hohp">
        <p>СТЕНА ПАМЯТИ</p>
        </div>
        <div class="hend">
          <img src="@/assets/рука.png" width="64px">
        </div>
        <div class="dota2">
        </div>
      </div>
    </div>
  </main>
  
</template>

<script>

</script>

<style>
body{
  width: 1920px;
  height: 1080px;
  background-image: url('@/assets/photo_2025-03-13_17-35-12.Problembo 1.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  overflow: hidden;
  margin: 80px 0px 80px 80px;
}
header{
display: flex;
flex-direction: row;
align-items: center;
}
header p{
  font-size: 3em;
}
.logo{
  margin-right: 44px;
}
.main{ 
 /* display: flex; 
  flex-direction: row;
  align-items: center;  */

}
.hoho{
  display: flex;
  flex-direction: row;
  align-items: center;
  width: 100%;
}
.search{
  cursor: pointer;
  border: 0 ;
  background-color: red;
  width: 280px;
  height: 69px;
  padding: 24px 32px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 1em;
  color:white;
  
}
.filter{
  border: 1px solid;
  cursor: pointer;
  padding: 24px 32px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 1em;
  background: none;
  width: 280px;
  height: 69px;
  margin: 0 16px;
}
.hohp{
  font-size: 3em;
  color: rgb(114, 114, 114);
}
.dota2{
border: 2px dotted #000; 
flex: 1;
size: 20px;

}
</style>