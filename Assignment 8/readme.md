## ** Assignment 8 **

## Task 
## <u>  Add a scroll bar in aside tag</u>

## Task 1 code
```
//Select aside element
let aside = document.querySelector("aside")
// Adding CSS property
aside.style.overflow = "auto";
// Create a dummy h2
let heading2 = document.createElement("h2");
heading2.setAttribute("class", "new-head");
heading2.innerHTML = "This is my custom heading?";
// Create a dummy para
let para = document.createElement("p");
para.setAttribute("class", "new-p");
para.innerHTML =
  "Private funding by VC firms is down 50% YOY. We take a look at what that means.";

  //appending in aside tag
aside.appendChild(heading2);
aside.appendChild(para);


```
## Output
![Output](./Output/Screenshot%202023-02-07%20215843.png)

## Task 

## Remove the slide bar

### Task code

```
aside.removeChild(heading2);
aside.removeChild(para);
aside.style.overflow="hidden";
```
## Output
![Output](./Output/Screenshot%202023-02-07%20220501.png)

##
### Toggle the Navbar element

## Task code

```
let button=document.querySelector(".navbar-toggler"); // Target button
let listbtn=document.querySelector(".list-btn"); //Select li element;

let div=document.querySelector(".col-lg-8")// main div
console.log(div);

//Create another div
let newdiv=document.createElement("div");
//Insert Element at the begininig in the main div
div.insertBefore(newdiv,div.childNodes[0]);
//newdiv append all li elements
newdiv.appendChild(listbtn);
newdiv.style.display='none'

// Button click event
button.addEventListener('click',function(){
    if(newdiv.style.display === 'none'){
        newdiv.style.display ='block';
    }
    else{
        newdiv.style.display ='none';

    }
})
```
![Output](./Output/Screenshot%202023-02-08%20122207.png)

## _Assignmnet 8 completed_
