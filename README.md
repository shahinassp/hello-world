# hello-world<html>
<head>

     <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>


 <script>
$(document).ready(function callMe(){

  alert ("hello world")
});
function showCountryName(obj){
  alert(obj.value);
}
       </script>
     </head>
     <body>
       <select id="country" onchange="showCountryName(this)">
       <option value="">Select One</option>
       <option value="USA">USA</option>
       <option value="Canada">Canada</option>

     <body onload ="callMe()">
       <button id="btn" onclick="callMe()" > click here </button>  </body>

     <input type="text" id="phone" name"phone"/>
     <input type="button" value="click" id="btn" />


</html>
