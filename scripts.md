# JavaScript Console Scripts:

## Text Change on Page:
Change the text content of an element on the page directly from the console.
```javascript
document.getElementById('someElement').innerText = 'New text';
```

## Page Structure Analysis:
Use selectors to analyze and output information about the page structure.
```javascript
console.log(document.querySelectorAll('a'));
```

## Element Style Modification:
Dynamically change the styles of elements.
```javascript
document.querySelector('h1').style.color = 'blue';
```

## Form Interaction Simulation:
Fill out a form or submit data using the console.
```javascript
document.getElementById('myForm').submit();
```

## Console Timer:
Use setInterval to create a timer in the console.

```javascript
let seconds = 0;
setInterval(() => console.log(seconds++), 1000);
```

Search and Replace:
Use replace to search and replace text on the page.
```javascript
document.body.innerHTML = document.body.innerHTML.replace(/oldText/g, 'newText');
```

## Performance Measurement:
Measure the execution time of specific code.

javascript
Copy code
console.time('myCode');
// Your code
console.timeEnd('myCode');
External Script Loading:
Connect and execute an external script directly in the console.

javascript
Copy code
const script = document.createElement('script');
script.src = 'https://example.com/myscript.js';
document.head.appendChild(script);
Browser Information Display:
Output information about the browser and its version.

javascript
Copy code
console.log(navigator.userAgent);
Element Animation:
Create an animation for an element on the page.

javascript
Copy code
const element = document.getElementById('animatedElement');
element.style.transition = 'transform 2s';
element.style.transform = 'translateX(100px)';
