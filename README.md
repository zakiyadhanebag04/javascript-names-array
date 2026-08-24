# JavaScript Names Array

## About the Project

This is a simple JavaScript project that demonstrates different array methods using an array of names.

The program starts with the following names:

John, Jane, Doe, Alice, Bob

It performs different operations on the array and displays the results in the browser console.

## What the Program Does

1. Creates an array named `names` with five names.
2. Prints all names to the console, one name on each line.
3. Adds `Eve` to the end of the array using `push()`.
4. Removes `Doe` from the array using `splice()`.
5. Sorts the names in alphabetical order using `sort()`.
6. Checks whether `Alice` exists using `includes()`.
7. Creates a new array named `uppercaseNames` using `map()`.
8. Converts all names to uppercase using `toUpperCase()`.
9. Prints the `uppercaseNames` array to the console.

## Array Methods Used

- `forEach()` - Prints each name separately.
- `push()` - Adds Eve to the end of the array.
- `indexOf()` - Finds the position of Doe.
- `splice()` - Removes Doe from the array.
- `sort()` - Sorts the names alphabetically.
- `includes()` - Checks whether Alice exists.
- `map()` - Creates a new array from the names.
- `toUpperCase()` - Converts each name to uppercase.

## Example Output

```text
John
Jane
Doe
Alice
Bob

Sorted names: Alice, Bob, Eve, Jane, John

Alice is present

Uppercase names: ALICE, BOB, EVE, JANE, JOHN
