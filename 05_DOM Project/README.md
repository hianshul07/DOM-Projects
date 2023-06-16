# Solutions for DOM

## Expected Output

![Output expected](./Output/DOM%20P2%20SS.png)

## 1st task

```javascript
let subscription = document.createElement("a");
subscription.href = "#";
subscription.className = "btn";
subscription.innerText = "Pro Subscription";

let sibling = document.querySelector(".btn");
sibling.parentNode.appendChild(subscription);

let menu = document.createElement("a");
menu.href = "#";
menu.innerText = "Chinese (7)";

let heading = document.querySelector(".text-r");
heading.nextElementSibling.appendChild(menu);

let recipeGallery = document.querySelector(".recipe-gallery");
recipeGallery.appendChild(divCard);

let divCard = document.createElement("div");
divCard.className = "card";
divCard.appendChild(recipeLink);

let recipeLink = document.createElement("a");
recipeLink.href = "#";
recipeLink.className = "recipe-text";
recipeLink.appendChild(recipeImage);
recipeLink.appendChild(heading5);
recipeLink.appendChild(prep);
recipeLink = document.querySelectorAll(".recipe-text");

let recipeImage = document.createElement("img");
recipeImage.className = "recipe-img";
recipeImage.src = "./img/main.jpeg";

let heading5 = document.createElement("h5");
heading5.className = "recipe-name";
heading5.innerText = "Pancake";

let prep = document.createElement("p");
prep.className = "recipe-disp";
prep.innerText = "Prep : 10min | Cook : 5min";

for (const i of recipeLink) {
	i.style.color = "#58228F";
}
let span = document.querySelector(".footer-logo");
span.nextElementSibling.innerText = "Priti Manwatkar";
```
