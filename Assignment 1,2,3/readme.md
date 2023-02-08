# DOM Assignments

## Task  1
## <u> Append a new element in navigation menu "Hire me".</u>

### Task 1 Code
```
//Task 1
//Targeting Ul element 
 let targetUl=document.querySelector("ul");

 //selecting last element and change text to "Projects"
let lastElement=targetUl.lastElementChild;
lastElement.innerHTML=`<a href="./contact/contact.html">Projects</a>`

//Creating new li element.
let addElement=document.createElement("li");
addElement.innerHTML=`<a href="#">Hire Me</a>`;
//Appending to document
targetUl.appendChild(addElement);

```
## Output

![Output Image](./Output%20image/Screenshot%202023-02-03%20120523.png)

## Task 2
## <u>Change the input of searching Placeholder from "Search" to  "Search My Product" </u>


### Task 2 code
```
//Select input Element
let inputSelect=document.querySelector("input");
//Adding Id to input element
inputSelect.setAttribute("id","searchinput");
//By using id change the placeholder content.
document.getElementById("searchinput").placeholder = "Search My Project";

//Changing the list element from contact to Project

// //Select the li element 
//let ulelement=document.querySelector("ul");
// // Select the last child of li element
//let lastli=ulelement.lastElementChild;
// //Change  the text from Projects to contact
 //lastli.innerHTML=`<a href="./contact/contact.html">Projects</a>`;


```

## Output
![Output image](./Output%20image/Screenshot%202023-02-03%20120026.png)

## Task 3
## <u>Change the last element of li from "Project" to "Contact" </u>

### Task 3 code :-

``` 
//Select the li element
let ulelement=document.querySelector("ul");
// Select the last child of li element
let lastli=ulelement.lastElementChild;
//Change  the text from Projects to contact
lastli.innerHTML=`<a href="./contact/contact.html">Contact</a>`;
```
 ## Output
![Output image](./Output%20image/Screenshot%202023-02-03%20115142.png))


## Task 4 :-
## <u>Add an image in place of Avatar
</u>

### Task 4 Code :-

```
let imageSelect=document.querySelector("img");
imageSelect.src="DSC_8693.JPG";

```
## Output
![Output Image](./Output%20image/Screenshot%202023-02-03%20111218.png)

## Task 5 :-
 ## <u>Adding Button "Support Me"</u> 

### Task 5 code :-
```
//Selecting the parent class of buttons
let btnclas=document.querySelector(".hero-right-section-btns");
//Adding "Id" to the parent div
btnclas.setAttribute("id","hero-btn")

// Creating another button
let addbtn=document.createElement("button");
//Adding Text
addbtn.innerHTML="Support Me";
console.log(addbtn);

//Append both variable
btnclas.appendChild(addbtn);

```
## Output
![Output](./Output%20image/Screenshot%202023-02-03%20113208.png)


## ** Assignment 1 Completed **
