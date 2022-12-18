# CS-360
-Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

This application had five goals in mind during development:
1.Provide a platform to store data
2.Allow users to add data
3.Allow users to delete data
4.Allow users to update data
5.Secure all of this behing a user account and password
All of the users needs were taken into account when brainstorming these goals.

-What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
This application has four screens that are vital for its functionality. 
Page 1: Register/Sign In
This page allows the user to either register a new account or continue to the sign in page by clicking sign in. Should the user decide to create an account they can enter their credentials in the boxes. If the account already exists the user must change the credentials.
Page 2: Returning User Sign In
This page is for returning users. The user can sign in using their username and password, and if it is incorrect they can retry. If the user does not have an account they can click the home button to return to the home page and create an account. All user account information is stored in an SQLLITE database.
Page 3: SMS Permissions
This page prompts the user to allow or deny SMS permissions for TrackThat. Should the user allow permission they can click the proceed button and access the inventory with SMS permissions active. If the user denies permissions they can still click the proceed button and access the inventory but without SMS services. This permission is only requested on each device one time no matter what account is used. The user will always be brought to the SMS permissions page and if they have already accepted or denied permissions they can proceed by clicking the “proceed” button.
Page 4: Inventory Screen
This page partially works. I had difficulty setting up the database for the inventory because of the amount of data that needed to be stored. I had 26 edit text boxes for the data and I could not figure out how to add or remove more with a button.
However, the user can insert data into the text boxes by clicking the text boxes but the data will not be saved upon closing the application.

-How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
I approached this as I do all other kinds of coding and application design, with an open mind. I always like to think that parts and features of my application are subject to change just in case I find a more efficent way to achieve something.

-How did you test to ensure your code was functional? Why is this process important and what did it reveal?
The only type of test I ran was a compilation test by launching the virtial phone to test my application in real time. If the application didn't launch or crashed after certain actions that's how I knew what to change or fix. Without this process I would not have completed this project or any other project for that matter. Testing is essential. 

-Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
All around designing this application was a learning curve. I figured this work would be split between multiple people for efficenty and doing it alone has give me a new found respect for app developers. Designing the UI was a challange because I'm not particuraly artistic, but I kepy it simplistic and easy to read.

-In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
The design aspect was the easiest part because of my past knowledge working with HTML designing websites. I may not make the best looking UI but it functions as it should. This is where a more artistic person would step in.
