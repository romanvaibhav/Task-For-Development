# Task-For-Development
1) Daily Task: (28-2-2024):-  ([https://www.youtube.com/watch?v=ZzmiJsD6HIo&list=PLFmBehh3Qjxr5_cwDBybRyjt-0E0fObgM&index=2&ab_channel=SmallTownCoder](https://www.youtube.com/watch?v=oH9DWKMM0Os&list=PLFmBehh3Qjxr5_cwDBybRyjt-0E0fObgM&ab_channel=SmallTownCoder)) <br>
Watch 1st 3 videos from above link <br>
Note:- Send Me Dry run cod ePhotos also <br>
2)DO DSA 3 quetions:-<br>
1)  https://docs.google.com/document/d/1jwhMD49HKTBz0uwtBfMjdf_JiDdYAcfr-xQLWtH9oYs/edit?tab=t.0 <br>
2)  Note:-- Send me the dry run code photos also <br>

3) Search Links and apply<br>
CanvasListBookmark folder
Pinned messages
  Apr 11th at 5:46 PM
Ajay react interview

babel vs webpack
react vs angular
Agular onInit
package.json ^ vs ~
package.json vs package.lock.json
hoising
codes - palindrom and reverse string
closure
useEffect vs useLayout
shadow dom vs virtual dom
center div
how to handle 10 thousand user in single page -- virutualization and pagination
angular faster or react faster
react hooks
explain the hooks which you use
tailwind vs material ui
which do you prefer angular or react
optimise react app
error boundary
suspense
lazy loading
how to handle error
how to use promise in react
which library you use in the project
store mangement
child to parent data communication in react
when to you redux store and context
can we use service in the react
props drilling
debounding and throttling

(edited)
  Mar 25th at 12:12 PM

const a = [1,2,3]
const b = [1,2,3]
console.log(a==b)

function example() {
  var x = 10;
  if (true) {
    let y = 20;
    console.log(x, y);
   }
   console.log(x, y); 
}
example();

const age2 = calcAge2(1987);
console.log(age2);

const calcAge2 = function(birthYear){
    return 2025-birthYear;
}

const age1 = calcAge1(1987);
console.log(age1);

function calcAge1(birthYear){
    return 2025-birthYear;
}

function wait(delay) {
// implementation
	
	return Promise((resolve, reject) => {
		setTimeout(() => {
			resolve(delay);
		}, delay)
	})

}
wait(1000).then((delay) => console.log(`executed after ${delay} milliseconds`));


function execute() {
    console.log(1);
    setTimeout(function() { console.log(2); }, 1000);
    setTimeout(function() { console.log(3); }, 0);
    console.log(4);
    Promise.resolve().then(() => {
        console.log('a');
        Promise.resolve().then(() => console.log('b'));
    });
    console.log('c');
    Promise.resolve().then(() => console.log(5));
}
 1 4 c 
execute() // ?

x = 10;
let foo = {
x:20,
  
  bar(){
  return this.x
  },
  baz: ()=> this.x,
  
  dux(){
  let arrow = ()=>this.x;
    return arrow()
  }
}
console.log(foo.baz())


describe


let arr = [a, b, b, c, c, c];
let cal = function (array) {
	//Implementation
}

cal(arr) // output: 1a2b3c

[10:13 AM] Aniket P

    hoisting
    event loop
    microtaskqueue
    solid principle
    jot vs ait
    promise
    RXjs switchmap concatmap mergemap
    angular unit testing
    angular migration
    zonejs
    subject
    what is the role in the project as angular dev
    preloading strategy
    signal
    singleton component
    performance
    js vs webapi
    context
    arrow function
    how to pass data between two parallel component

  Jan 22nd at 3:03 PM
Project description
Lazy loading
Interceptor
AOT and JIT difference
angular version 13 and 14 differences
RXJS operator
Directives in angular
Pure pipe and impure pipe difference
explain the working of structural directives
diff between *ngIf and hidden
Dependency Injection
life cycle hook of componentNode js:
How to improves the performance of node js application.Task:
create one custome pipe that can transform indian Rupees to doller.

1. project
2. steps to migrate angular10 project to angular 15+
3. lazy loading , eager loading
4, promises vs observable
5. what is observable
6. directive
7. decorators and its types
8. data binding
9. communication between components
10. life cycle hooks
11. best practice for application
12. AOT compilation.
13. get and post method(Rest APIs)
14. routing.
15 unit testing.
15 how to create server using node js.
16 Diff between constructor and ngOnInit.task:

    create custom directive that highlight text or change the text color.
    arr=[{name:"alice",salary:20000},{name:"john",salary:30000},{}.......]

 sort the array based on salary.
  Feb 25th at 6:38 PM
KANINI 2nd Round Questions:
Interviewer: Mukesh Kumar

    HTML
    multipart form data
    formatting tags
    difference between link and anchor tag
    possible values for target attribute
    '_top' attribute
    tags used in table
    col-span and row-span
    media tags
    !DOCTYPE in html

    CSS
    how to apply css to html
    Client side libraries used

    JAVASCRIPT
    JS selectors
    Input --- AB BC CD  & output CD BC AB  without reverse method
    let arr1 = [1, 2, 3];   let arr2 = arr1;  arr2[0]=100;  console.log(arr1);
     '=' vs '==' vs '==='
    split function
    data types
    let vs var

    ANGULAR
    What's angular
    library vs framework
    Single page application
    mechanism behind SPA
    loadChildren
    write one lazy loaded route
    route guards based on condition
    authentication in angular
    pipes
    Write a pipe, such that if our value is 0 or null or undefined, it should return "-" else the value.
    isFinite()
    standard way to put loader for each api call
    can we use multiple interceptors
    switchMap vs mergeMap vs concapMap vs forkJoin
    library used to show pdf
    data transfer between two components

  Feb 22nd at 1:25 PM
Apart form the questions mentioned by
@Sanket Anandkar
, here are some more questions I was asked:

    Write how to define and use pipe.
    What is NgRx?
    What are Directives? List some.
    Why is trackby used while using *ngFor ?
    How do you maintain good coding standards?
    What is two-way data binding?
    How you manage pagination? Write a request having query params for pagination.
    What is guard? When to use one?
    Explain canActivate and canDeactivate.

(edited)
  Feb 22nd at 1:02 PM
Interviewer: DibyaSinghANGULAR -

    Explain any project and role, responsibility in it
    Challenges/difficulty in project
    Lifecycle hooks
    Ng Zone
    Optimisation of angular application
    AOT compilation
    Caching in angular app
    Use cases of  rxjs
    State management in rxjs
    Implement pagination and explain (payload to send and how to handle response)
    Pipe and decorators

NON-TECHNICAL:

    How your work day goes
    How do you handle team

  Feb 18th at 12:53 PM
ROUND 2 QUESTIONS
> (Html)

    Difference between strong & b tag.
    How to create a link ?
    All the values of "target" attribute in a tag.
    A link in i-frame should be opened in your current page. So, how to implement it ?
    Create a table with 3 rows & 3 columns.

> ( Javascript & Typescript )

    What are javascript selectors ?

> ( Angular )

    Currently on which version you are working ?
    Previous angular version in which you have worked.
    Difference between them.
    What is angular ?
    What is Single Page Application & how to achieve it in angular ?
    How do you define modules in angular ?
    What are pipes ?
    Write a pipe, such that if our value is 0 or null or undefined, it should return "-" else the value.
    Parent component to child component communication in angular & vice-versa.
    Life cycle hooks in angular.
    Which life-cycle hook will be triggered at first.
    Implement FormGroup.

  Feb 18th at 12:46 PM
ROUND 1 QUESTIONS
> ( Javascript & Typescript )

    What is meta-type and viewport in html ?
    What is javascript ?
    What is the difference between these two operators, "==" and "===" ?
    Difference between var and let keyword in javascript ?
    Output of var x = "3";  var y = 3; console.log(x + y) ?
    what is call, apply and bind in javascript ?
    What is JSON ?
    Write an object in javascript.
    What is the output of console.log(isNan("Hello World"));
    Difference between slice & splice array methods ?
    What is the map function of an array in javascript ?
    What is unary function in javascript ?
    What is typescript & how it works ?
    Why we use typescript ?
    Class in typescript.
    Difference between a class & an interface.
    What is the type never in typescript ?
    Difference between null & undefined in javascript.
    A scenario where interface is applicable.
    Abstract class.
    What are decorators ?
    What are anynomous functions in javascript ?

> ( Angular )

    What is Angular ?
    Working on which version currently ?
    Difference you saw between 18th & 14th version of angular ?
    What is life cycle in angular ?
    ngOnDestroy function in angular.
    ngOnInit function in angular ?
    ngAfterViewChecked function in angular.
    Components in angular.
    Difference between component and directive.
    Module in angular.
    Injectable decorator in angular.
    How do you communicate from parent to child component ?
    How do you communicate from child to parent component ?
    What is Pipe ? and implement it.
    What is Single Page Application ?
    How to implement SPA in angular ?
    What is child-routing ?
    What is dependency injection in angular ?
    ng build & ng serve commands.
    What is HttpClient in angular ?
    Methods in HttpClient service.
    Write a get method using HttpClient service.
    put & patch function difference.
    Interceptors in angular.

>  ( Node js )

    What is npm ?
    What is package.json ?
    What is package-lock.json ?
    Difference between Promise & Observable.
    Create an observable.

  May 10th, 2024 at 3:01 PM

1. What were the challenges you faced during the last 4 years
2. What is the type of null?
3. Predict the output:
    i. null == undefined
    ii. null === undefined
4. Tasks:
    i. Reverse string using recursive function
    ii. Extract keys from a nested object into an array without using any predefined function e.g. use of Object.keys() is prohibited
5. What is web worker?

  Nov 24th, 2023 at 3:28 PM

1. What is promise chanining?
2. What are guards?
3. In Promise and setTimeout which one will execute first?
4. HTTP interceptor
5. How to increase performance of app
6. How to calculate the bundle size of component?
7. What is microfrontend
8. code  let str = "Google" o/p :- {g:2, o:2, l:1, e:1}
9. When there is two tab and when we close second tab then how we can make event in first tab
10. What is difference between constructor and ngOnInit

(edited)
  Nov 8th, 2023 at 6:46 PM

1. content projection
2. pure and impure pipe
3. parent child communication
4. ngOnChanges
5. observable and promise
6. Set in js
7. Fibonacci series
8. map, filter, reduce
9. project description
10. get data from api and print on html
11. rxjs opertors(inculding tap)
12. waitAsync and WaitForAsync (unit testing)
13. ngViewInit
14. how to increase angular performance.
15. lazy route
16. how to write children route
17. resolve guard
18. describe all route guards
19. agile life cycle explain
20. sprint duration
21. code quality and code coverage
22. callback hell
23. viewChildren and viewChild
24. all life cylce hooks
25. virtual dom and shadow dom
26. directives 
27. how to created custome directive, which one you have created
28. TestBed and fixture(unit testing)
29. steps to create custome pipe
30. ngContent and ng-template
31. methods call on expect function (unit testing)

Angular Questions

Promise and observable
Loading and its type
JWT Interceptor
Diff betwn Bearer token and Access token
Reactive form and Directive form in angular
Life cycle methods
What is generated when we do ng new <project name>
Have you created custom directive
How can i call a button dynamically depending upon whether it has a id property of not
(if it have an id call save() if it do not call update())

Js Questions
every, sum and includes() in js
How will you show nested array values in html

Css Questions
What is mixing in saas
What is pseudo class and pseudo elements
Flex box and flex grid
Block and inline property
border-box and content-box

HTML 
Diff betwn html and html5

 (edited) 
  May 17th, 2023 at 10:35 AM
SECTION 1 (Solve any 2)
1. Given an integer array nums of unique elements, return all possible subsets. The solution
set must not contain duplicate subsets. Return the solution in any order.
Input: nums = [1,2,3]
Output: [[],[1],[2],[1,2],[3],[1,3],[2,3],[1,2,3]]
2. You are given a string s. You can convert s to a palindrome by adding characters in front
of it.
Return the shortest palindrome you can find by performing this transformation.
Input: s = "aacecaaa"
Output: "aaacecaaa"
3. Given a string s that contains parentheses and letters, remove the minimum number of
invalid parentheses to make the input string valid.
Return a list of unique strings that are valid with the minimum number of removals. You may
return the answer in any order.
Input: s = "()())()"
Output: [“(())()","()()()"]
4. Given an integer n, return the least number of perfect square numbers that sum to n.
Input: n = 13
Output: 2
Explanation: 13 = 4 + 9.SECTION 2 (Solve any 2)
1. Create a React Component which passes 2 props namely rows(number) and
columns(number) to a Child Component and Child Component renders a grid of div with
some background colour with the same rows and columns as received from props.
2. Given an array of objects as following:
const arr = [{id: 'AB',sum: 100,},
{id: 'BC',sum: 200,},
{id: 'CA',sum: 200,},
{id: 'BC',sum: 500,},
{id: 'AB',sum: 900,}];
Convert this array such that objects with same ids have one object and sum should be
equal to sum of all objects of same id
[{id: 'AB',sum: 1000,},
{id: 'BC',sum: 700,},
{id: 'CA',sum: 200,}];
3. Build a timer application using React JS. Users should be able to set a timer for a

specified amount of time and receive alerts when the timer expires.

  Apr 21st, 2023 at 4:19 PM

- difference let & var
- route and route guard
- differ and async
- input and output
- whats service
- whats hoisting
- whats ngrx 
- difference between ngrx and service
- why ngrx
- Explain eagerfetch and eagerLoad
- different ways of data communication between component
- how to implement pagination in backend
- promise vs observable 
- how to create promise, observable
- when to use promise and observable
- whats interceptor
- application of interceptor
- whats dynamic component
- How to create component and service
- component decorator properties
- whats dependency injection
- difference between service and ngrx, and their applications
- difference between Constructor and onInit
- whats Event Bubbling
- normal function vs arrow function 

(edited)
  Apr 21st, 2023 at 2:32 PM
event loop
callback
higher order function
 ts vs js
angular js vs angular
pipe and types of pipe
directive
routing
component to component commmunication
guard
websocket and poling
constructor vs onInit
 lifecycle hooks
 DI and services
 new feature of angular
 observalble and subject vs behavioual subject
Code ----
1.write a promise to check prime number?
2.async function foo() {​​ const result1 = await new Promise((resolve) =>   setTimeout(() => resolve("1")), ); const result2 = await new Promise((resolve) =>   setTimeout(() => resolve("2")), ); }​​ foo(); (edited)**********************************************
let a = { name: 'john' };
    let b = a;
    b.name = 'deo';
    console.log(a);
    console.log(b);
1. What is the output of code.
2. Why the value of a and b are same?
3. If we want to change the output then what changes need to do.
2. What is the output of the following code and why?
console.log(1);
setTimeout(() => console.log(2), 0);
console.log(3);
3. What is closure and its use and example.
4. What is the spread operator.
5. How can spread array and object.
6. Why we can use the spread operator.
7. What is authentication.
8. Which authentication is used to secure your APIs.
9. Why password is not added to the JWT token?
10. What are promises.
    1. If we want to call two APIs and send a response after completing both the APIs. How can we achieve it?
     2. If one of API call gets failed and we want to send both result to client then what method would be used?
11.  user collection:
[
  {name: "person a", skills: ['mysql', 'mongo', 'react'] },
  {name: "person b", skills: ['node', 'mongo', 'react'] },
...
]
1. Write a query to get all the user details with matching skills 'react' or 'mongo'
2. Write a query to get all the user details with matching skills 'react' and 'mongo'
1. Difference  between let, var, and const
2. Which promise method is used to execute all API calls parallel
3. What is the bind method and the difference between call and bind.
4. What will be the output of the following code and why?
function two() {
    console.log('myVar', myVar);
}
function one() {
    var myVar=2
    two()
}
var myVar=1
one()
5. What will be the output of the following code and why?
function printHello() {
    console.log('Hello')
}
printHello()
6. What will be the output of the following code and why?
printHello2()
var printHello2 = function() {
    console.log(' printHello2 Hello')
}
7. What is an event loop?
8. What will be the output of the following code and why?
console.log('Log first')
setTimeout(function(){console.log('Log second')},3000)
setTimeout(function(){console.log('Log third')},0)
console.log('Log fourth')
9. What is sharding in MongoDB?
10. Why MongoDB is better than SQL database?
11. What are the operators available in MongoDB?
12. What is unwind?
13. Find the second highest salary from the table
14. Find all the users having a role developer whose age is less than 27.
15.  What are authentication and authorization?
16.  Which authentication module is used in your project.
17.  Where you are storing the JWT token?
18. How do you manage expired JWT tokens?
19. After the token expires are you logging out the user from the app?
20. What is the other way to manage expired tokens so that users don't need to do logout and login again?Last round of interview Asked about the following topics
Past projects
API standards
Security standards
Scaling Application
Managing multi-role functionality
Code review standards*************************************************
what are the mongoose operators you have used
$skip
$size
2 what is closure?
3 how will you achieve api versioning?
4 functions used in unit testing
5 which Promise functions you have used like Promise.all()
6 advantages of nosql over sql
7 what is cluster in node js
[6:03 PM] output of following programsfor(var i=0;i<100;i++){
  setTimeout(()=>{console.log(i)},0)
}
let obj={foo:"bar"};
let obj1=obj;
obj1.foo=6;
console.log(obj1.foo)
console.log(obj.foo)return toppers data from students table using mongoose query
js is synchronous or asynchronous ?
does javascript use oop?
[6:10 PM] what is $lookup in aggregation?
[6:14 PM] output for following prog
let number=0
console.log(number++)
console.log(++number)
console.log(number)what is the difference between var and let?
what is the difference between arrow fun  and normal function?
  Apr 11th, 2023 at 2:15 PM

what are the mongoose operators you have used
$skip
$size
2 what is closure?
3 how will you achieve api versioning?
4 functions used in unit testing
5 which Promise functions you have used like Promise.all()
6 advantages of nosql over sql
7 what is cluster in node js
[6:03 PM] output of following programs
for(var i=0;i<100;i++){
  setTimeout(()=>{console.log(i)},0)
}
let obj={foo:"bar"};
let obj1=obj;
obj1.foo=6;
console.log(obj1.foo)
console.log(obj.foo)
return toppers data from students table using mongoose query
js is synchronous or asynchronous ?
does javascript use oop?
[6:10 PM] what is $lookup in aggregation?
[6:14 PM] output for following prog
let number=0
console.log(number++)
console.log(++number)
console.log(number)
what is the difference between var and let?
what is the difference between arrow fun  and normal function?

interview questions:
1.do you know what current angular vs angular js
2.did you create custom directive and tell its types also
3.what is pipe and its type and did you create any custom pipe
4.what is lazy loading and when it is load
5.how many ways we can communicate with the component
6.what is observable
7.difference between promise and observable
8.how can you improve the application performance
8.what is aot and jit
9.what is memory leaked problem
10.what is dependency injection
11.why we use promise
12.what is async and await
13.difference between typescript and javascript
14.code:var prom = new Promise((resolve,reject)=>{    setTimeout(()=>{        resolve(10);    },100*3);
})prom.then((data)=>{    console.log(data);
    return data*2;
}).then((data)=>{    console.log(data);
    return data;
})
guess the output??*after guessing can you apply async and await in below the code (edited) 
  Apr 5th, 2023 at 3:49 PM

1)what is the difference between hidden and ngIf
2)what is observable
3)what is pipe and tell its type
4)box model in css
5)difference between call and apply
6)what is directive and explain its type
7)explain server side rendering
8)shallow copy and deep copy
9)inline html in decorator
10)promise in js..
11)did you create custom pipe and which?
12)what is dependency injection..
13)how update request handle in node js and using which method
14)what is stream and how can you use in node js?

(edited)
  Mar 30th, 2023 at 1:54 PM
event loop
callback
higher order function
 ts vs js
angular js vs angular
pipe and types of pipe
directive
routing
component to component commmunication
guard
websocket and poling
constructor vs onInit
 lifecycle hooks
 DI and services
 new feature of angular
 observalble and subject vs behavioual subject
Code ----
1.write a promise to check prime number?
2.async function foo() {​​ const result1 = await new Promise((resolve) =>  setTimeout(() => resolve(“1”)), ); const result2 = await new Promise((resolve) =>  setTimeout(() => resolve(“2")), ); }​​ foo();
  Mar 28th, 2023 at 6:35 PM
// Online Javascript Editor for free
// Write, Edit and Run your Javascript code using JS Online Compiler
str="cviic";
console.log(str);
arr1=Array.from(str);
len=arr1.length;
str2=[];
var temp='';
var c=0;
res=null;
console.log(arr1);for(let i=0;i<arr1.length;i++){
    let a=arr1[i];
   delete arr1[i];
    console.log(arr1);
    if(arr1.includes(a)){
        console.log("a",a);
        console.log(arr1.indexOf(a));
        str2[i-c]=a;
        str2[len-1]=a;
        console.log(str2);
        arr1.splice(arr1.indexOf(a),1);
        len--;
    }
    else{
        console.log("s",a)
        if(c==0){
        temp=a;
        console.log("temp",temp);
        c++;}else{
            res=false;
        }
    }
    if(res){
    str2[Math.round(str2.length/2)-1]=temp;
    console.log(str2.join());
    }
    console.log("result",res);
}
  Mar 24th, 2023 at 8:36 PM
Interview Questions:

    What is Event bubbling.
    What is diff betn RouterModule.forRoot() & RouterModule.forChild().
    What is async and await
    What is AJAX in vanila js
    What is service workers
    What is flex-box
    How can we handle error in Observables?
    What is scan() and reduce() operators in Observable?
    What is diff betn Injectable and Injector?
    <div data-val="1" /> what is data-val in given html element.
    What is window.onload and document.ready
    Difference between arrow function and normal function.
    Js code

function sum(arr) {
   // write your code here

        var sum = 0;
        arr.forEach((element) => {

                num = "";
                for(i = 0; i < element.length; i++) {

                        if(parseInt(element.charAt(i))) {
                                num = num + element.charAt(i);
                        }

                }

                if(num !== "") {
                        sum = sum + parseInt(num);
                }

        })

        return sum;
}

console.log(sum(['123f','ab32d','dafa','43vf','d']))
console.log(sum(['d']))                                    // 0
console.log(sum(['13f','3d']))                             // 16
console.log(sum(['43vf','d']))

// Atleast try to write the code within 30 mins

(edited)
L-2 Interview Questions :

    Swap two elements in array
    Difference between call and apply
    Let vs const
    Whats Metadata in angular
    Whats Dynamic component
    How to use Dynamic component  in another component
    Share data from grandChildren to Parent component
    Why do used interceptor
    What are RXJS operators
    Map vs Tap operator
    Subject vs Behaviour subject
    Replay Subject vs Async SUbject
    Angular.json vs tsconfig.json file
    What's Hoisting
    What's SSR
    Unit Testing
    How to handle one API request into another API request
    How to use Preloading
    What's Resolve Guard
    What's ViewChild
    ng-template
    How to create custom package
    Third party libraries used
    Angular bootstraping flow
    Explain polymorphism and Inheritance in javasript

(edited)
  Feb 8th, 2023 at 10:19 AM
Bhanu's L1 interview Questions

    what is diff between var ,let and const
    what is call bind and apply
    what is diff between normal function and arrow function
    what is spread and rest operator
    what is hoisting
    what is lazyloading
    how can we create a component in cli without having the default imports in component
    what is viewchild
    how can we create a component in using cli
    what is two way data binding
    how can we change structure of ui dyanically
    what is present in Component decorator object
    what is present in module decorator object
    what is bootstraping
    how can we create a Pipe
    what is function used to create a Pipe
    what is pure and impure Pipe
    what are lifecycle hooks and tell execution order
    diff between obervable and promise
    diff between oberservable and subject
    what are diff types subjets in rxjs
    how can we communicate between components
    do you have idea about testing
    how can we write mock function for testing
    what is testbed
    how can we create a git branch using cli
    how can we delete a branch using cli 

  Feb 6th, 2023 at 10:27 AM
1.difference between html4 and html5
2.what is web workers
3.closure
4.difference between observable and subject
5.box design
6.how can you store your data temperory in browser
7.what is block and inline element
  Feb 6th, 2023 at 10:26 AM
My interview Questions:

    What is eagerly loading
    diff between DOM and BOM
    what is scss... what is used to convert it to css
    Why do you prefer angular in your project....what are the advantages of angular
    what will happen if i disabled javascript from angular project
    how to show array items present in parent comp in child comp html
    what is server side rendering
    difff between framework and library
    can we create custom packages & how
    why do we use typescript with angular....can't we use javascript
    why do we write code in ngOninit instead of constructor
    what is web workers
    what is impure pipes
    there are 2 modules and I run a command  (ng g c comp_name)  to generate comp outside that modules...where will that component gets declared

15. how to create only .ts file using CLI
  Feb 6th, 2023 at 10:36 AM

    Difference between subject and behaviour.
    All information about guards.
    Difference between Template drive and Reactive Form.
    difference between Html 5 and Html 4.
    View Child, View Children.
    Function to add new value in between of array.
    Talk more about your project, add all small details by which he will ask you questions related to it. 

(edited)
  Feb 7th, 2023 at 10:34 AM
L2 interview questions:

    diff between observable and promises
    closure
    web workers
    Universal angular
    Data binding
    angular zone
    swap two variables without using temp
    what is depedancy injection and services
    what is MVC
    diff between ecmascript and typescript


<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
#<b>NOTE:-Link which are not working on click , Just copy the link and paste it on the search bar</b><br>

#NOTE OF THE DAY:- <strong>Upload all the certificated and achievements on LINKEDIN It is require for resume upload 1 certificate daily</strong> <br>

<b>Do NOT try to undestand full concepts just complete it one by one </b>

1)Javascript concepts and all:-(Complete Cource)

1.1) Javascript Practice Projects:  (https://youtu.be/MIYQR-Ybrn4?si=i74K-EHlQ5WPhxWW) <br> Note:- Practice the project from this at least 2 in a week

2)CSS FLEXBOX:- (https://www.youtube.com/watch?v=tXIhdp5R7sc)     

2.1.0)CSS Grid   :- (https://www.youtube.com/watch?v=t6CBKf8K_Ac)
        
2.1.1)CSS Media Queries:- (https:www.youtube.com/watch?v=aook54SsfhY)

2.2) HTML & CSS Practice:- (https://www.youtube.com/watch?v=yU_JgeAIRko&list=PLjwm_8O3suyOwElnplQ3quKEHsOuHyP9R) <br> Note:- Practice the project from 2 Projectsper week
            
2.3)LocalStorage:(https:youtu.be/-ZRDZyUjEEI?si=HgcQ-ssG_L9OxPA7) <br>

2.4)Git & GitHub: [https://youtu.be/apGV9Kg7ics?si=TgzOd3aDdF0MB5qt] (https://youtu.be/apGV9Kg7ics?si=TgzOd3aDdF0MB5qt) (Note: Steps:- Undestand write or remeber following concepts 1)How to Ulpoad project to github 2)How to Clone Repository 3)How to merge project to the same repository 4)how to create pull request )<br> <b>Upload All the project on Github and send me the link </b>

3)Task-1):-Make TODO list project using HTML,CSS, and use localstorage to store data ,And use any ui template add functionalities like getting task from localstorage ,deleting task on button click and clearning all the localStorage Data.  (Push it on github and share me the link) 
<b>NOTE:-Refer this link to undestand:- [https://youtu.be/SeKQSQDUMDQ?si=cYcEHoICStXeiRDs](https://youtu.be/SeKQSQDUMDQ?si=cYcEHoICStXeiRDs)</b>

4)React.Js:-[https:youtu.be/hn80mWvP-9g?si=Y1QjSKC34d4xbA5u](https:youtu.be/hn80mWvP-9g?si=Y1QjSKC34d4xbA5u)

4.1)Do React Project 1):- [https://youtu.be/9wiWzu_tRB0?si=hlwsW6Y_6xErqyW7](https://youtu.be/9wiWzu_tRB0?si=hlwsW6Y_6xErqyW7)

4.2)Do React Project 2):- [https://youtu.be/jPo0mIcNZfM?si=S30UNRqmTBZ9151L](https://youtu.be/jPo0mIcNZfM?si=S30UNRqmTBZ9151L)

<b>NOTE:-Undestand and remember the syntax from NODE.JS try to remeber it like how to render, API request,Connecting with database</b><br>
5.0)MongoDB:  (https://youtu.be/c2M-rlkkT5o?si=UHUTt71iixkpN3Al) <br>
5)Node.Js-Express-MongoDB:[https:youtu.be/ZQsrcayZcSk?si=hTksZVXEYLjOLCdG](https:youtu.be/ZQsrcayZcSk?si=hTksZVXEYLjOLCdG)

5.1)Project 1):- (https://youtu.be/4WvX9dBjiJo?si=i8d0Wz6LqULaY7Ve)

5.2)Project 2): <br>


6)Angular Major Projects:-
1)E-Learning Angular:- https://youtu.be/WFTZF-jDwvQ?si=-Hw93Z2I0-MS2DLO
2)E-commerce Angular-Springboot:- https://youtu.be/ryQHyOzQ9fA?si=fjO3nGYmNyziesph
3)Food-app React: -
4)Hotel-Management React Springboot:- 


<b><em>1)#TASK OF THE DAY-15-11</em></b> :-<br> Bulid a web page like given below -1) RequireMents:-when i click on the submit button the message in the input box should be display on the screen <br>
![Screenshot from 2024-11-14 13-57-07](https://github.com/user-attachments/assets/75901013-b8b1-4fa5-a790-7f26d808646d)<br>

<b><em>2)#TASK OF THE DAY-14-11</em></b> :-<br> Bulid a web page like given below -1) RequireMents:- Its a registration form validation using javascript :- 1) When you click on the input box and do not type anyting in it then it should dsiply a message below the input box in screen that is (IT IS REQUIRED) dont use the required keyword in html do it using javascript<br>
![Screenshot from 2024-11-15 11-47-36](https://github.com/user-attachments/assets/e95a8001-bf97-41a7-9163-e6afe1c3c1f0)<br>

<b><em>3)#TASK OF THE DAY-16-11-24</em></b> :-<br>Guess The Number Game -1)RequireMents:- 1) You have to generate a randoem number between 1-100 store that number in variable 2)You have to create input box in html which will get number as input  3)if the number entered in input box is == to the random number generated then display You Won 4)If the number entered is greter than the random number display "Number is greter please enter smaller number" similar for the smaller number<br>
<b>DO NOT USE YOUTUBE TRY ON OWN</b><br>
![Screenshot from 2024-11-15 14-28-49](https://github.com/user-attachments/assets/80a704c5-fc3f-436c-be63-4b9852f30fe2)

<br>

<b><em>4)#TASK OF THE DAY-19-11-24</em></b> :-<br>React Concepts:-  1) crete a component and function inside component which will print some  text when Clicked   2)Watch UseState hook video  :- crete input and also add button when you clicked on it the text should be added in the
Usestate array wtach hot add seach it on google and print the array   3)Watch useEffect :-</b><br>
<br>


    
<b>Time Management:-Days require to complete it</b><br>
1)<b>[2, 2.1, 2.1.1, 1 practice Project] [1-day]</b><br>
2)<b>[2.3, 3 ,1 js practice Project] [1-day]</b><br>
3)<b>[4] [1 day (already done just revise all concepts its just a javascript)]</b><br>
4)<b>[4.1, 5, 5.1] [6-days]</b><br>
5)<b>Ready To Apply and Give Interviews</b><br>
6)<b>Start with the basics of DSA<b/><br>


