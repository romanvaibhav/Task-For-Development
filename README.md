# Task-For-Development

#<b>NOTE:-Link which are not working on click , Just copy the link and paste it on the search bar</b><br>

#NOTE OF THE DAY:- <strong>Upload all the certificated and achievements on LINKEDIN It is require for resume upload 1 certificate daily</strong> <br>

<b>Do NOT try to undestand full concepts just complete it one by one </b>

1)Javascript concepts and all:-(Complete Cource)

1.1) Javascript Practice Projects:  (https://youtu.be/MIYQR-Ybrn4?si=i74K-EHlQ5WPhxWW) <br> Note:- Practice the project from this at least 2 in a week

2)CSS FLEXBOX:- (https://www.youtube.com/watch?v=tXIhdp5R7sc)     

2.1.0)CSS Grid   :- (https://www.youtube.com/watch?v=t6CBKf8K_Ac)
        
2.1.1)CSS Media Queries:- (https:www.youtube.com/watch?v=aook54SsfhY)

2.2) HTML & CSS Practice:- (https://www.youtube.com/watch?v=yU_JgeAIRko&list=PLjwm_8O3suyOwElnplQ3quKEHsOuHyP9R) <br> Note:- Practice the project from 2 Projectsper week
            
2.3)LocalStorage: [https:youtu.be/-ZRDZyUjEEI?si=HgcQ-ssG_L9OxPA7](https:youtu.be/-ZRDZyUjEEI?si=HgcQ-ssG_L9OxPA7)

2.4)Git & GitHub: [https://youtu.be/apGV9Kg7ics?si=TgzOd3aDdF0MB5qt] (https://youtu.be/apGV9Kg7ics?si=TgzOd3aDdF0MB5qt) (Note: Steps:- Undestand write or remeber following concepts 1)How to Ulpoad project to github 2)How to Clone Repository 3)How to merge project to the same repository 4)how to create pull request )<br> <b>Upload All the project on Github and send me the link </b>

3)Task-1):-Make TODO list project using HTML,CSS, and use localstorage to store data ,And use any ui template add functionalities like getting task from localstorage ,deleting task on button click and clearning all the localStorage Data.  (Push it on github and share me the link) 
<b>NOTE:-Refer this link to undestand:- [https://youtu.be/SeKQSQDUMDQ?si=cYcEHoICStXeiRDs](https://youtu.be/SeKQSQDUMDQ?si=cYcEHoICStXeiRDs)</b>

4)React.Js:-[https:youtu.be/hn80mWvP-9g?si=Y1QjSKC34d4xbA5u](https:youtu.be/hn80mWvP-9g?si=Y1QjSKC34d4xbA5u)

4.1)Do React Project 1):- [https://youtu.be/9wiWzu_tRB0?si=hlwsW6Y_6xErqyW7](https://youtu.be/9wiWzu_tRB0?si=hlwsW6Y_6xErqyW7)

4.2)Do React Project 2):- [https://youtu.be/jPo0mIcNZfM?si=S30UNRqmTBZ9151L](https://youtu.be/jPo0mIcNZfM?si=S30UNRqmTBZ9151L)

<b>NOTE:-Undestand and remember the syntax from NODE.JS try to remeber it like how to render, API request,Connecting with database</b><br>
5)Node.Js-Express-MongoDB:[https:youtu.be/ZQsrcayZcSk?si=hTksZVXEYLjOLCdG](https:youtu.be/ZQsrcayZcSk?si=hTksZVXEYLjOLCdG)

5.1)Project 1):- (https://youtu.be/4WvX9dBjiJo?si=i8d0Wz6LqULaY7Ve)

5.2)Project 2): <br>


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


<b>Here is the code</b>

<form class="formTag" validate [formGroup]="loginPage"  autocomplete="on">
    <div class="main">
        <div class="container">

        <div class="heading">
            <h2>Login to your account</h2>
        </div>
        <div class="email">
            <label for="email" placeholer="Enter your email">Email</label><br>
            <input autocomplete="email" name="email" formControlName="email" type="email" required>
        </div>
        <div class="Dcolor">
            @if(loginPage.controls['email'].touched && loginPage.controls['email'].errors?.['required']){
                <span>This is required</span>
            }
        </div>
        <div class="password">
            <label for="password">Password</label><br>
            <input autocomplete="current-password" name="password" formControlName="password" type="password" required minlength="3">
        </div>
        <div class="Dcolor">
            @if(loginPage.controls['password'].touched && loginPage.controls['password'].errors?.['required']){
                <span>This is required</span>
            }
            @else if(loginPage.controls['password'].errors?.['minlength']){
                <span>Min 6 chared required</span>
            }
        </div>
        <div>
            <a (click)="OpenForgetPass()">Forget Password</a>
        </div>

        <div class="btn">
            <button class="login-btn" (click)="login()">Login</button>
        </div>
        <div class="registration">
            <a class="regi"  (click)="regi()">Register</a>
        </div>
        </div>
        <div id="google-signin-button"></div>
    </div>
</form>

<div *ngIf="isOpenForgtePass">
    <label for="email">Enter Email:</label>
    <input [(ngModel)]="ForgetEmail" type="text" >
    <button (click)="handleForgetPassword()">Submit</button>
</div>



<b>End</b>



    
<b>Time Management:-Days require to complete it</b><br>
1)<b>[2, 2.1, 2.1.1, 1 practice Project] [1-day]</b><br>
2)<b>[2.3, 3 ,1 js practice Project] [1-day]</b><br>
3)<b>[4] [1 day (already done just revise all concepts its just a javascript)]</b><br>
4)<b>[4.1, 5, 5.1] [6-days]</b><br>
5)<b>Ready To Apply and Give Interviews</b><br>
6)<b>Start with the basics of DSA<b/><br>


