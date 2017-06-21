# void-functions

Void functions are functions with no return value. They can also contain arguments. Functions need to be capatilized at the start of the name, otherwise it will be declared a variable.
For example,
void Function(){
  print(x);
}

void Function(){
  print(y);
}

void Function(){
  print("Pizza is good.");
}

void Function(){
  print("These are not the droids you are looking for.");
}
//a void function can be as simple as the above example, when called upon it prints the statement or variable

void Function(int x, int y){
  if(x == 1 && y == 1){
    print(x + y);
  }
  else{
    print(x);
  }
}

void Function(int x, int y){
  if(x >= 1 || y >= 1){
    print(x + y);
  }
  else{
    print("Both are less than one.");
  }
}
//arguments passed in the above example are of type int and prints the sum of x and y

public int Function(int x, int y){
  if(x == 1 || y == 1){
    return sum;
  }
  else{
    return x;
  }
}

public double Function(int x, int y){
  if(x == 1 || y == 1){
    return sum;
  }
  else{
    return x;
  }
}
//the above example is not a void function, it is a function with a datatype of int and double

