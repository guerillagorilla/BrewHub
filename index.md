# BrewHub

## Used to track coffee consumption and money owed.

<center>This is another test.</center>

<div class="tutorialWrapper">
<body>
    <form>
        <div class="fieldWrapper">
            <label for="pass1">Password:</label>
            <input type="password" name="pass1" id="pass1">
        </div>
        <div class="fieldWrapper">
            <label for="pass2">Confirm Password:</label>
            <input type="password" name="pass2" id="pass2" onkeyup="checkPass(); return false;">
            <span id="confirmMessage" class="confirmMessage"></span>
        </div>
    </form>
    <script type="text/javascript">
    
    function checkPass() {
        //Store the password field objects into variables ...
        var pass1 = document.getElementById('pass1');
        var pass2 = document.getElementById('pass2');
        //Store the Confimation Message Object ...
        var message = document.getElementById('confirmMessage');
        //Set the colors we will be using ...
        var goodColor = "#66cc66";
        var badColor = "#ff6666";
        //Compare the values in the password field 
        //and the confirmation field
            if(pass1.value == pass2.value) {
                //The passwords match. 
                //Set the color to the good color and inform
                //the user that they have entered the correct password 
                pass2.style.backgroundColor = goodColor;
                message.style.color = goodColor;
                message.innerHTML = "Passwords Match!"
        } else {
            //The passwords do not match.
            //Set the color to the bad color and
            //notify the user.
            pass2.style.backgroundColor = goodColor;
            message.style.color = goodColor;
            message.innerHTML = "Great Job!"
        }
    }  

NEW TEXT
</script>
</body>
</div>



