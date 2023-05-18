# Github_Actions_Assignments
<p align="center" width="100%">
    <img width="33%" src="https://raw.githubusercontent.com/github/explore/2c7e603b797535e5ad8b4beb575ab3b7354666e1/topics/actions/actions.png"> 
</p>

### Assignment 1
```python
1- Create a repository on GitHub with whatever name you may prefer.

2- Add a dummy postman collection to it.

3- The main objective would be to create a CI/CD pipeline that will run your postman collection using Newman, via GitHub Actions. If you want, you may use postman CLI if needed, it is up to you.

4- Once created we need to generate the report as well.

5- The generated report should be stored as an artifact.

6- The artifact should get expired after 30 days.

7- You will need to create a YAML file to configure the pipeline
```

### Solution of Assignment 1
```python
Click on Actions Tab

Then on left-side, click on workflow named as “Postman Collection”

Finally on “Run Workflow”
```

### Assignment 2
```python
1- Create a new branch named “feature/gitHubActionsAssignmentTwo”. Once created, along with the postman collection, you need to push the selenium project that you may have created in the earlier assignments.

2- Along with the postman collection execution on the pipeline, you are required to create another job in the same stage for the execution of selenium tests.

3- Configure your selenium project in such a way that the test should get executed in headless mode only.

4- For selenium execution, you should only be using the maven command only. Generate the report for the selenium execution and store it as an artifact as you did in the earlier assignment.
```

### Solution of Assignment 2
```python
Click on Actions Tab

Then on left-side, click on workflow named as “Postman And Selenium”

Finally on “Run Workflow”
```

### Assignment 3
```python
1- you are required to push a project whose build tool is sbt instead of maven.

2- The logic of the project is not required, it should be working with “sbt” command, even if it prints “Hello world” only. The only ask is that there should be some output when “sbt clean compile” or some other sbt command is used.

3- Once the above steps are done. You need to create a separate job for this and run your project in the pipeline. 

4- You may use the same GitHub repo that you used in the earlier assignment. However, create a separate branch for each of the GitHub assignments.
```

### Solution of Assignment 3
```python
Click on Actions Tab

Then on left-side, click on workflow named as “SBT Project”

Finally on “Run Workflow”
```

### Assignment 4
```python
1- For this assignment, leverage all the things that you have done so far in Github action assignments.

2- Now, you are required to run the job sequentially.

3- The order of execution should be
 a. Postman Collection Execution
 b. Selenium Test Execution
 c. Sbt Project execution.
```

### Solution of Assignment 4
```python
Click on Actions Tab

Then on left-side, click on workflow named as “Sequential Execution”

Finally on “Run Workflow”
```


