# Arthematic-operation
exports.add= function(x,y){
return x+y;
}

exports.sub= function(x,y){
return x-y;
}

exports.mul= function(x,y){
return x*y;
}

exports.div= function(x,y){
return x/y;
}



var sum = require('./add')
console.log(sum.add(3,6));	


var sub = require('./sub')
console.log(sub.sub(3,6));	

var mul = require('./mul')
console.log(mul.mul(3,6));	

var div = require('./div')
console.log(div.div(3,6));	
