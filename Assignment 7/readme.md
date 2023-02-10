
## ** Assignment 7 **

## Task 
## <u>Removing the languages that have 2.0 in their name</u>

## Task 1 code

```
let removeLang = document.querySelectorAll(".main__languages a");

for (let i = 0; i < removeLang.length; i++) {
  if (removeLang[i].innerText.includes("2.0")) {
    removeLang[i].style.display = "none";
  }
}

// Enable button and Input field

let inputField = document.querySelector(".main__form-input");
inputField.disabled = false;

let submitBtn = document.querySelector(".main__form-btn");
submitBtn.disabled = false;

```
## Task 02
## <u>Adding a eventlistener in submit button</u>
```
submitBtn.addEventListener("click", click);
function click() {
  for (let i = 0; i < removeLang.length; i++) {
    removeLang[i].style.display = "inline-block";
  }
}

```
## Output
![Output](Screenshot%202023-02-10%20181716.png)
