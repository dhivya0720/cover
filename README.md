# Ex.05 Book Cover Page Design
## Date:16/12/2025

## AIM:
To design a book back cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
cover.html
```
<html>
    <head>
        <title>Book Cover Page</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
    <div class="container">
        <div class="About">
            <h1>About the Book</h1>
            <div class="hrstyle">
                <hr style="color: darkcyan;">
        </div>
         <p>The Art of Computer Programming is a highly influential multi-volume series written by Donald E. Knuth, often considered the “Bible” of computer science. It provides a deep exploration of algorithms, covering fundamental concepts, data structures, sorting, searching, number theory, combinatorics, and more. The books are known for their rigorous mathematical approach, detailed proofs, and challenging exercises. Although the content is advanced and not ideal for beginners, it serves as an essential reference for serious programmers, researchers, and students who want to understand how algorithms truly work. The series has shaped modern computing, and Knuth continues to update it, making it a timeless masterpiece in the field of computer science.</p>
        </div>
        
        <div class="quote">
            <h3>“Computer programming is an art, because it applies accumulated knowledge to the world, because it requires skill and ingenuity, and especially because it produces objects of beauty.”</h3>
        </div>
        <div class="author">
            <img src="author img.jpeg" alt="Author Image">
           <div> DHIVYA DARSHNEE.U</div> 
           <div>
            DHIVYA DARSHNEE.U is a first year student who has a keen interest in exploring new concepts and technologies in field of computer science.Currently studying computer programming languages and developing technical skills and developing problem-solving skills.
        </div>
        </div>
        
        
        <div class="publisher">
            <div class="prints">
                <div>SEC Publishers</div>
                <div>printed in India</div>
            </div>
            <div class="price">
                <div>Price: Rs.399</div>
            </div>
        </div>
    </div>

    
    </body>
</html>
```
style.css
```
body
{
    background:url('image 1.png')no-repeat center/contain;
    flex-wrap: wrap;
    padding: 20px;
}
.container
{
    display:flex;
    width:50%;
    height: auto;
    background-color:cadetblue;
    margin: auto;
    padding: 10px 20px;
    border-radius:10px;
    border: 4px solid rgb(0, 32, 128);
    flex-wrap: wrap;
    
}
.About
{
 font-size: medium;
 color:rgb(80, 20, 220);
 margin-bottom: 10px;
 font-weight: bold;
 padding: 5px;
 }
.quote
{
    background-color:burlywood;
    padding: 20px;
    margin: 20px 0;
    border-left:5px solid navy;
    font-style:italic;
    font-weight: bold;
    color: brown;
    
}
.Author
{
    display: flex;
    align-items:center;
    gap: 15px;
    background-color: aqua;
    border-radius: 10px;
    margin-top: 25px;
    font-weight: bold;
    font-style: italic;
    color:darkred;
    
    
}
.Author img
{
    width: 100px;
    height:100px;
    border-radius: 5px;
    margin-right: 10px;
    border: 3px solid darkgoldenrod;
    object-fit:cover;
    color: crimson;
    
    
}

.publisher
{
    display: flex;
    margin-top: 20px;
    padding: 10px;
    background-color: chocolate;
    color:antiquewhite;
    border-radius: 5px;
    align-items: center;
    font-weight: bold;
    border:outset 2px  chartreuse;
    border-radius: 5px;
    margin-left: 20px;
    justify-content: space-between;
    width: 100%;
    
    
}

.price
{
    
    position:fixed;
    right: 400px;
    bottom:65px;
}
```

## OUTPUT:
![alt text](<Screenshot (36).png>)


## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
