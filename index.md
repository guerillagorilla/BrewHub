# BrewHub

## Used to track coffee consumption and money owed.

<div class="tutorialWrapper">
<body>
    <script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js'></script>
    <form>
        <div class="fieldWrapper">
            <label for="pass1">Password:</label>
            <input type="password" style="text-align:right" name="pass1" id="pass1">
        </div>
        <div class="fieldWrapper">
            <label for="pass2">Confirm Password:</label>
            <input  type="password" style="text-align:right" name="pass2" id="pass2" onkeyup="checkPass(); return false;">
            <span id="confirmMessage" class="confirmMessage"></span>
        </div>
    </form>
    <content>
        <div id="box1" class="box">Click Count: <span class="num">0</span></div>
    </content>
    <script type="text/javascript" src="/BrewHub/assets/js/test.js"></script>
</body>
</div>



