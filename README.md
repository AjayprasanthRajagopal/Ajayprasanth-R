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
import static io.restassured.matcher.RestAssuredMatchers.*;
import static org.hamcrest.Matchers.*;
import static io.restassured.RestAssured.*;

```

## Use log().all() for consoling in output
