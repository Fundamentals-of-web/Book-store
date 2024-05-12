# Project Responsive of web Design
# Book Store Managing System
## AIM
To develop a web development project based on book store managing system
## DESIGN STEPS
STEP 1: Clone the problem from GitHub
STEP 2: Create a new app for htmlstoring the books
STEP 4: Execute the project and create details for 10 books
## PROGRAM
## book.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bookskey</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
</head>
<body>
    <div class="navbar">
        <h1> Books</h1>
    </div>
     <div class="container">
        <div class="book-container">
            <h2>power of positivity</h2>
            <h5>Lowrence</h5>
            <P>Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo vel, veritatis dolorem veniam provident quas, eaque eius quos expedita eos voluptatem ullam. Dolorum, perspiciatis. Saepe delectus consequuntur fuga in sapiente!</P>
            <button onclick="deletebook(event)">Delete</button>
        </div>
<button class="add-button" id="add-popup-button">+</button>
          <script src="script.js"></script>
</body>
</html>
## Stule.css
*{
    margin: 0;
    padding: 0;
}
.book-container{
    padding: 15px;
    width: 25%;
    background-color: black;
    color: white;
    border-radius: 10px;
    margin: 30px;
    display: inline-block;
    vertical-align: top;
}
.book-container h2{
    color: blueviolet;
}
.book-container button{
    background-color: blueviolet;
    color: black;
    border-radius: 10px;
    padding-top: 5px;
    padding-bottom: 5px;
}
.popup-box textarea{
    background: transparent;
    border: none;
    width: 100%;
    margin: 5px;
    padding: 5px;
    font-size: 20px;
    border: solid black 2px;
}
~~~
~~~
.popup-box input::placeholder{
    color: black;
}
.popup-box textarea::placeholder{
    color: black;
}
## book.js
var popupoverlay = document.querySelector(".popup-overlay")
var popupbox = document.querySelector(".popup-box")
var addpopupbutton = document.getElementById("add-popup-button")
 addbook.addEventListener("click",function(event){
    event.preventDefault()
    var div=document.createElement("div")
    div.setAttribute("class","book-container")
    div.innerHTML = `<h2>${booktitleinput.value}</h2>
    <h5>${bookauthorinput.value}</h5>
    <P>${bookdescriptioninput.value}</P>
})
function deletebook(event)
{
    event.target.parentElement.remove()
}
~~~
## OUTPUT
![image](https://github.com/Fundamentals-of-web/Book-store/assets/141748873/ce4c0a2f-70f9-491a-b921-c8470f537b3c)
![image](https://github.com/Fundamentals-of-web/Book-store/assets/141748873/a119e5e1-496c-4040-812c-9fd9dcd34ed8)
## RESULT
Thus the program for creating a database using book store hass been executed successfully
