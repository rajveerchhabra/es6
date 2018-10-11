# es6

/* using let */
function order(x,y) {
 if (x>y) {
    let tmp=x;
    x=y;
    y=tmp;
          }
 console.log(tmp===x); // let scope is onlly limited to a block, shows error while printing let outside the block 
 return [x,y];
                    
/* using var */
function func {
     if (true) {
       var tmp = 123;
     }
     console.log(tmp); //will print the value, as scope of var is through the whole funtion
   }
      
