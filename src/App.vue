<template>
  <div class="home-page">
    <div class="color-overlay"></div>
    <div class="content">
      
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage'
}
</script>

<style>
.home-page {
  position: relative; 
  width: 100vw;
  height: 100vh;
  min-width: 1920px;
  min-height: 1080px;
  overflow: hidden;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-image: url('@/assets/Property 1=obl.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

.color-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: #F2E5CC; 
  opacity: 0.6;
  z-index: 1; 
}

.content {
  position: relative; 
  z-index: 2; 
}

.cta-button {
  margin-top: 30px;
  padding: 15px 40px;
  font-size: 18px;
  background: #6200ee;
  color: white;
  border: none;
  border-radius: 50px;
  cursor: pointer;
  transition: all 0.3s ease;
}

.cta-button:hover {
  background: #3700b3;
  transform: translateY(-3px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.2);
}
</style>