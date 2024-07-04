void main() {
  //check weather the number is in the range of 20 and 30

  int number = 23;
  if (number > 20 && number < 30) {
    print("$number is in the range");
  } else {
    print("$number is not in the rang");
  }

  //ternary operator

  String result = number > 20 && number < 30
      ? "$number is in the range"
      : "$number is not in the range";
  print(result);
}
