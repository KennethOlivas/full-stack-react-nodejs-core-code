# weak 2
---

## isPalindrome

````javascript
    const isPalindrome = (input) => {
        if (typeof input === 'number') {
            input = input.toString();
        }
        const reversed = input.split('').reverse().join('');
        return input === reversed;
    }
````

## Multiple of index

````javascript
    function multipleOfIndex(array) {
        return array.filter((element, index) => element % index === 0);
    }
````

## 

````javascript

````