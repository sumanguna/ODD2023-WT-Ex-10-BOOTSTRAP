# Ex-10-BOOTSTRAP
# EX-10(1):
# AIM:
Create a Responsive feedback form for a virtual workshop on Constructing Modern Websites built with Bootstrap.

# DESIGN STEPS:10(1) :
# STEP 1:
Initialize the HTML document.

# STEP 2:
Create the body structure.

# STEP 3:
Construct the form

# STEP 4:
Add a submit button and Link Bootstrap JavaScript.

# CODE 10(1) :
'''DEVELOPED BY: SUMAN.G NO:212223240163'''

```
<html>
  <head>
    <title> Feedback Form | Virtual Workshop on Constructing Modern Websites</title>
    <link rel="stylesheet" href="style.css">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
   </head>
<body>
  <div class="container">
    <div class="title">Feedback</div>
    <div class="content">
      <form action="#">
        <div class="user-details">
         
 <div class="input-box">
            <span class="details">First Name</span>
            <input type="text" placeholder="Enter your 1st name" required>
            </div>

<div class="input-box">
            <span class="details">Last Name</span>
            <input type="text" placeholder="Enter your last name" required>
            </div>

          <div class="input-box">
            <span class="details">Email</span>
            <input type="text" placeholder="Enter your email" required>
          </div>

          <div class="input-box">
            <span class="details">Phone Number</span>
            <input type="text" placeholder="Enter your number" required>
          </div>
        </div>

        <div class="rating-details">
          <input type="radio" name="rate" id="dot-1">
          <input type="radio" name="rate" id="dot-2">
          <input type="radio" name="rate" id="dot-3">
          <input type="radio" name="rate" id="dot-4">
          <input type="radio" name="rate" id="dot-5">
          <span class="rate-title">Rating</span>

          <div class="category">
            <label for="dot-1">
            <span class="dot one"></span>
            <span class="rate">1</span>
          </label>

          <label for="dot-2">
            <span class="dot two"></span>
            <span class="rate">2</span>
          </label>

          <label for="dot-3">
            <span class="dot three"></span>
            <span class="rate">3</span>
            </label>

          <label for="dot-4">
            <span class="dot four"></span>
            <span class="rate">4</span>
            </label>

          <label for="dot-5">
            <span class="dot five"></span>
            <span class="rate">5</span>
            </label>

          </div>
        </div>
        <div class="button">
          <input type="submit" value="Post">
        </div>
      </form>
    </div>
  </div>
</body>
</html>

```
# OUTPUT 10(1):
