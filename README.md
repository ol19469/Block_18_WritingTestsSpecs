# Block_18_WritingTestsSpecs

Unit Tests:

1.A function called "multiplication" that returns the product of the two input numbers.
Expect multiplication(2,3) to be a number
Expect multiplication(2,3) to be equal to 6
Expect multiplication(a,3) to throw an error
Expect multiplication() to take two parameters and throw an error if there is one or none.

2.A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.
Expect concatOdds(arrA,arrB) to take in two arrays that are made of numbers.
Expect concatOdds(arrA,arrB) to make a new array with only the odd numbers of both arrays
Expect concatOdds(arrA,strA) to throw an error
Expect concatOdds(arrA,num) to throw an error
Expect concatOdds(arrA,boolean) to throw an error
Expect concatOdds(arrA,arrB) throw an error if neither arrays have odd numbers.
Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to take only one instance of each odd number into the new array.

Functional Tests:

1.A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.

When a User attempts to checkout with an empty cart they should get a pop up saying their cart is empty.
When a User attempts to sign in they should get an error message if their credentials are wrong.
When a User attempts to checkout they should first be shown their cart with the prices of everything in their cart.
When a User attempts to proceed to checkout they should then be prompted with a login page where they could also choose to continue as guest
When a User attempts to proceed as guest they should then be prompted for an email and phone number.
When a User attempts to proceed without filling out their email or phone number give them an error
