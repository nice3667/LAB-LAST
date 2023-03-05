<template lang="">
   <div class="topnav">
      <div classname="barlow">
    <h1 style="text-align: center">หนังสือทั้งหมด</h1>
  <a href="#home">หน้าหลัก</a>
  <a href="#news">นิยม</a>
  <a href="#contact">มาใหม่</a>
  <a href="#contact">แนะนำ</a>
      </div>
  </div>
</template>
<script>
export default {}
</script>
<style scoped>
.topnav {
  overflow: hidden;
  background-color: #f4f4f4;
}

.topnav a {
  float: right;
  display: block;
  color: black;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
  border-bottom: 3px solid transparent;
}

.topnav a:hover {
  border-bottom: 3px solid #32CD32;
}

.topnav a.active {
  border-bottom: 3px solid #32CD32;
}
</style>