# Solutions for DOM

## Expected output

![Output](./ass7.1-after.png)
![Output](./ass7.2-after.png)

## 1st task

```JavaScript

let vardiv = document.querySelector(".main__languages");
let vara = vardiv.querySelectorAll("a");

		for (const i of vara) {
			if (i.innerText.includes("2.0")) {
				vardiv.removeChild(i);
			}
		}

```

## 2nd task

```JavaScript

let input = document.querySelector(".main__form-input");
	input.value = "Refreshing Page";
	let form = document.querySelector("form");
	setTimeout(() => {
		form.submit();
	}, 2000);

```
