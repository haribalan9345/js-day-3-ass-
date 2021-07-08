# js-day-3-ass-

//program for fizzbuzz
for(i=1;i<=100;i++){
  if(i/3==1){
    console.log("Fizz")
  }
  else if(i/5==1){
    console.log("Buzz")
  }
  else if(i/15==1){
    console.log("FizzBuzz")
  }
  else{
    console.log(i)
  }

}


//program for palindrome
s="civic,level,madam,racecar,rotor"
s1= ""
for(t of s){
  s1 = t+s1
}
console.log(s1)
