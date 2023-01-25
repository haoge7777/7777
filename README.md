# 7777
<Script Language="JavaScript"> 

　　 var timedate= new Date("October 1,2002"); 

　　 var times= "国庆节"; 

　　 var now = new Date(); 

　　 var date = timedate.getTime() - now.getTime(); 

　　 var time = Math.floor(date / (1000 * 60 * 60 * 24)); 

　　 if (time >= 0) 

　　 document.write( "现在离"+times+"还有: "+time +"天")

</Script>
