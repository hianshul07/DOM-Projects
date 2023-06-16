# Solutions for DOM

![Output expected](./Output/DOM%20P3%20SS-1.png)
![Output expected](./Output/DOM%20P3%20SS-2.png)

## 1st task

```javascript
let image = document.querySelector("header .logo");
	image.src = "./assets/ineuron-logo.png";

let appPrice = document.querySelector(".app_price span");
	appPrice.innerText = "$10";

let footer = document.querySelector(".footer_social");
	footer.appendChild(socialIcon);

let socialIcon = document.createElement("div");
	socialIcon.className = "footer_social_ico";

let indent = document.createElement("i");
	indent.classList = "fa-brands fa-linkedin";
    
	socialIcon.appendChild(indent);
```