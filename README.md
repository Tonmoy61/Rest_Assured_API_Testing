<h1 align="center">Rest_Assured_API_Testing</h1>

### An [API](http://dmoney.professionaltrainingbd.com) is tested by using REST Assured framework integrated with TestNG as testing framework for validation purpose. Here, the status codes, validation messages and the flow of API is tested using a Dmoney API where there is login, searching, creating, updating and deleting features.
Here the following tasks are done:
- [x] Login feature tested using proper valiadtion,negative test cases added for email and password.
- [x] Can get user list by user authorization token, both positive and negative test cases are added for it.
- [x] Can search any user by proper id.
- [x] Can create a user by random name,email,password,nid and phone number using proper validation and secret key token.
- [x] Can update any user by the corresponding id, validated using PUT and PATCH method.
- [x] Can delete any user by the id, negative test cases are added for it.
- [x] The variables are set and used from config.properties file.
## :pushpin: Technology: </br>
- [x] Tool: REST Assured
- [x] IDE: Intellij
- [x] Build tool: Gradle
- [x] Language: Java
- [x] Test_Runner: TestNG

## :pushpin: Prerequisites</br>
- [x] Install jdk 8 
- [x] Configure JAVA_HOME and GRADLE_HOME
- [x] Download Allure 2.18.1 and configure environment path
- [x] Stable internet connection

## :pushpin: Project Run
- [x] Clone the repo.
- [x] Open cmd in the root folder.
#### Run the Automation Script by the following command:
 ```
 gradle clean test 
 ```
:small_orange_diamond: The following report is generated:


![Sample report](https://github.com/Tonmoy61/Rest_Assured_API_Testing/blob/master/report/report.png)



