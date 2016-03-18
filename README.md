Obscure JavaScript Examples
===========================

Code from [obscurejavascript.tumblr.com](http://obscurejavascript.tumblr.com) in an easy to download format. All of the code can be run in Node.js and most of it in a browser (what can't is noted below). A few posts require libraries and these are found in the node_modules folder and are specified by packages.json. This is a standard NPM layout.

*Just like the blog, there may be some examples that do not good follow JavaScript patterns for demonstration purposes.*

Example Explanations
====================

Each example corresponds directly to a blog post:

<h5>2016</h5>
<hr/>
* [callLater.js](http://obscurejavascript.tumblr.com/post/140584717376/calllater-in-javascript): A function to store functions to be called later.
* [compose.js](http://obscurejavascript.tumblr.com/post/140984777408/compose-in-javascript): A function used to simplify sequences of functions.
* [functionToString.js](https://github.com/Jacob-Friesen/obscurejs/blob/master/2016/functionToString.js): About the Function.toString method and how it can be used for debugging and function regeneration.
* [observable.js](http://obscurejavascript.tumblr.com/post/137500537300/observables-in-javascript): How to treat data that arrives over time in an array like fashion.
* [proxy.js](http://obscurejavascript.tumblr.com/post/138429574082/proxies-in-javascript): How to change JavaScript syntax on given objects via the Proxy API.
* [replace3rdArg.js](http://obscurejavascript.tumblr.com/post/139312155038/the-stringreplace-callback-in-javascript): How to use the little known ability of String.replace to accept callbacks.
* [compose.js](#): Return a function that calls the passed in callback with reversed arguments.
* [selfRegeneration.js](http://obscurejavascript.tumblr.com/post/139742651734/object-self-regeneration-in-javascript): How an object can regenerate itself. This is useful when the object constructor is lost.
* [stub.js](http://obscurejavascript.tumblr.com/post/137969738765/simple-asynchronous-javascript-stubs): A simple one function method of stubbing functions including asynchronous ones.
* [void.js](http://obscurejavascript.tumblr.com/post/138877228983/void-in-javascript): Uses of the void keyword. Best understood in conjunction with the blog post in this case.

<h5>2015</h5>
<hr/>
* [argumentParameterBinding.js](http://obscurejavascript.tumblr.com/post/122101479376/javascript-arguments-and-function-parameter): A demonstration of a little known arguments object quirk.
* [arrowFunctions.js](http://obscurejavascript.tumblr.com/post/131956254400/arrow-functions-in-es6-javascript): How to implement arrow functions in pre ES6 JavaScript.
* [beforeAndAfter.js](http://obscurejavascript.tumblr.com/post/118047746815/before-and-after-in-javascript): A before function with an extension into an after one.
* [bind.js](http://obscurejavascript.tumblr.com/post/107819323140/bind-in-javascript): Bind and an example of it in JavaScript.
* [chainify.js](http://obscurejavascript.tumblr.com/post/126848395566/a-function-to-make-any-object-chainable): How to build a generic chaining method that can add chaining to any object.
* [circularReference.js](http://obscurejavascript.tumblr.com/post/122697146656/javascripts-circular-references): Circular references and potential issues with them. Does not go into all the details, more of an overview.
* [circularReferencePositives.js](http://obscurejavascript.tumblr.com/post/123302560591/circular-references-the-positives): Positives of circular references.
* [class.js](http://obscurejavascript.tumblr.com/post/134216232213/classes-in-es6-javascript): Classes in ES6 and how to create a close equivalent.
* [clone.js](http://obscurejavascript.tumblr.com/post/110468721243/deep-copy-in-javascript): How to deep copy objects in JavaScript.
* [const.js](http://obscurejavascript.tumblr.com/post/135135024082/const-in-es6-javascript): The const keyword in ES6 and how to create a close equivalent.
* [debounce.js](http://obscurejavascript.tumblr.com/post/115595038489/debounce-in-javascript): Create a wrappped function so that the function it wraps is only called after it stops being triggered every n milliseconds.
* [defer.js](http://obscurejavascript.tumblr.com/post/113091822041/defer-in-javascript): Run a function after all processing is done in the current callstack.
* [dependencyInversion.js](http://obscurejavascript.tumblr.com/post/109803267466/monads-in-javascript): Screwed up the monad post. So just the dependency inversion part will be kept.
* [floatingPointArithmetic.js](http://obscurejavascript.tumblr.com/post/129013057189/floating-point-arithmetic-in-javascript): A simple algorithm strategy for reliably calculating decimal based numbers.
* [flow.js](http://obscurejavascript.tumblr.com/post/113715151349/flow-in-javascript): This is used to string functions that use each others results in a chain.
* [functionDecompilation.js](http://obscurejavascript.tumblr.com/post/119214042002/function-decompilation): Function decompilation, Angular.js and simplified dependency injector for it.
* [functionExpressionProperties.js](http://obscurejavascript.tumblr.com/post/127416893771/using-named-function-expressions-properties-in): How properties on object can be used to simplify code. Specifically, with named Function Expressions.
* [generator.js](http://obscurejavascript.tumblr.com/post/133745153006/generators-in-es6-javascript): How to implement a relatively close equivalent of generators in pre ES6 JavaScript.
* [genericChaining.js](http://obscurejavascript.tumblr.com/post/125694248566/generic-chaining-in-javascript): An explanation of a simple generic pattern for creating chainable objects.
* [interatedAsyncCalls.js](http://obscurejavascript.tumblr.com/post/112442518446/issues-with-iterated-asynchronous-calls-in): How to solve a seemingly wierd issue while passing state to multiple asynchronous calls in JavaScript.
* [iterator.js](http://obscurejavascript.tumblr.com/post/131438691771/iterators-in-es6-javascript): A simple implementation of the ES6 iterator abstraction in non ES6 JavaScript (without an Iterable implementation).
* [lazyFunctionDefinition.js](http://obscurejavascript.tumblr.com/post/128172325331/lazy-function-definitions-in-javascript): Caching values without using conditionals. This is useful for calls that need to be made multiple times.
* [mapObject.js](http://obscurejavascript.tumblr.com/post/130495034293/the-map-object-in-es6-javascript): An implementation of the map object in ES6 in less than ES6 JavaScript.
* [mapOrRemove.js](http://obscurejavascript.tumblr.com/post/123911209628/map-or-remove-in-javascript): A function used to filter and modify objects.
* [mapsThirdArgument.js](http://obscurejavascript.tumblr.com/post/124508304377/maps-third-argument-in-javascript): How the 3rd argument in map() can be used to operate on multiple array elements at once.
* [memoize.js](http://obscurejavascript.tumblr.com/post/111106381319/memoize-in-javascript): A way to automatically cache function calls.
* [nonMutatingAssign.js](http://obscurejavascript.tumblr.com/post/129512291001/non-mutating-assign-in-javascript): Showing the implementation of a function similar to Lodash assign and how to not mutate with it. 
* [oneLineRandomText.js](http://obscurejavascript.tumblr.com/post/125694248566/generic-chaining-in-javascript): How to generate short random text codes in JavaScript in one line using no library functions.
* [sortsAndNan.js](http://obscurejavascript.tumblr.com/post/125103356483/sorts-and-nan-in-javascript): What NaN return values do to JavaScript's default sort.
* [templateStrings.js](http://obscurejavascript.tumblr.com/post/132413275313/template-strings-in-es6-javascript): Evaluating strings with expressions in JavaScript similar to ES6 templates.
* [let.js](http://obscurejavascript.tumblr.com/post/133287385450/let-in-es6-javascript): The ES6 let statement and how to emulate close aproximations.
* [monad.js](http://obscurejavascript.tumblr.com/post/111788543345/monads-in-javascript): Defining a chainable specification of operations.
* [multiIf.js](http://obscurejavascript.tumblr.com/post/121526887468/cleaning-up-complex-conditionals-with-chaining): Making complex conditionals more readable by using an expression and chaining conditions.
* [multicore.js](http://obscurejavascript.tumblr.com/post/134675242340/multicore-javascript-with-nodejs): Multicore node.js code. **Node.js Only**
* [omit.js](http://obscurejavascript.tumblr.com/post/114336196594/omit-in-javascript): Return an object with properties removed with no side effects.
* [primitiveCoercion.js](http://obscurejavascript.tumblr.com/post/128642547205/primitive-coercion-in-javascript): A brief explanation of automatic primitive coercion in JavaScript.
* [promise.js](http://obscurejavascript.tumblr.com/post/117449806524/promises-in-javascript): Create an object that represents future state.
* [undefined.js](http://obscurejavascript.tumblr.com/post/116842290598/undefined-in-javascript): An explanation of the undefined type.
* [repl.js](http://obscurejavascript.tumblr.com/post/120957199678/a-repl-for-javascript-in-javascript): A REPL of JavaScript in JavaScript using streams. **Node.js Only**
* [server.js](http://obscurejavascript.tumblr.com/post/119785644766/4-line-node-js-http-test-server): A 4 line http server using connect.js and serve-static.js **Node.js Only**
* [setObject.js](http://obscurejavascript.tumblr.com/post/130966866306/the-set-object-in-es6-javascript): An implementation of the set object in ES6 in less than ES6 JavaScript.
* [stream.js](http://obscurejavascript.tumblr.com/post/120374509401/node-js-streams): A simple example of streams **Node.js Only**
* [symbol.js](http://obscurejavascript.tumblr.com/post/132877236317/symbols-in-es6-javascript): Implementing ES6 Symbols in pre ES6 syntax.
* [thisKeyword.js](http://obscurejavascript.tumblr.com/post/116172560774/how-this-can-be-modified-in-javascript): An attempt of defining all the possible ways that the *this* context is defined.
* [throttle.js](http://obscurejavascript.tumblr.com/post/114959169455/throttle-in-javascript): Create a wrappped function so that the function it wraps is called at most every n milliseconds.
* [trim.js](http://obscurejavascript.tumblr.com/post/135590649158/trim-in-javascript): The trim string function and polyfills for trimLeft and trimRight.
* [typedArray.js](http://obscurejavascript.tumblr.com/post/137036713404/typed-arrays-in-javascript): A simple demonstration of the differences between Array and a Typed Array.
* [where.js](http://obscurejavascript.tumblr.com/post/108473136150/where-in-javascript): Code for the JavaScript where function.
* [unionAndIntersection.js](http://obscurejavascript.tumblr.com/post/109132410484/intersection-and-union-in-javascript): Code for the intersection and union array manipulation functions and the unifyling function.
* [variableChaining.js](http://obscurejavascript.tumblr.com/post/118630892587/variable-chaining-and-globals-in-javascript): How variable chaining can create globals and how global creation can be avoided.
* [zip.js](http://obscurejavascript.tumblr.com/post/107136419970/zip-in-javascript): How to use a function that automatically structures raw array data.

<h5>2014</h5>
<hr/>
* [assign.js](http://obscurejavascript.tumblr.com/post/105199465669/assign-in-javascript): How to use and implement a function that merges objects.
* [autoExecutingRecursionFunctions.js](http://obscurejavascript.tumblr.com/post/73013181197/auto-executing-recursive-functions): How to create functions that can be called without parenthesis. Or other helpers.
* [bracketFreeCall.js](http://obscurejavascript.tumblr.com/post/87491571318/paren-free-function-calls): How to create functions that can be called without parenthesis. Or other helpers.
* [caseForLinting.js](http://obscurejavascript.tumblr.com/post/102806165655/a-case-for-linting-in-javascript): Example of why linting should be used in JavaScript. See blog post for more info.
* [chaiAndParenFree.js](http://obscurejavascript.tumblr.com/post/87981579491/chai-js-and-paren-free-calls-in-javascript): How Chai.js uses bracket (parent) free calls.
* [cleanSwitches.js](http://obscurejavascript.tumblr.com/post/83829086495/a-cleaner-way-to-do-switches-in-javascript): A cleaner way of long decision branches.
* [cleanCallbacks.js](http://obscurejavascript.tumblr.com/post/79867797983/cleaning-up-javascript-callbacks): A clean way of ordering JS callbacks using an object.
* [comprehensions.js](http://obscurejavascript.tumblr.com/post/92833095461/javascript-list-comprehensions): A quick way to do list operations in JS, list comprehensions. Commonly, used in other scripting languages.
* [computedProperties.js](http://obscurejavascript.tumblr.com/post/93680556182/computed-property-values-in-literals): A proposal for computed property literals in JavaScript and how to implement a near equivalent.
* [constant.js](http://obscurejavascript.tumblr.com/post/97472306093/real-constants-in-javascript): How to implement real constants in JavaScript.
* [curry.js](http://obscurejavascript.tumblr.com/post/103825579554/curries-in-javascript): How to implement a function that splits a multi argument function into a series of single argument ones.
* [date.js](http://obscurejavascript.tumblr.com/post/91548405930/dates-in-javascript): JavaScript date comparions.
* [decorators.js](http://obscurejavascript.tumblr.com/post/82388140032/implementing-decorators-in-javascript-using-closures): How to implement decorators in JS using closures.
* [explicitBooleanConversion.js](http://obscurejavascript.tumblr.com/post/76532933108/explicit-boolean-coercion): Using explicit Boolean conversion to save time.
* fibonacci.rb: A fibonacci sequence in Ruby. Syntax emulated in ruby.js.
* [flatten.js](http://obscurejavascript.tumblr.com/post/89552294013/flatten-in-javascript): How to write a simple array flattening function.
* [fold.js](http://obscurejavascript.tumblr.com/post/89068550361/folds-in-javascript): A useful higher order function explained.
* [functionExpressionsVsDeclarations.js](http://obscurejavascript.tumblr.com/post/102207548636/the-difference-between-function-declarations-and): A subtle difference between function expressions and declarations.
* [functionalInheritance.js](http://obscurejavascript.tumblr.com/post/98733772655/javascript-inheritance-strategy-1-functional): How functional inheritance works. 
* [constant.js](http://obscurejavascript.tumblr.com/post/97472306093/real-constants-in-javascript): An explanation of the potiential issues of not using new for object instantiations and a way to combat it.
* [multipleInheritance.js](http://obscurejavascript.tumblr.com/post/100430383994/multiple-inheritance-in-javascript): One way to implement multiple inheritance.
* [new.js](http://obscurejavascript.tumblr.com/post/98144418406/using-new-vs-not-using-new-in-javascript): The pitfalls of not using new before object initializations and an alternative.
* [nodePolyglot.js](http://obscurejavascript.tumblr.com/post/86791947037/node-polyglots): How to use Bash in combination with Node.js to make the script executable without a node command across multiple OSs. **Node.js Only**
* [objectInitializerShorthand.js](http://obscurejavascript.tumblr.com/post/95642604521/traceur-object-initializer-shorthand-in-current-js): An implementation of JS.next's object initializer shorthand.
* [once.js](http://obscurejavascript.tumblr.com/post/104606556389/once-in-javascript): An implementation and usage example of a once function.
* [pluckAndUnique.js](http://obscurejavascript.tumblr.com/post/105799098478/pluck-and-unique-in-javascript): How pluck and unique functions are
* [private.js](http://obscurejavascript.tumblr.com/post/90848733484/private-variables-in-javascript): Private Variables in JavaScript and their uses.
* [prototypalInheritance.js](http://obscurejavascript.tumblr.com/post/99651761063/javascript-inheritance-strategy-3-prototypal) How Prototypal Inheritance works.
* [psuedoClassicalInheritance.js](http://obscurejavascript.tumblr.com/post/99247110986/javascript-inheritance-strategy-2-pseudoclassical) How Psuedoclassical Inheritance works.
* [range.js](http://obscurejavascript.tumblr.com/post/92238246124/a-range-operator-for-javascript): A range operator in JavaScript.
* [restParameters.js](http://obscurejavascript.tumblr.com/post/95097113886/traceur-rest-parameters-in-current-js): Implementing JS.next's rest parameters in vanilla 
* [ruby.js](http://obscurejavascript.tumblr.com/post/90251062581/imitating-ruby-in-javascript): A close aproximation to Ruby's syntax in JavaScript.
* [rubyMethodSyntax.js](http://obscurejavascript.tumblr.com/post/85524888334/rubys-math-method-syntax-in-javascript): How to use ruby math method like syntax in JS.
* [spread.js](http://obscurejavascript.tumblr.com/post/94247680464/spread-vs-apply-in-javascript): JS.next spread and a close alternative.
* [stringInterpolation.js](http://obscurejavascript.tumblr.com/post/74389765835/javascript-string-interpolation): Implementing string interpolation.
* [super.js](http://obscurejavascript.tumblr.com/post/101001619389/super-in-javascript): Implementing super in JavaScript (using functional inheritance).
* [superThatIsEfficient.js](http://obscurejavascript.tumblr.com/post/101608780722/efficient-super-calls-in-javascript): Implementing super in JavaScript in a more efficient way. Specifically, using PsuedoClassical Inheritance.
* [trackingJSStatistics.js](http://obscurejavascript.tumblr.com/post/80464717044/tracking-javascript-statistics): Building a simple function call tracker.
* [toStringFunctionTriggers.js](http://obscurejavascript.tumblr.com/post/77487572765/tostring-based-function-triggers): Calling functions by using the '+' operator.
* [withEmulation.js](http://obscurejavascript.tumblr.com/post/78333366271/emulating-the-with-statement-in-javascript): Emulating the JS with statement via a function.

<h5>2013</h5>
<hr/>
* [arrayInstantiations.js](http://obscurejavascript.tumblr.com/post/64389973002/hardcore-array-instantiations): A compact way to declare pre-initialized arrays in JS.
* [batman.js](http://obscurejavascript.tumblr.com/post/51075341151/batman-arrays-and-javascript-collide): The weird behavior of Array.join demonstrated.
* [chaining.js](http://obscurejavascript.tumblr.com/post/50657613243/chaining-javascript-self-invoking-function-calls): Chaining self invoking function calls to shorten code.
* [defaults.js](http://obscurejavascript.tumblr.com/post/55779896076/clean-default-values-in-javascript): A much better way to do default values in JS.
* [erlang.js](http://obscurejavascript.tumblr.com/post/56604431893/erlang-in-javascript): Emulating Erlang in JS.
* [expressions.js](http://obscurejavascript.tumblr.com/post/61814998019/advanced-javascript-expressions): Using expressions to simplify code in JS.
* [functionCallInheritance.js](http://obscurejavascript.tumblr.com/post/66874710993/inheritance-with-function-call): How Function.call() can be used to create inheritance in JS.
* [functionConstructor.js](http://obscurejavascript.tumblr.com/post/65893136656/the-javascript-function-constructor): How the Function constructor works.
* [functionDeclerationOperations.js](http://obscurejavascript.tumblr.com/post/63861215073/operations-on-javascript-function-declerations): How function declerations (not just calls) can actually be used in arithmetic operations.
* [innerFunctionTesting.js](http://obscurejavascript.tumblr.com/post/69080603746/easily-testing-inner-functions-in-js): How to test inner functions in JS.
* [metaprogramming.js](http://obscurejavascript.tumblr.com/post/51730042465/javascript-metaprogramming) Using metaprogramming to simplify stuff in JS. **Browser Only** 
* [multipleValueChecking.js](http://obscurejavascript.tumblr.com/post/65231120961/clean-mulitple-value-checking): A good way to check multiple values at once in JS.
* [multipleReturnValues.js](http://obscurejavascript.tumblr.com/post/57795427130/multiple-return-values-in-javascript-a-new-way): A good way to return multiple variables in JS.
* [labeledLoops.js](http://obscurejavascript.tumblr.com/post/53519194124/labeled-loops-in-javascript): Did you know that JavaScript has labeled loops?
* [listOperatorMagic.js](http://obscurejavascript.tumblr.com/post/59141181114/list-operator-magic): How to expliot JSs list operator to shorten code.
* [obscureIntegers.js](http://obscurejavascript.tumblr.com/post/52949238843/extremely-obscure-javascript-integers) You should see it for yourself.
* [obscureStrings.js](http://obscurejavascript.tumblr.com/post/52302750125/extremely-obscure-javascript-strings) You should see it for yourself.
* [overloadingArrayOperators.js](http://obscurejavascript.tumblr.com/post/60174354628/overloading-array-operators-in-javascript): What is possible by overloading array operators in JS. This led me to discover how to run functions paranthesis free. **Node.js Only**
* [overloadingFunctions.js](http://obscurejavascript.tumblr.com/post/57179890654/overloading-functions-in-javascript): How to make overridable functions in JS.
* [partials.js](http://obscurejavascript.tumblr.com/post/67961302246/partials-in-javascript): How to create partials and some applications.
* [perl.js](http://obscurejavascript.tumblr.com/post/54101830984/imitating-perl-in-javascript): Emulation perl in JS.
* [recursion.js](http://obscurejavascript.tumblr.com/post/62719895830/recursion-in-javascript-without-making-a-recursive-call): Recursion without making a recursive call. I'm not joking.
* [scheme.js](http://obscurejavascript.tumblr.com/post/55175533448/imitating-scheme-lisp-dialect-in-javascript): Emulating scheme in JS.
