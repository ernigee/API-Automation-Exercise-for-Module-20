This is just a working log I wrote to remind myself how I did it.
just like a digital diary.

## 16 September 2024
1. Created project, named it `Final Project`
2. added dependencies in `build.gradle`
   ```bash
     testImplementation 'org.junit.vintage:junit-vintage-engine:5.11.0'

    implementation group: 'io.cucumber', name: 'cucumber-java', version: '7.18.1'
    testImplementation group: 'io.cucumber', name: 'cucumber-junit', version: '7.18.1'

3. added package under `src/test/java`, name it `feature`, then created `api.feature` file. it will activate or connect or whatever the cucumber.
checked the gherkin plugins and install the cucumber on ide because apparently it won't show the cucumber logo on the file name.
4. Worked on `api.feature` file, wrote a scenario `Test get list data normal`
point the yellow underline and click `create step definition`. but before that, create new package under java folder and named it `stepDefinition`.
   ```bash
   Feature: Test Automation Rest API
   Scenario: Test get list data normal
   Given prepare URL valid for get list data

5. point the yellow underline and clicked `create step definition`, created a new file and named it `ApiStep.java`.
it automatically wrote a methode for 'ApiStep'. made a `println` statement to test it but failed.
Now I'm waiting for mentor's feedback before continue.

   ```bash
   
    public class ApiStep {
    @Given("prepare URL valid for get list data")
    public void prepareURLValidForGetListData() {
    System.out.println("Henlo Step");
    }}


## 17 September 2024
1.


 
