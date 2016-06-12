# js-while

perf

var m=[0,1,2,3,4], l = m.length;
console.log('length/value:')
while(l!==0){
  console.log(l+'/'+m[--l])
}

"length/value:"
"5/4"
"4/3"
"3/2"
"2/1"
"1/0"
