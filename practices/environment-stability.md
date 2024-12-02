# Flow Through Environments: Dev, Staging, and Production  

This document outlines the flow of code through the development environments: dev, staging, and production. It also describes the automated tests and validations that must be performed at each stage to ensure code quality, security, and reliability.

## 1. Running Locally  
When running the code locally, developers must validate it with the following:  
- **Linting**: Ensures code adheres to defined best practices and style guidelines.  
- **Code Coverage**: Verifies unit tests cover the intended portions of the codebase.  

### Recommended Practices:  
- Include linting and coverage checks in the build script.  
- Enforce these checks via Git hooks, making them mandatory before code commits.  


## 2. Pull Request to Feature Branch  
When a Pull Request (PR) is opened to merge changes into a feature branch, the following validations are executed:  
- **Best Practices and Unit Test Validation**:  
  - Tools such as **SonarQube** or **Codacy** are used to ensure adherence to coding standards and robust unit test coverage.  
- **Security Validation**:  
  - Dependency vulnerability management tools like **Snyk** check for known vulnerabilities in the codebase.  


## 3. Development Branch Update  
Once the feature branch is merged into the **development branch**, the code is:  
- **Deployed to the Dev Environment**:  
  - This environment is used for initial integration and validation of the code changes.



## 4. Pull Request from Development Branch to Main Branch  
When a PR is opened from the **development branch** to the **main branch**, the following tests and validations are triggered:  
- **Integrated Tests**: Ensure the system works cohesively.  
- **Performance Validation**: Verify the system meets performance requirements under typical and peak conditions.  
- **Static Application Security Testing (SAST)**: Detect security vulnerabilities in the source code.  
- **Dynamic Application Security Testing (DAST)**: Identify vulnerabilities in the running application.  



## 5. Main Branch Update  
Once the development branch is merged into the **main branch**, the following occurs:  
- **Deployed to Staging Environment**:  
  - Code is deployed in a staging environment that closely mirrors production.  
- **End-to-End Validation**: Comprehensive testing of the entire system to ensure all components work together seamlessly.  



## Summary of Automated Tests and Validations  

| Stage                        | Validations                                                                 |
|------------------------------|-----------------------------------------------------------------------------|
| Running Locally              | Linting, Unit Test Coverage                                                |
| PR to Feature Branch         | Best Practices (SonarQube/Codacy), Dependency Security (Snyk)              |
| Development Branch Update    | Deployment to Dev Environment                                              |
| PR from Dev to Main Branch   | Integrated Tests, Performance Validation, SAST, DAST                      |
| Main Branch Update           | Deployment to Staging, End-to-End Validation                              |

By following this structured flow and ensuring comprehensive testing, teams can maintain high code quality and reduce the risk of issues in production.
