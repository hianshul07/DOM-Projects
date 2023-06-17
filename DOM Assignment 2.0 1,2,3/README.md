# Solutions for DOM

## 1st Task Solution

### ![Expected Output](./firstAssignmentImage/task1Output.png)

```javascript
let contact = document.querySelector("ul").children[2];
contact.innerText = "Projects";

let ul = document.querySelector("ul");
let projects = document.createElement("li");
projects.innerText = "Hire Me";
ul.appendChild(projects);

let footer = document.querySelector("footer");
footer.children[1].remove();

footer.style.justifyContent = "flex-start";
footer.style.marginLeft = "18rem";
```

## 2nd Task Solution

### ![Expected Output](./firstAssignmentImage/task2Output.png)

```javascript
let contact = document.querySelector("ul").children[2];
contact.innerText = "Projects";

let footer = document.querySelector("footer");
footer.children[1].remove();

footer.style.justifyContent = "flex-start";
footer.style.marginLeft = "18rem";
```

## 3rd Task Solution

### ![Expected Output](./firstAssignmentImage/task3Output.png)

```javascript
let contact = document.querySelector("ul").children[2];
contact.innerText = "Projects";
```

## 4th Task Solution

### ![Expected Output](./firstAssignmentImage/task4Output.png)

```javascript

let contact = document.querySelector("ul").children[2];
contact.innerText = "Projects";

let image = document.querySelector("img");
image.src = "./firstAssignmentImage/task4img.png";

```

## 5th Task Solution

### ![Expected Output](./firstAssignmentImage/task5Output.png)

```javascript
let contact = document.querySelector("ul").children[2];
contact.innerText = "Projects";

let parent = document.querySelector(".hero-right-section-btns");
let supportMe = document.createElement("button");
supportMe.innerHTML = "Support Me";
parent.appendChild(supportMe);
```
