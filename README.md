<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
      *{
    margin: 0;
    padding: 0;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
.cv{
    margin-left: 200px;
    margin-top: 30px;
    padding:20px 10px 10px 50px;
    border: 3px solid black;
    margin-right: 300px;
}
#cv1,#cv2,#cv3,#cv4,#gap1{
    color: rgb(13, 135, 29);
    height: 10px;
    margin-top: 15px;
}
#cv2,#cv3,#cv4{
    margin-bottom: 20px;
}
#gap{
    margin-top: 30px;
    
}
a{
    text-decoration: none;
}

#blue{
    color: rgb(24, 96, 213);
}
hr{
   margin-right: 100px;
}
    </style>
</head>
<body>

   <div class="cv">
      <hr>
<h2>Your Name</h2>
<p id="cv1">junior frontend developer</p><br>
123 Your Street<br>
Your City, ST 12345<br>
(123) 456-7890<br>
no_reply@example.com<br><br>

<p id="cv2">Skills</p>
HTML, CSS, JavaScript, Accessibility, Figma to Design, Responsive Web Design,<br>
Technical Writing, Presentation<br><br>

<p id="cv3">Education</p>
School Name, Location - Degree<br>
Month 20xx to Month 20xx<br>
List of exciting things you did at university<br><br>

<p id="cv4">Experience</p>
<p class="gap">
   <p id="blue">Company Name, Location - Job Title</p><br>
    Month 20xx to Month 20xx<br><br>
   <ul>
    <li>list of achievements</li>
    <li>list of achievements</li>
    <li>list of achievements</li>
   </ul><br>
    Skills: List of skills used or gained at this company</p> <br>
      <p id="gap1">Across the internet</p><br>
      <a href="#">add your links</a>
   </div> 



</body>
</html>
