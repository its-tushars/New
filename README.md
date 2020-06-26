<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>HTML</title>
   <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Baumans">
   <link rel="stylesheet"   href="https://fonts.googleapis.com/icon?family=Carme">
    <link href="https://fonts.googleapis.com/icon?family=Blinker" 
    rel="stylesheet">
   <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
  <link href="style.css" rel="stylesheet">
</head>

<body>
   <div id="loader">
     <div class="box">
     </div>
     <div class="silder"><i class="material-icons slider">group_work</i></div>
     <p>Just A Sec...</p>
   </div>
   <script>
     window.onload = function() {
       setTimeout(function() {
         document.getElementById("loader").remove();
         document.body.style.overflow = 'visible';
       }, 3000);
     };
     function openNav() {
     document.getElementById("mySidenav").style.width = "250px";
     }
     function closeNav() {
     document.getElementById("mySidenav").style.width = "0";
     }
   </script>
   <div id="mySidenav" class="sidenav">
     <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
     <a href="#">Home</a>
     <a href="#">Categories</a>
     <a href="#">Settings</a>
     <a href="#" style="border-top: 2px solid rgba(900,900,900,0.5);">Need help?</a>
     <span class="down">
       <span>Already a Customer?</span>
       <a href="#none" onclick="alert('The Login function isn\'t supported')">Log In</a>
       </span>
     
   </div>
  <div class="top">PACIFIC
  <i class="material-icons modal0">beach_access</i>
  <i class="material-icons modal" onclick="alert('The Cart function isn\'t available at this version')">shopping_cart</i>
  </div>
    <span style="font-size:30px;cursor:pointer" onclick="openNav()">  <i class="material-icons modal1">dashboard</i></span>

  
  
  <div class="search">

    <i class="material-icons modal2">search</i>
    <input id="search" type="search" 
     placeholder="Search among thousands of products :)">
  </div>
   <script>
     
   </script>
   <div class="list">
     <span>What are you looking for?</span>
     <ul class="main">
       <li>
         <ol>
           <li><i class="material-icons">whatshot</i></li>
           <li>Deals</li>
         </ol>
         </li>
         <li>
           <ol>
            <li><i class="material-icons">smartphone</i></li>
             <li>Mobile</li>
           </ol>
         </li>
         <li>
           <ol>
             <li><i class="material-icons">laptop</i></li>
             <li>Laptop</li>
           </ol>
         </li>
         <li>
           <ol>
            <li>
              <i class="material-icons">personal_video</i>
              </li>
             <li>T.Vs</li>
           </ol>
         </li>
         <li>
           <ol>
             <li><i class="material-icons">drive_eta</i></li>
             <li>Cabs</li>
           </ol>
         </li>
         <li>
           <ol>
        <li><i class="material-icons">free_breakfasts</i></li>
       <li>Grocery</li>
           </ol>
         </li>
         <li>
           <ol>
             <li><i class="material-icons">flight</i></li>
             <li>Travel</li>
           </ol>
         </li>
         </ul>
         <div class="ads">
           <img src="https://dl.dropbox.com/s/jj8k1q9oa749upw/images%209.jpeg?dl=0">
         </div>
    <div class="sign">
         <span>Sign In for the best experience</span>
         <button class="btn" onclick="alert('The Sign In function isn\'t available at this version')">Sign In</button>
    </div>  
   </div>
   <div class="parallax">
     <span class="first"> 
     Iphone 11 pro at 50% off!
     </span>
    <div class="image"></div>
    
     <div class="parallax2">
       <span class="second">
         Buy Now the new Iphone starting at just ₹70,000
       </span>
       <div class="secimage"></div>
     </div>
     
     <div class="products">Discover Laptops</div>
       <div class="products2">
  <div><img src="https://dl.dropbox.com/s/9c4a3llgups7ha6/image%207.jpeg?dl=0">
  <span>Lenovo</span></div>
 <div><img src="https://dl.dropbox.com/s/ihyt937pucxihiw/images%204.jpeg?dl=0">
 <span>Acer</span></div>
  <div><img src="https://dl.dropbox.com/s/32kk42ofthi5mtq/images%205.jpeg?dl=0">
  <span>Apple</span></div>
 <div><img src="https://dl.dropbox.com/s/2me2y7wegjyd9jq/images%203.jpeg?dl=0"><span>Dell</span></div>
       </div>
   
   <div class="swipe">
       Swipe Down
      <div>
        <i class="material-icons">keyboard_arrow_down</i>
        </div>
        
   <div class="last">
   <span>Made By</span>
   <span>VENAGE</span>
   <div><img src="https://dl.dropbox.com/s/wyapj6hfzy8qtai/IMG%201.jpg?dl=0"></div>
   </div>
   
  <footer>
 <span> All rights reverved 2020 🔥VENAGE🔥.</span>
 <span>THIS IS TO CERTIFY THAT THIS DOCUMENT BELONGS TO 'TUSHAR SHARMA' AND NO COPY OF THIS DOCUMENT SHOULD BE PUBLISHED IN ANY MEANS OR FORM ON ANY PLATFORM.</span>
 <span>Contact details</span>
 <span>
   <a href="https://github.com/its-tushars"><img src="https://dl.dropbox.com/s/yr59b9eolhy6u46/download.png?dl=0" style="width:40px;height:auto;padding:10px 20px 0 0"></a>
 <a href="https://www.sololearn.com/Profile/18358780/?ref=app"><img src="https://dl.dropbox.com/s/vo5zzkl3rgsao51/images%2010.jpeg?dl=0" style="width:40px;height:auto"></span></a>
 </footer>
   
 </body>
</html>
