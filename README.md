
# Lamp Website Project

This designed template demonstrates a solid understanding of HTML, CSS and JavaScript.




## Website HomePage

![VueLamp Website HomePage](https://github.com/zaidaslam99/Lamp_Home_Page_Project/blob/main/project_pictures/lamp_homepage.png?raw=true)


## Lessons Learned

```javascript
var btn = document.getElementById("btn")
var light = document.getElementById("light")

function toggleBtn(){
btn.classList.toggle("active")
light.classList.toggle("on")}
```
The classList JS is a read-only property that is used to return CSS classes in the form of an array. The classList JS allows us to add, remove, replace, toggle, or check whether the specific CSS class is present or not.

Notice that we are using getElementById to access the id that is btn. The reason we are doing this is that we want to get one particular element. Here the important concept to understand is that .btn class is referring to the button and .light class is referring to the image.

Once we have access to that element we then create a function called toggleBtn(){} and essentially what we are doing is calling toggle() and within toggle there is "active" & "on" This is referring to the CSS styling that is going to be taking place. So essentially what's going to happen is that the element that we have selected is going to be running the CSS class that we created to create this "illusion" of change. 
