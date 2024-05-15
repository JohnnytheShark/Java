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

## Array of Objects
This is possible but not considered good practice:
Object[] objectArray = new Object[3];
objectArray[0] = "Hello";
objectArray[1] = new StringBuilder("World");

## Java Arrays type functions
Arrays.sort(arrayName); // Natural Sort 
Arrays.toString(arrayName); // Turns array into string to be printed out
int[] copyArray = Arrays.copyOf(arrayName,arrayName.length) // To make a copy of an array
When you are making copies of an array and you choose a length that is larget than the original array, the default values for all new values is set to 0.

## Finding a match
### Binary Search
If you are going to use a binary search remember that the array must be ** Sorted **. Second, if there are duplicate values in the array, there's no guarantee which one it'll match on.
Finally Elements must be comparable.
It returns the index or 0 if no match is found.
Arrays.binarySearch(arrayName, key)

Checking if arrays are equal 
Arrays.equals(arrayName1,arrayName2); // Arrays have to be the same length and order.



