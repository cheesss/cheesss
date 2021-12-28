<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <<title>box</title>
  </head>
<style>
 h1,a {
   border-bottom: 1px gray solid;
   text-align: center;
   margin:0;

 }
 /*h2{
   border-top: 1px gray solid;
 }*/
 ol{
  border-right: 1px gray solid;
  width: 100px;
  padding: 20px;
  padding-left: 50px;
 }
 body{
   margin: 0;
 }
 #grid{
   display: grid;
   grid-template-columns: 150px 1fr;
 }
 #grid2{
   padding-left: 30px;
 }
 @media(max-width:800px){
   #grid{
     display: block;
   }
   ol{
    border-right: none;
   }
   #grid2{
     padding-left: 40;
   }

 }
 }
</style>
<body>

  <h1> 조현준 </h1>
<div id="grid">
  <ol>
    <li><a href="https://www.google.com/search?q=%EA%B0%95%EC%84%9C%EA%B5%AC+%EB%B0%A9%ED%99%94%EB%8F%99&oq=%EA%B0%95%EC%84%9C%EA%B5%AC+%EB%B0%A9%ED%99%94%EB%8F%99&aqs=chrome.0.0i355i512j46i512j0i512j0i30l7.5560j0j7&sourceid=chrome&ie=UTF-8"> 주소 </a></li>
    <li> 직업 </li>
  </ol>

<div id="grid2">
  <h2> 소개 </h2>
   안녕하세요 <a href="https://www.facebook.com/profile.php?id=100007007868129">조현준</a>입니다.
</div>
</div>

</body>

</html>
