# Rest_Assured_API_Testing

### An [API](http://dmoney.professionaltrainingbd.com) is tested by using the REST Assured framework integrated with TestNG as a testing framework for validation purposes. Here, the status codes, validation messages, and the flow of API are tested using a Dmoney API where there is login, searching, creating, updating, and deleting features.
## Here the following tasks are done:
- Login feature tested using proper validation, negative test cases added for email and password.
- Can get user list by user authorization token, both positive and negative test cases are added for it.
- Can search any user by proper id.
- Can create a user by random name, email, password, nid, and phone number using proper validation and secret key token.
- Can update any user by the corresponding id, validated using PUT and PATCH methods.
- Can delete any user by the id, negative test cases are added for it.
- The variables are set and used from the config.properties file.


### Technology: </br>
- Tool: REST Assured
- IDE: Intellij
- Build tool: Gradle
- Language: Java
- Test_Runner: TestNG

### Prerequisites</br>
- Install jdk 8 
- Configure JAVA_HOME and GRADLE_HOME
- Download Allure 2.18.1 and configure the environment path
- Stable internet connection


### Project Run
- Clone the repo.
- Open cmd in the root folder.
#### Run the Automation Script by the following command:
 gradle clean test 
 ```
- The following report is generated:


![Sample report](https://github.com/Tonmoy61/Rest_Assured_API_Testing/blob/master/report/report.png)

