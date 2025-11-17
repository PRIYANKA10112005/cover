# Ex.06 Book Front Cover Page Design
## NAME: PRIYANKA P
## REG NO: 212224230212

## AIM:
To design a book front cover page using HTML and CSS.

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
cover.html

<html>
    <head>
        <title>MyBook
        </title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>

        <div class="page">
            <div class="insights">
                SEC Insights
            </div>
            <div class="hr">
                <hr>
            </div>
            <div class="title">
                "CAREERS IN CYBER SECURITY"
            </div>
            <div class="subtitle">
               Guidance for building a successful career in cyber defense<br>
              Top Seller of 2025
            </div>
            <br>
            <div class="edit">
             SPECIAL EDITION
             </div>
             <br><hr>
              <div class="name">
                V.Jagan kumar
                </div>
                <div class="bottom">
                    SEC
                </div>
            <div class="pic">
            </div> 
        </div>
    </body>
</html>

styles.css

body
{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 110vh;
    
}
.page
{
    width:500px;
    height:700px;
    background-image:url('web background.png');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    border: 20px solid yellow;
    padding:20px;
    box-sizing:border-box;
    background-clip: padding-box;
    position: relative;
}

.insights
{
    font-size: 18px;
   font-weight: bold;
   margin-bottom: 10px;
}
.hr
{
    color: white;
    width: 120px;
    right: 200%;
    

}
.title
{
     color:#ffff;
    font-size: 45px;
     margin: 13px 0 15px 0;
    
   font-weight: bold;
    text-align: center;
}
.subtitle
{
    font-size: 17px;
    margin-bottom: 40px;
}
.edit
{
    position: relative;
    font-size: 19px;
    font-weight: bold;
    margin-top: 200px;
}
.name
{
    position: relative;
    font-size: 25px;
    font-weight: bold;
    margin-top: 5px;
    top:0%;
   
}
.bottom
{
    
    position: absolute;
    font-size: x-large;
    bottom: 20px;
    right: 60px;
    bottom:5%;
    font-weight: bold;
}
.pic
{
    position: absolute;
    bottom:90px;
    left: 75%;
    width: 100px;
    height:100px;
    background:url('my pic1.png.jpg')no-repeat;
    background-size: 80px;

}

```

## OUTPUT:
![alt text](book.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
