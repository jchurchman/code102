git steps
What's going on?                      git Status
Create BRANCH                         git checkout -b <FILENAME>
Create new file                       git touch <directory>\<filename>
Stage new file for committing         git add <directory>\<FILENAME>
Commit newly made file to local repo  git commit -m "<COMMIT MESSAGE>"
push new file to remote repo          git push origin <directory>

Vocab
repository = collection of files
remote = literally an alias for a URL that is the location of the copy of your repo
branch = bookmark of changes in files of repository

Shortcuts
"ctrl + /" shortcut for "comment out" a block of code


Javascript concepts:
truthy - 1, 'thursday', 8, 28.65, 'false'
falsey - 0, undefined, null, false,

= defines a variable
== can X equate Y? For Example: "2 == '2' yields a result of 'true'"
=== tests perfect truthiness

semicolons end expressions
functions should have verb names
variables should have noun names


Advice:
1. Make it run
  then make it right
  then make it fast (pretty)
2. DRY
  Don't
  Repeat
  Yourself

  Fun with Functions
    general syntax for a function:
      function () {
        <CODE BLOCK>
        <CODE BLOCK>
      }
    Named Functions:
      function doSomething() {
        <CODE BLOCK>
        <CODE BLOCK>
      }
      commonly declared at the end/bottom of the code b/c it gets hoisted/created first
    Anonymous Function:
      function () {
        <CODE BLOCK>
        <CODE BLOCK>
      }
      anonymous functions can be defined as a variable
        var doSomething =  function () {
                              <CODE BLOCK>
                              <CODE BLOCK>
                            }
      does NOT get hoisted/created first
    Invoking a function: nameOfFunction() OR nameOfVariableThatHousesFunction()
    IIFE Functions:
      Immediately Invoked Function Expression
      anonymous functions that are immediately called
      only used once in a code
      the code for the function acts as the call for the function
      (function(<Var>) {
        var play = "We're playing " + ballType + " with an IIFE!";
        console.log(play)
        }(rugby));


Function Review:
  function add(num1, num2) {
    return num1 + num2;
  }

  var subtract = function (num1, num2) {
    return num1 - num2;
  };

  (function(first, second) {
    add(first, second);
    }(4,6));

Name parameters when you define your function
Provide values (parameters) when you call your function
