#Thursday Notes


##GIT Flow
Repository—collection of files
Remote—where you are storing those files, someplace other than your computer (alias to a URL for a location where you have a copy of the repository)
Branch—bookmark within your repository that marks where you have a set of changes

git status
git checkout -b "thursday" (creates branch)
touch notes/thursday-name.md (creates notes file)
git add notes/thursday-name.md (adds notes file to git)
git commit -m "notes" (commits file to tracking)
git push (command) origin (name of remote location) thursday (branch)

##Expressions



##truthy / falsey

true is 1
false is 0

1 is truthy
0 is falsey

'thursday' is truthy
undefined / null is falsey

if there's something there, it will evaluate as truthy
if it's false, undefined or null, it will evaluate as falsey

=== (always use, strict comparison with greater precision)
== (true-ish)

##if / else

##for

##functions
* named
* anonymous—declaring a function without a name. How can one do that? Assign the function into a variable. (local)
* IIFE's (Immediately Invoked Function Expression)

function () {} *parameters are in parens*
function doSomething () {} *named function*

myFunction(); *this is the syntax that invokes function*
or doSomething()

put function at bottom.
convention for naming functions is verb (since they are actions)

var doSomething = function() {}

declaring function (specify the variable we are going to accept)
invoke the function (specify the actual values we are going to pass)

##Shortcut
Command + / to quickly comment out code in Atom

##other

1. Make it run
2. Make it right
3. Make it fast
4. Make it pretty

DRY—Don't Repeat Yourself—looking for lines of code that are identical, or follow the same pattern

Timeboxing!
