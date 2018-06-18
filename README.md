<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
* {
  box-sizing: border-box;
}
.menu {
  float: left;
  width: 20%;
}
.menuitem {
  padding: 8px;
  margin-top: 7px;
  border-bottom: 1px solid #f1f1f1;
}
.main {
  float: left;
  width: 60%;
  padding: 0 20px;
  overflow: hidden;
}
.right {
  background-color: lightblue;
  float: left;
  width: 20%;
  padding: 10px 15px;
  margin-top: 7px;
}

@media only screen and (max-width:800px) {
  /* For tablets: */
  .main {
    width: 80%;
    padding: 0;
  }
  .right {
    width: 100%;
  }
}
@media only screen and (max-width:500px) {
  /* For mobile phones: */
  .menu, .main, .right {
    width: 100%;
  }
}
</style>
</head>
<body style="font-family:Verdana;">

<div style="background-color:#f1f1f1;padding:15px;">
  <h1>Divya Gupta</h1>
</div>

<div style="overflow:auto">
  <div class="menu">
    <div class="menuitem">Introduction</div>
    <div class="menuitem">Education</div>
    <div class="menuitem">Aim</div>
    <div class="menuitem">Contacts</div>
  </div>

  <div class="main">
    <h2>Introduction</h2>
    <p>Name-Divya Gupta</p>
    <p>Father's Name-Suresh Sah</p>
    <p>Mother's Name-Kumari Shyamlata</p>
    <img src="IMG_20180115_163951.jpg" style="width:100%">
  </div>

  <div class="right">
    <h2>Qweries</h2>
    <h2>Instagram</h2>
    <h2>My linkedin profile</h2>
    <p>Faceboom</p>
  </div>
</div>
<div style="background-color:#e5e5e5;text-align:center;padding:10px;margin-top:7px;">Contacts</div>
</body>
</html>

