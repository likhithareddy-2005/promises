# promises
let mypromise=new Promise((resolve,reject)=>{
  x=true;
  if(x==true){
    resolve("success");
  }
  else{
    reject("operation failed");
  }
});
mypromise.then((value)=>{
  console.log(value);
}).catch((reason)=>{
  console.log(reason);
})
