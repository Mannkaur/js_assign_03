Closure, as the name indicates, to close something.
Closure is nothing more than a nested/inner function which may continue to live even after its outer function has finished.
Closure is a function and scope chain (an environment within which it is created) associated with it.
To make it understandable in a layman language,
Let's consider a person named as F2 who graduated from college F1 and has friends say x. Now, even college is ended, still person remembers his friends.
Now, comparing with this example, closures as person (F2), function as college (F1) and scope chain/lexical scope as friends(x). We get
                                                 Closure = Function + Scope Chain
This means, Closure is, when a function is able to remember and access its lexical scope even when that function is executing outside its lexical scope.

You can create closure by adding a function inside a function or any time you can nested function, you have a closure there.
It can access not only to variables defined within them but also its outer function's variables in addition to global variables.
Closures are the way to hide your code from public eye. Even global variables can be made private. With closures, you can easily have private members that are shielded from outside world. Closures are the key thing to achieve privacy in JavaScript.


References:
https://code.tutsplus.com/tutorials/closures-front-to-back--net-24869
http://javascript.info/tutorial/closures
http://www.w3schools.com/js/js_function_closures.asp
https://medium.freecodecamp.com/lets-learn-javascript-closures-66feb44f6a44#.140sc2wco
http://www.bing.com/videos/search?q=javascriot+closures&&view=detail&mid=D193E9969C50F428AD73D193E9969C50F428AD73&rvsmid=36971D43074C92E7BC4