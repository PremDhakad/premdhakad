<html>
    <head> 
        <title>Job Application by prem</title>
        <style>
            h1{
               border-style: solid;
                margin-right: 30%;
                border-color :red;
                color: midnightblue;
                font-family:monospace;
                align-content: center;
                text-align: center;
                
            }
            form{
                color: blue;
                background-color:floralwhite;
                align-items: center;
                text-align: center;
                border-style: solid;
                margin-right: 30%;
                font-size: 150%;
            }
            input{
                color:blue;
                font-size: 90%;
            }
            
        
        
        
        </style>
    </head>
    <body>
<!--        <canvas id="myCanvas" width="200" height="100" style="border:1px solid green;"></canvas>-->
        <h1 >Job Application Form</h1>
        <form >
        <label>Name:</label>
        <input type="text" placeholder="Ex.Pradum">
        <br>
        <label>Last Name:</label>
        <input type="text" placeholder="Ex.Dhakad">
        <br>
        <label>Email:</label>
        <input type="email" placeholder="prddkd@gmail.com">
        <br>
        <label>Password:</label>
        <input type="password">
        <br>
        <label>Date of Birth</label>
        <input type="date" min="1990-01-01" max="2000-01-01" >
        <br>
        <label>Gender:</label>
        <input type="radio" value="Male" name="Gender">Male
        <input type="radio" value="Female" name="Gender">Female
        <input type="radio" value="Other" name="Gender">Other
        <br>
        <label>Country:</label>
        <select>
            <option value="India">India</option>
            <option value="USA">USA</option>
            <option value="UK">UK</option>
        </select>
        <br>
        <label>Technical Skills:</label>
        <input type="checkbox" value="Java">Java
        <input type="checkbox" value="SQL">SQL
        <input type="checkbox" value="Web">Web
        <br>
<!--        Upload Picture-->
        <label>Upload Picture:</label>
        <input type="file">
        <br>
<!--        Comment-->
        <label>Comment:</label>
        <textarea>Write here.</textarea>
        <br>
        <input type="reset" value="reset">
        <input type="submit" value="submit" name="submit">
            </form>
        
        
    </body>
</html>
