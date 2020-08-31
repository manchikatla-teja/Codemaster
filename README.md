

var arr=[];

function prime(y){
  
  
  for(var x=2; x<y; x++){
    for (var i=2; i<x; i++){
      if(x%i===0 && arr.indexOf(x) === -1){
         arr.push(x);
         
      }
    }
    
   
}
}
prime(50);
console.log(arr)
