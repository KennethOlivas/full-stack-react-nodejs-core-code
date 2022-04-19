# weak 1
---

## Ensure questio

````javascript
    function ensureQuestion(s) {
        if (s.endsWith("?")) {
            return s;
        } else {
            return s + "?";
        }
    }
````

## Reversed Words

````javascript
    function reverseWords(str) {
        return str.split(' ').reverse().join(' ');
    }
````

## Find the smallest integer in the array

````javascript
    class SmallestIntegerFinder {
        findSmallestInt(args) {
            return Math.min(...args);
        }
    }
````
## Odd or Even?

````javascript
function oddOrEven(array) {
    return array.reduce((a, b) => a + b, 0) % 2 === 0 ? 'even' : 'odd';
}
````