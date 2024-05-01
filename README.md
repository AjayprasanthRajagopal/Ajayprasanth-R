# Readme Rest Assured

#### Pre Requisites

- TestNG
- RestAssured
- Eclipse IDE

*1. Install Testng compatible version.*
*2. Check for JRE Execution version*
*3. Import required statements*

` import org.testng.annotations.Test;`
`import io.restassured.RestAssured;`
`import io.restassured.response.Response;`


## Use Static Imports to minimize Declaration of Classes

```
import static io.restassured.RestAssured.*;
import static org.hamcrest.Matchers.*;
import org.json.simple.JSONObject;
import org.testng.annotations.Test;
import io.restassured.http.ContentType;

```

## Use log().all() for consoling in output

### use 

- header
- contentType
- accept 

to Accept the request in JSON format.


## To create dummmy api using json-server dependency using NPM


`npm install -g json-server`
`json-server --version`

### Create a db.json file and start the server by using 

`json-server db.json`


Install few other dependencies for JSON Validation

#####  json-simple
##### json-schema-validator

Refer `https://www.youtube.com/watch?v=xIidl6Iua0o&list=PLUDwpEzHYYLvLZX_QEGTNolPvNADXid0I&index=2 ` for Sending data in JSON

we can pass the data using -> POJO (getter , setter) , external JSON File, HashMap 
