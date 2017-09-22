Boo who  
  
Check if a value is classified as a boolean primitive. Return true or false.  

Boolean primitives are true and false. 
 
booWho(true) should return true.    
booWho(false) should return true.    
booWho([1, 2, 3]) should return false.   
booWho({ "a": 1 }) should return false.   
booWho(1) should return false.   
booWho(NaN) should return false.   
booWho("a") should return false.  
i>booWho("true") should return false.    
booWho("false") should return false. 
 
  ===================================================    
  
function booWho(bool) {
  
 var type=typeof bool   
 if(type=="boolean")  
   return true; 
   else   
   return false;  
   ////===============2nd solution =================	  
   //return typeof bool ==='boolean';  
}  
   
booWho({ "a": 1 })   
