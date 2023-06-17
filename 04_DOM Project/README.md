# DOM-Assignment-Cards

## Expected Output

![Output expected](./Output/DOM%20P1%20SS.png)

## 1st task

```javascript
window.onload = function () {
	// Card titles
	const barbarian = document.querySelector(
		".clash-card__unit-stats--barbarian"
	);

	const archer = document.querySelector(".clash-card__unit-stats--archer");

	// Card stat & footer colors colors
	barbarian.style.backgroundColor = "#ec9b3b";
	barbarian.style.color = "#ffffff";

	archer.style.backgroundColor = "#ee5487";
	archer.style.color = "#ffffff";

	const giant = document.querySelector(".clash-card__unit-stats--giant");
	giant.style.backgroundColor = "#f6901a";
	giant.style.color = "#ffffff";

	const goblin = document.querySelector(".clash-card__unit-stats--goblin");
	goblin.style.backgroundColor = "#82bb30";
	goblin.style.color = "#ffffff";

	const wizard = document.querySelector(".clash-card__unit-stats--wizard");
	wizard.style.backgroundColor = "#4facff";
	wizard.style.color = "#ffffff";

	const archText = document.querySelector(".archer").children;
	archText[2].innerHTML = "The Archer";

	const goblinText = document.querySelector(".goblin").children;
	goblinText[2].innerHTML = "The Goblin";

	const statsColor = document.querySelector(".one-third");
	statsColor.style.color = "#ffffff";

	const lastThird = document.querySelectorAll(".one-third.no-border");
	lastThird.style.color = "#ffffff";
};
```
