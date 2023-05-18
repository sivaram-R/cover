# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Create django admin user interface
### Step 2:
Build html and css code
### Step 3:
Run the server to get the output
## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:rgb(212, 157, 7);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/html/back1.jpg);
            background-size: cover;
        }
            

        .insight{
            color: rgb(17, 255, 0);

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(222, 222, 222);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:orange;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(219, 172, 30);">
            </div>
            <div class="booktitle">
                <h1>Coolest Careers In CYBER SECURITY </h1></div>
            <div class="subtitle">
                1.THREAT HUNTER
            </div>
            <div class="subtitle">
                2.RED TEAMER
            </div>
            <div class="subtitle">
                3.DIGITAL FORENSIC ANALYST
            </div>
            <div class="subtitle">
                4.MALWARE ANALYST
            </div>
            <div class="subtitle">
                5.BLUE TERMER
            </div>
            <div class="mypic">
                <img src="/static/html/me2.jpg" width="120" height="155" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(182, 160, 164);">
            </div>
            <div class="author">
               <p><b>SIVARAM R</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>First Edition</b>
            </div>
        </div>
     </body>
</html>
```

## Output:
![2023-05-18](https://github.com/sivaram-R/cover/assets/121165794/defd4ef0-3949-4aef-9127-04e3976118ac)


## Result:
Book cover page is created.
