ml>
    <head>
        <meta charset="utf-8">
        <title>Using external stylesheets</title>
        <style>
        body {
            background: rgb(215, 250, 220);
            font-family: sans-serif;
        }
        
        .header {
            background-color: rgb(36, 89, 36);
            color: white;
            padding: 5px 10px;
        }
        
        .footer {
            background-color: rgb(186, 222, 187);
            padding: 6px;
            clear: both;
        }
        
        #hopper-pic {
            width: 100px;
            float: left;
            margin-right: 6px;
            margin-bottom: 6px;
            
        }
        
        #hopper-links {
            float: right;
            width: 30%;
            margin-left: 10px;
        }
        </style>
    </head>
    <body>
        
    <div class="header">
        <h1>All about Hopper</h1>
    </div>
     
    <div id="hopper-links">
        <h3>Cool links</h3>
        <p>Here's how you can learn more about Grace Hopper, and everything she's inspired.</p>
        <ul>
            <li><a href="http://en.wikipedia.org/wiki/Grace_Hopper">Wikipedia article</a></li>
            <li><a href="https://www.youtube.com/watch?v=1-vcErOPofQ">Grace Hopper on Letterman</a></li>
            <li><a href="http://gracehopper.org/">Grace Hopper conference</a></li>
        </ul>
    </div>
      
    <p id="hopper-bio">
    <img id="hopper-pic" src="https://www.kasandbox.org/programming-images/creatures/Hopper-Cool.png">
      I'm Hopper! I was named after Grace Hopper, one of the first American computer scientists and an admiral in the Navy. Grace Hopper invented the term "debugging" for fixing computer bugs, after finding a moth in a computer, plus she invented the first compiler.
    </p>
    
    <div class="footer">
        <p>Contact me for more info at 1-800-HOPPER.</p>
    </div>

    </body>
</html>
   
