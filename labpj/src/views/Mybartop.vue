<template>
    <div>
        <ul>
  <li><a class="active" href="#home">ล็อกอินเข้าสู่ระบบ / สมัครสมาชิก</a></li>
  <li style="float:right"><a class="active" href="#about">กะตร้า</a></li>
  <li style="float:right"><a class="active" href="#about">ใส่</a></li>
  <div class="search-container">
    <form action="/action_page.php">
      <input type="text" placeholder="ค้นหาหนังสือ" name="search">
      <button type="submit"><i class="fa fa-search"></i></button>
    </form>
  </div>
</ul>   
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
  ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #32CD32;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #8bfd98;
}
  
* {box-sizing: border-box;}

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.search-container {
  float: right;
}

input[type=text] {
  padding: 6px;
  margin-top: 8px;
  font-size: 17px;
  border: none;
}

.search-container button {
  float: right;
  padding: 16px 15px;
  margin-top: 8px;
  margin-right: 16px;
  background: #ddd;
  font-size: 17px;
  border: none;
  cursor: pointer;
}

.search-container button:hover {
  background: #ccc;
}

@media screen and (max-width: 600px) {
.search-container {
    float: none;
  }
input[type=text], .topnav .search-container button {
    float: none;
    display: block;
    text-align: left;
    width: 100%;
    margin: 0;
    padding: 14px;
  }
input[type=text] {
    border: 1px solid #ccc;  
  }
}
</style>