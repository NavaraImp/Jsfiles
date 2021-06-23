
 var a=0;var max=2; 


 function light(sw) {
  var bkl=".......................................";
  var pic= [
    
       "https://1.bp.blogspot.com/-fEcaqayHiH0/YI_gHOzKjcI/AAAAAAAAARg/yvVdfIWP4T4uJ03U1p-vHjsGCYRzAa8AACLcBGAsYHQ/s16000/2.png"
     , "https://1.bp.blogspot.com/-wrvx2JEI-LY/YI_ZMxryVwI/AAAAAAAAARM/KYLqcuHgW8sQefVvxCM2zSsf1CjKl7kGACLcBGAsYHQ/s1518/1.jpg"
    , "https://1.bp.blogspot.com/-Yv8JIaTCqr8/YJE9wDg-m5I/AAAAAAAAASw/RuhXI7Lq0iMaTa8T9IP-0ImfBZKU2xdsQCLcBGAsYHQ/s0/004.jpg"
  
  
  ] ;
 
   
   
   
   


   
   
   if(sw==1)
  {if(a<max)
  {a=a+1;}
   
  }
  if(sw==0)
  {if(a>0)
  {a=a-1;}
  
  }
  if(sw==2)
  { var x = document.getElementById("myNumber").value;
  if(x>=0&&x<=max)
  {a=x;}
  }
  bkl="         "+a+bkl;
 
   
   
   


 
   
   

   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   document.getElementById("demo").innerHTML = bkl;
  var fll="<br>"
  var rrr="Bottom line"
   document.getElementById("dem").innerHTML = rrr+fll;
  
  document.getElementById('myImage').src = pic[a];
   
 // document.getElementById('dem').style.backgroundImage = 'url('+pic[a]+')';
  // document.getElementById('dem').style.backgroundRepeat = 'no-repeat';
  //  document.getElementById('dem').style.backgroundAttachment = '';
  // document.getElementById('dem').style.backgroundSize = '100%';
   
   
   
   
   
   
  
   
   
   
   
   
}
 

  