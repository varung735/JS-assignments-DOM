## 1. [Dev To](https://dev.to/)
***

### Task

> Target the Top description div and change the DEV Community to <Your_Name> and description to your passion

### Original 

![Sample One](./Pic1.png)

### Solution

```
// For Heading
document.querySelector(".side-bar .crayons-card .crayons-subtitle-2").innerHTML = "VARUN GUPTA";

// For Content
document.querySelector(".side-bar .crayons-card .color-base-70").innerHTML = "Aspiring to be best web developer";
```

### Output

![Output](Solution-1.png)

## 2. [Apple](https://support.apple.com/en-in)
***
### Task

> Fetch all the product name and store in an array

### Sample-2

![Original](Pic3.png)

### Solution

```
const queryNodeList = document.querySelectorAll(".as-imagegrid-item-title");
let queryArray = [];

queryNodeList.forEach((item) => {
    let temp = item.firstChild.textContent;
    queryArray.push(temp);
})
```

### Output

![output](./solution-2.png)

## 3. [youTube Support](https://support.google.com/youtube/#topic=9257498)
***
### Task
> Add another FAQ 'My New FAQ' to the list

### Sample 3

![Original](./Pic4.png)

### Solution

```
let accordian = document.getElementsByClassName("accordion-homepage");
let section = document.createElement('section');
let h = document.createElement('h3');
h.innerText = 'My New FAQ';
section.classList.add('parent');
section.appendChild(h);
accordian[0].appendChild(section);
```

### Output

![output](./solution-3.png)

## 4. [OnePlus](https://www.oneplus.in/support)
***

### Task
> Change the contact number

### Sample 4

![Original](./Pic6.png)

### Solution

```
document.querySelector(".one-tel-number").innerText = 6265412345;
```

### Output

![Output](./solution-4.png)

## 5. [Samsung](https://www.samsung.com/in/offer/online/samsung-fest/)
***

### Task
>Target the main div of card and change the Button text to Check out

### Solution

```
document.querySelector(".diwali-deals-product-sale-btn").innerText = "Check Out";
```

### Output

![Output](./solution-5.png)

## 6. [Adidas](https://www.adidas.co.in/)
***

### Task
>Target the search box and on hover change thebackground color to red.

### Sample

![Original](./Pic10.png)

### Solution

```
let search = document.querySelector(".searchinput___19uW0");

search.addEventListener('mouseenter', () => {search.style.backgroundColor = 'red'});

search.addEventListener('mouseleave', () => {search.style.backgroundColor = 'white'});
```

### Output

![Output](./solution-6.png)

## 7. [MDN Web Docs](https://developer.mozilla.org/en-US/)

### Task
>To Search a topic in the MDN Search bar.
     First add a text to search in the search bar and then hit the submit search button to search the docs using DOM

### Sample

![original](./Pic12.png)

### Solution

### output

## 8. [Google](https://www.google.com/)

### Task
> Remove alternate languages from the home page languages listed

### Sample

![original](./Pic14.png)

### Solution

```
let div = document.getElementById('SIvCob');
let a = div.querySelectorAll('a');
for(let i = 0; i < a.length; i++){
    if(i%2 == 0){
        a[i].remove();
    }
}
```

### Output

![output](./solution-8.png)

## 9. [Code Wars](https://www.codewars.com/)

### Tasks
> Change the font family of the text to monospace and text color to the logo’s background color.

### Sample

![Original](./Pic16.png)

### Solution

### Output


## 10. [Freecodecamp](https://www.freecodecamp.org/)

### Tasks
> Target the button and change background colour on mouseover

### Sample
![Original](./Pic18.png)

### Solution

```
let getStarted = document.querySelectorAll(".login-btn-text");
getStarted[1].addEventListener("mouseleave", (event) => {
    event.target.style.backgroundColor = 'red';
});
```

### Output

![output](./solution-10.png)

## 11. [realme](https://www.realme.com/in/)

### Task
> change the realme logo to ineuron logo

### Sample 
![Sample One](./Pic20.png)

### Solution

```
let logo = document.querySelector(".icon-logo");
logo.style.backgroundImage = "url('https://ineuron.ai/images/ineuron-logo.png')";
```

### Output
![Output](./solution-11.png)

## 12. [Github](https://github.com/)

### Tasks
> change the background colour of the button to blue.

### Sample

![Sample](./Pic22.png)

### Solution

```
let btn = document.querySelectorAll(".btn-primary");
btn[1].style.backgroundColor = 'blue';
```

### Output

![Output](./solution-12.png)

## 13. [Hackerrank](https://www.hackerrank.com/)

### Tasks
> Target the top description and change “Matching developers with great companies” to ‘JSBOOTCAMP“.

### Sample
![Sample](./Pic24.png)

### Solution
```
let heading = document.querySelector(".fl-heading-text");
heading.innerHTML = "JSBOOTCAMP";
```

### Output
![Output](./solution-13.png)

## 14. [Asus](https://www.asus.com/in/)

### Tasks
> change the fontsize of “Hot Deals” to 80px

### Sample
![Sample](./Pic26.png)

### Solution

```
let heading = document.querySelector(".HotDealsAll__Heading__2fIbe");
heading.style.fontSize = '80px';
```

### Output
![Output](./solution-14.png)

## 15. [Dell](https://www.dell.com/en-in/shop/deals/laptop-deals?gacd=10415953-9016-5761040-285981356-0&dgc=ST&gclid=Cj0KCQjwguGYBhDRARIsAHgRm4-XUDMhhVNyHXb3s1gY4ZBzORr_d9Se-buhJwy7asyUe7YdqEA11eEaAt6UEALw_wcB&gclsrc=aw.ds&nclid=BxjBlpBQsX6pjSHh-L8YYSU77EpfXRkG1AGMB5Wbeu386ykspfrPDnfx_DdFau20)

### Tasks
> Convert the text “G15 Gaming Laptop” from left to right

### Sample
![Sample](./Pic28.png)

### Solution

```
let title = document.querySelectorAll(".ps-title");
title[1].style.textAlign = 'right';
```

### Output

![Output](./solution-15.png)

## 16. [Vercel](https://vercel.com/)

### Tasks
> change the heading “Start with the developer” to “Start with Scratch”

### Sample 
![Sample](./Pic30.png)

### Solution

```
let secHeading = document.querySelectorAll(".section-title_title__VEDfK");
secHeading[0].innerHTML = "Start with Scratch";
```

### Output

![Output](./solution-16.png)

## 17. [Sony](https://www.sony.co.in/)

### Tasks
> change the button text To current Date.

### Sample
![Sample](./Pic33.png)

### Solution

```
let btnContent = button[0].innerHTML;
let date = new Date();
button[0].innerHTML = date;
```

### Output
![Output](./solution-17.png)

## 18. [Philips](https://www.philips.co.in/)

### Tasks
> change the background colour blue to orange

### Sample
![Sample](./Pic34.png)

### Solution

```
let footer = document.querySelector(".p-f03-footer-container ");
footer.style.background = 'orange';
```

### Output
![Output](./solution-18.png)

## 19. [Canon](https://in.canon/)

### Tasks
> extract the canon logo

### Sample
![Sample](./Pic36.png)

### Solution

```
let logo = document.querySelector(".logo");
logo.getAttribute('src');
```

### Output
![Output](./solution-19.png)

## 20. [Oppo](https://www.oppo.com/in/)

### Tasks
> Change the description colour black to orange

### Sample
![Sample](./Pic38.png)

### Solution

```
let desc = document.querySelector(".desc");
desc.style.color = 'orange';
```

### Output
![Output](./solution-20.png)
