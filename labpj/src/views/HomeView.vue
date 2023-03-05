<template>
  <div>
    <div class-button>
      <button class="button">สมัครอ่านหนังสือ</button>
      <button class="button">สมัครขายหนังสือ</button>
      <button class="button">ใส่</button>
      <button class="button">หนังสือแนะนำ</button>
    </div>
  </div>
</template>
<script>
export default {
  
}
</script>
<style scoped>
  .button {
  display: inline-block;
  padding: 15px 25px;
  font-size: 15px;
  cursor: pointer;
  text-align: center;
  text-decoration: none;
  outline: none;
  color: #fff;
  background-color: #32CD32;
  border: none;
  border-radius: 5px;
  box-shadow: 0 9px #ffffff;
  margin: 5px 10px;
}

.button:hover {background-color: #32CD32}

.button:active {
  background-color: #32CD32;
  box-shadow: 0 1px #ffffff;
  transform: translateY(3px);
}
.button 
{font-size: 22px;}
</style>