#### JS Extensible Dice InitiativE (jeDIE) ####
A string parser that extracts nd replaces dice rolls in text
by Jay Crossler, Open Source CC-BY license


### To include the library, use ###
    <script type="text/javascript" src="diceRoller.js"></script>

### To pass a string to encode, use ###
    <script type="text/javascript">
        var revisedText = TextParsers.replaceDiceRolls("I Roll [5W] or [3d6+10],'fullhtml');
        alert(revisedText);
    </script>

##Instead of using 'fullhtml', the formatting options are ##
longhtml : html, longer text showing each die result, mouseover for more details
fullhtml : html, all dice rolls listed in page
shorthtml: html, short concatenation of all die rolls
longtext : text, showing ech die result in shorthand
shorttext: text, showing result
result   : number, resulting total or total number of successes


### Other pages ###
rollTester.html gives a testing page that makes it easier to validate and test content
diceMatrix.html gives a matrix of many die rolls



### You can style the dice roll text output ###
    <style>
        .rollresponse {background-color: #caf;}
        .dieinput {font-style: italic; font-size: small;}
        .dieresult {font-weight: bold; border:1px solid blue;}
        .diesuccess {background-color: #4D4;}
        .diefailure {background-color: #d88}
    </style>
