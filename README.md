# beatsbykeshav-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BeatsbyKeshav — Video Editor</title>

<style>
*{
  box-sizing:border-box;
  margin:0;
  padding:0;
}

body{
  background:#080909;
  color:#f5f5f5;
  font-family:Arial,Helvetica,sans-serif;
  line-height:1.5;
}

a{
  color:inherit;
  text-decoration:none;
}

.container{
  width:min(1100px,92%);
  margin:auto;
}

header{
  position:sticky;
  top:0;
  z-index:20;
  background:rgba(8,9,9,.92);
  backdrop-filter:blur(15px);
  border-bottom:1px solid #242424;
}

.nav{
  height:72px;
  display:flex;
  align-items:center;
  justify-content:space-between;
}

.logo{
  font-size:23px;
  font-weight:800;
}

.logo span{
  color:#ffd21c;
}

.nav-links{
  display:flex;
  gap:25px;
  color:#aaa;
  font-size:14px;
}

.nav-links a:hover{
  color:#ffd21c;
}

.hero{
  min-height:90vh;
  display:flex;
  align-items:center;
  padding:80px 0;
}

.hero small{
  color:#ffd21c;
  letter-spacing:5px;
  font-weight:bold;
}

.hero h1{
  font-size:clamp(48