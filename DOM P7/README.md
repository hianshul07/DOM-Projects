# Solutions for DOM

## 1st assignment

```JavaScript

let vardiv = document.querySelector(".main__languages");
let vara = vardiv.querySelectorAll("a");

		for (const i of vara) {
			if (i.innerText.includes("2.0")) {
				vardiv.removeChild(i);
			}
		}

```

## 2nd assignment

```JavaScript

let input = document.querySelector(".main__form-input");
	input.value = "Refreshing Page";
	let form = document.querySelector("form");
	setTimeout(() => {
		form.submit();
	}, 2000);

```
