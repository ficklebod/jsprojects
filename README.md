# jsprojects
learning what js can do



var fizzBuzzArray = [];

function fizzBuzz(i){
  for (i = 1; i < 100; i++){
    if (i%3 === 0 && i%5 === 0){
     fizzBuzzArray.push("fizz-buzz")
    }
    else if (i%3 === 0){
      fizzBuzzArray.push("fizz")
    }
    else if (i%5 === 0){
      fizzBuzzArray.push("buzz")
    }
    else{
      fizzBuzzArray.push(i)
    }
  }
}
fizzBuzzArray.push(fizzBuzz())
console.log(fizzBuzzArray)
