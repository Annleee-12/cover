# Ex.05 Book Cover Page Design
## Date:15.3.2026

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
```

<html>
    <head>
        
        <title></title>
        <style>
            .box
            {
                border:solid 3px darkblue;
                background-image: url(background.jpeg);
                background-size: cover;
                width:450px;
                height:700px;
                padding:25px;
                margin:500;
                border-style:double;
                border-radius:20px;
                
            }
            .header
            {
                padding-top:0px;
                margin-top: 10px;
                color:darkblue;
                text-align:left;
                font-weight:Bold;
                text-align:top;
            }
            .para
            {
                padding:5px;
                color:black;
                line-height:1;
                font-weight:bold;
                text-align: justify;
            }
            span
            {
                background:lightskyblue;
            }
            .quotes
            {
               background:rgb(230, 240, 250);
               border-left: 6px solid darkblue;
               padding: 10px;
               margin: 20px;
               color: darkblue;
               font-weight: bold;
            }
            .myself
            {
                
                 width:400x;
                height:140px;
                background-color:rgb(200, 220, 255);
                margin-left: 20px;
                padding-left:50px;
                margin-top: 35px;
                color:rgb(30, 30, 120);  
                padding:10px; 
                
            }
            .footer
            {
                border:dashed darkblue;
            
                width:400px;
                height:60px;
                display:flex;
                justify-content: space-between;
                align-items: center;
                background-color:lightsteelblue;
                margin-left:30px;
                margin-top:70px;
                color:darkblue;
                
                
                
                
            }
        </style>
    </head>
    <body bgcolor="lavender">
        <div class="box">
        <div class="header">
            <h1>About the book</h1>
            <hr size="3" color="darkblue">
        </div>
        <div class="para">
        
            <p><span>Artificial Intelligence (AI)</span> is a branch of computer science that focuses on creating intelligent machines capable of thinking, learning, and making decisions like humans. It includes areas like machine learning, natural language processing, computer vision, and robotics. AI powers everyday technologies such as virtual assistants, recommendation systems, and self-driving cars. The field is rapidly growing, offering exciting career opportunities in healthcare, finance, and automation.</p>
        
        </div>
        <div class="quotes">
            <I>
            "Artificial Intelligence is the new electricity." — Andrew Ng.
            </I>
        </div>
        <div class="myself">
            <img src="Author.jpeg" width="80" height="150" align="left">
            <h2>ANNLEE AGHAI DAVIDSON 25001177</h2>
            <p align="justify">Annlee is an Indian educator, author, and technology enthusiast. he is passionate about Artificial Intelligence and aims to inspire the next generation of AI innovators through his writing and research. </p>
            
        </div>
        <div class="footer">
            <b> SEC PUBLISHERS</b>
             <h3 align="right">PRICE:500rupees</h3>
        </div>
        </div>
    </body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (35).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
