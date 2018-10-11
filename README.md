# es6

/* using let */
function order(x,y) {
 if (x>y) {
    let tmp=x;
    x=y;
    y=tmp;
          }
 console.log(tmp===x);  
 return [x,y];
                    
/* using var */
function func {
     if (true) {
       var tmp = 123;
     }
     console.log(tmp);
   }
      
