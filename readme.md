for (var i = 0; i < 100; i++) {

  var number = i + 1;
  var result = "";

  if (number % 3 == 0) {
    result = "Fizz";
  }
  else if (number % 5 == 0) {
  	result += "Buzz";
  }
  else {
  	result = i + 1;
  }
  console.log(result);

}
