# Checkpoint 01

> **Fork and clone this repo and follow the directions below.**

Please reference [this document](https://git.generalassemb.ly/jdr-0127/homework-submissions/blob/master/README.md) for more information on how to submit this checkpoint.

For the following exercise, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ). When you're done, submit this updated file as a pull request to this repo.

## Javascript Variables and Data Structures

### Question 1

Create a variable and store the string "pizza" in it...

```js
// Answer goes here...
let varFood = "Pizza";
```

---

>  **For questions 2-5, use the code below.**

```js
let names = ["Jonas", "Inigo Montoya", "Slim Shady", "Mr. Robot"];
let clown = {
  name: "Joker",
  evil: true,
  minions: ["Bozo", "Harley Quinn", "Grumpy", "Chuckles"],
  enemy: {
    name: "Batman",
    evil: false,
    minions: ["Robin", "Alfred"]  
  }
};
```

### Question 2

Access the value `"Jonas"` out of the `names` array...

```js
// Answer goes here...
console.log(names[0]);
```

### Question 3

Write a for loop that prints `hello NAME` to the console. `NAME` should be replaced with a name that appears in the `names` array. Each iteration of the loop should print a different name.

```js
// Answer goes here...
for (let i=0; i<names.length(); i++)
{
console.log(names[i]);
}
```

### Question 4

Access the value `"Alfred"` out of the `clown` object...

```js
// Answer goes here...

console.log(clown.enemy.minions[1]);

### Question 5

Set a new property on the object stored in the variable clown. Make it anything you want!

```js
// Answer goes here...
```
let var = clown.newName = "sachin";
console.log(var);


---

### Question 6
Write a function that takes an array as an argument and returns the array's first value...

```js
// Answer goes here...
function firstfunction(let array)
{
return array[0];
}

```
---

## Git & GitHub

### Question 7

What is Git, what problem does it solve? What is the difference between Git and Github?

```
# Answer goes here...
```
git is used for version control
hithub is cloud based system that holds git repositories

---

### Question 8

What is the difference between a fork and a clone?
fork is copying the code to repository
clone is copying the code to local repository s that we can update it 
```
# Answer goes here...
```

---

## HTML & CSS

### Question 9

How would you link a CSS file entitled `hardstyle.css` in an HTML file?

```html
<!-- Answer goes here... -->
<link="css file" rel="stylesheet" type="css">
```

---

> **For Questions 10 & 11 use the code example below...**

```html
<body>
  <div id="dog-resume">
    <ul class="skillz">
      <li> - Bone Location</li>
      <li> - Remote Sniffing</li>
      <li> - Delineating Territory</li>
      <li> - Shoe Deconstruction </li>
      <li> - Carpet Stain Placement </li>
    </ul>
  </div>
</body>
```

### Question 10

Write a CSS selector that will apply styling to an element with an id of `dog-resume`...


```css
/* Answer goes here... */
```
dog-resume dr {
width: auto;
float left;
}

### Question 11

Write a CSS selector-rule that will select and apply styling to every `<li>` inside of a `<ul>`:

```css
/* Answer goes here... */
```
ul.skillz li {
width: auto;
float left;
}
