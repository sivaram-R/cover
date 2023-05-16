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
<html>
<head>
  <title>Magic Book Front Page</title>
  <style>
    body {
      background-image: url("back1.jpg"), url("doc strange.jpg");
      background-position: center, center;
      background-repeat: no-repeat, no-repeat;
      background-size: cover, cover;
    }
    
    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      color: white;
      text-align: center;
    }
    
    h1 {
      font-size: 48px;
      margin-bottom: 20px;
    }
    
    p {
      font-size: 24px;
    }
  </style>
</head>
<body>
  <div class="container">
    <img src="doc strange.jpg" alt="Book Cover" width="600" height="300">
    <h1>DEATH NOTE</h1>
    <h2>Author: patric bateman</h2>
    <h2>Publisher: pyscho Publications</h2>
    <p>Read if you wanna die ..!</p>
  </div>
</body>
</html>
```
## Output:
![2023-05-16 (1)](https://github.com/sivaram-R/cover/assets/121165794/189e910e-e604-4cfb-8262-29cda5632bba)

## Result:
Book cover page is created.
