# FirebaseProject
Made to enhance my skills on firebase authentications and databases.  
It consists an info activity of user with profile pic, user email, name & phone no.  
App starts with a signin page if the user not logged-in otherwise starts with the user info page.  
Any new user need to signup first from a valid email address and by selecting a strong password for the account.

Firebase Auth - used for user authentication, account creation/deletion  
Real-time database - used for storing/retrieving user name, email & phone no.  
Firebase cloud storage - used for storing user's profile picture  
Firestore - used for storing profile pic URIs of users for retrieving image data.

![11](https://user-images.githubusercontent.com/123496162/218548031-a4f5b046-67ce-4d73-8291-9dad72d5247f.jpg)
Signin with email & password. A password reset email will be sent in case the user forgot the password.

![22](https://user-images.githubusercontent.com/123496162/218548616-2c5e695a-62aa-4922-a07b-8b726c9a2172.jpg)
Signup activity for creating a user with email and password. Specified email address need to be verified by the firebase's verification link email.
Without verification no user can enter app's main interface. In case of exiting app without verification, the account created will be deleted.

![3](https://user-images.githubusercontent.com/123496162/218547549-4311517a-958f-482f-8684-fba173c0f877.png)
![4](https://user-images.githubusercontent.com/123496162/218549797-854853c7-8707-4519-ab36-3319ca3d0185.jpg)
Main UI of the application in a scroll view. Profile pic get visible if the data for the user exits in the firestore.
All data need to filled by the user to see more features. Data can be filled automatically from the real-time database once filled by the user.
After data updation, data deletion option and other users option get visible. The data get saved in the database with UID.

![5](https://user-images.githubusercontent.com/123496162/218550203-c071d49a-2687-4f99-9e60-9aa87600bf5f.jpg)
Any user can view any other user's profile picture, name & email by clicking on an item of the visible list view.

![6](https://user-images.githubusercontent.com/123496162/218551898-9ea7e866-1acf-4f72-ac3f-4eae49255053.jpg)
![7](https://user-images.githubusercontent.com/123496162/218552041-4fce7438-f27a-45d0-a7ec-ffabe3f30a5d.jpg)
password changing activity, initiated by re-authenticating the user with his/her old password.

![8](https://user-images.githubusercontent.com/123496162/218552412-57e18529-d505-42e5-b832-4ffdab1e812a.jpg)
![9](https://user-images.githubusercontent.com/123496162/218553680-c919aa7b-a3f5-4bb6-89b6-694d5c408ff2.jpg)
This dialog will appear after clicking on profile pic. User can delte/change the current picture from here. This will get updated on cloud storage.


made using java, XML, Android studio, Firebase & some supportive libraries.
