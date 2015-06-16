1. May 6

Define a JavaScript function add that can be used like so:

add(1)(1);   // returns 2
add(20)(20); // returns 40

2. May 7
Consider an array of sheep where some sheep may be missing from their place. Write a function that counts the number of sheep present in the array (true means present).

For example,

var sheep = [true,  true,  true,  false,
  true,  true,  true,  true ,
  true,  false, true,  false,
  true,  false, false, true ,
  true,  true,  true,  true ,
  false, false, true,  true];

countSheep(sheep);
The countSheep function, if defined properly, should return 17 in this case.


3. May 8
Create an array of 5 things you did this morning (strings). Write a for loop that returns everything preceded by "This morning I"
returns something like:

"This morning I woke up"
"This morning I got dressed"
"This morning I went back to bed"
"This morning ..."
"This morning ..."


4. May 11
With an array [1,2,3,4,5]. Write a while loop that adds 2 to odd numbers and squares even numbers.
returns:

    3
    4
    5
    16
    7


5. May 13
Given an array of test scores [ 68, 74, 99, 45, 83, 95 ] and the scale: F is less than 60, D is 60 to 69, C is 70 to 79, B is 80 to 89, A is 90 to 100.

Write a function that returns an array: convertToGrade(arr); // => [ D, C, A, F, B, A ]


6. May 14
Create a cup that is an object.
It starts out empty.
When you pour coffee into it, the cup becomes full
When you drink the coffee the cup becomes empty
What other properties can the cup have? Add some.
How can those properties be changed? Try it out.


7. May 18
Define a function called indexOf that takes in two arguments: an array, and an item that might be in the array. Your function should return the index of the item if it is found within the array; otherwise, it should return -1.

Example:

indexOf(['a', 'b', 'c'], 'a');
// => 0

indexOf(['a', 'b', 'c'], 'd');
// => -1


8. May 19
Use the forEach method to implement a function that returns the average number within an array.

Example:

getAverage([1,2,3]);
// => 2

9. May 20
Implement a function that takes two arguments. The first argument is an array of numbers. The second argument is a number two compare with each item in the array. Your function should return an array of numbers that are greater than the second argument.

Example:

findGreater([1,2,3,4,5,6,7,8], 5);
// => [6,7,8]

10. May 26
Write a function that takes two arrays and returns a new array with all items in alphabetical order.
    var array1 = [ "cat", "dog", "fish", "zebra" ],
        array2 = [ "lion", "aardvark", "gorilla" ]

    alphanimal(array1, array2);
    //-> [ "aardvark", "cat", "dog", "fish", "gorilla", "lion", "zebra" ]


10. May 27
Write a function that uses one or more loops and takes two arrays and returns an object that has the items in the first array as properties and the items in the second array as values.
    var array1 = [ "cat", "dog", "fish" ],
        array2 = [ "lion", "pointer", "trout" ]

    animalMatch(array1, array2);
    //-> animals = {
              cat: "lion",
              dog: "pointer",
              fish: "trout"
           }


11. May 28
Write a function that returns the longest string in the array and it's length as an object.
arry = ["truck", "sidewalk", "book"]

longString(arry)
//-> longString = { sidewalk: 8 }


12. May 29
Write a function that pulls the vowels out of a string and tells you the number of vowels. The function should return an array with the vowels used and the number of vowels as the last item in the array as “n vowels". If a vowel is used more than once in the array it will NOT appear in the array more than once.
var string = “I don’t know if this sentence has vowels in it.”

findVowels(string)
 //-> [ “i”, “o”, “e”, “a”, "4 vowels" ]


 13. June 2
 Implement each of these functions.

var dogs = ["Fido", "Harleigh", "Mali", "Trixie", "Snow", "Victory"];

howManyDogs(dogs);
// => 6

nameLengths(dogs)
// => [4, 8, 4, 6, 4, 7]

reverseDogNames(dogs);
// => ['odiF', 'hgielraH', 'ilaM', 'eixirT', 'wonS', 'yrotciV']

firstThreeDogsWithEach(dogs);
//=>  ["Fido", "Harleigh", "Mali"]


14. June 3
Implement each of these functions.

var people = [{name:'A', age: 20}, {name:'B', age: 30}, {}, {name:'', age: 10}];

removeBadPeople(people);
// => [{name:'A', age: 20}, {name:'B', age: 30}];

sumAgesValid(people);
// => 50

sumAgesAll(people);
// => 60


15. June 4
Write a function that takes an array and returns an object where each key is an item from the array and the corresponding value is how many times that item was in the array.

Example:

var list = ['a', 'b', 'c', 'a', 'b'];

sumInstances(list);
// => { a: 2, b: 2, c: 1 }

// **Make sure you write tests for the function!**

`jasmine init`


16. June 5
Write a function that reverses a string.

reverser('code')
//=> 'edoc'


17. June 6
Write a function that will capitalize not only the first word of the fish in the array, but the second as well.

var fish = [ "rainbow trout", "smallmouth bass", "white bass", "channel catfish" ]

capitalizeFish(fish)
//-> ["Rainbow Trout", "Smallmouth Bass", "White Bass", "Channel Catfish"]


18. June 10
Write a function that takes nested arrays and turns it into nested objects. If you solve it one way, then solve it another.

var books = [
  ["Learn to Program", "Chris Pine", 1934356360],
  ["Eloquent Javascript", "Marijn Haverbeke", 1593275846]
]

bookData(books)
//-> {
  "1934356360": {
    "title": "Learn to Program",
    "author": "Chris Pine",
    "isbn10": 1934356360
  },
  "1593275846": {
    "title": "Eloquent Javascript",
    "author": "Marijn Haverbeke",
    "isbn10": 1593275846
  }
}

19. June 11
Create a super 8 camera that shoots 18 frames a second. You'll need to load a 50 foot cartridge with 3,600 frames to film anything. Keep track of the frames you've shot, and when you need a new cartridge.


20. June 12
Take an array of arrays of dogs and make an object.
var dogs = [
  ["German Shepherd", "90 lbs.", "Work"],
  ["Pointer", "40 lbs.", "Hunting"],
  ["Corgi", "30 lbs.", "Awesomeness"]
];

consol.log(dogObject(dogs)
//-> { 'German Shepherd': { size: '90 lbs.', 'bred for': 'Work' },
  Pointer: { size: '40 lbs.', 'bred for': 'Hunting' },
  Corgi: { size: '30 lbs.', 'bred for': 'Awesomeness' } }


  
