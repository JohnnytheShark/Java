# Array Notes from Master Class

## Declarations
Declaring an array we need to declare what type of array we are planning on having

int[] integerArray; 

Another way of instantiating one is using the new keyword: 
int[] integerArray = new int[10];

Assigning values to the array: 
integerArray[0] = 50;

## Array Rules
When arrays are instantiated you can not change the size of an array.
When declaring a type of array such as an int, you can not assign it a string value or double or any other kind as it breaks a rule. The compiler will show an error.

## Array initializer
int[] firstFivePositives = new int[]{1,2,3,4,5};

Another way
int[] firstFivePositives = {1,2,3,4,5};

## Indexing
firstFivePositives[firstFivePositives - 1] = last element of the array

## Backwards Array

int[] newArray;
newArray = new int[5]; //Declaring an array of length 5
for (int i = 0; i < newArray.length; i++){
    newArray[i] = newArray.length - i;
}

## For Loops 

Two different options available: 
Enhanced:
for (declaration : collection){
    // block of statements
}

Basic Loop:
for (init; expression; increment){
    //block of statements
}

Example: 
for (int element : newArray){
    System.out.print(element + " " );
}