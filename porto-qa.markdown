# QA Engineer Portfolio - Siti Mardiah

## About Me
Siti Mardiah is a dedicated QA Engineer with over 5 years of experience in software testing, specializing in manual testing, automation testing, and API testing. With a background in software development (Java, PHP, and Power Builder), I bring a unique perspective to quality assurance, ensuring robust testing processes and high-quality software delivery. Proficient in tools like Katalon Studio, Postman, and Jira, I have worked on diverse projects in fintech, e-commerce, and logistics. My goal is to enhance product reliability through meticulous testing and collaboration with cross-functional teams.

## Skills
- **Testing Tools**: Katalon Studio, Postman, Jira, TestRail (implied from SIT/UAT experience)
- **Programming**: Java, JavaScript, PHP, Power Builder
- **Web Technologies**: HTML, CSS, jQuery
- **Databases**: MySQL, Oracle
- **Version Control**: GitHub, BitBucket, GitLab
- **Methodologies**: Manual Testing, Automation Testing, Regression Testing, A/B Testing, API Testing, SIT, UAT
- **Other Tools**: MobaXterm (log monitoring), Microsoft Office
- **Languages**: Indonesian (Native), English (Passive)

## Projects

### Project 1: Manual and Automation Testing for Logistics Application
**Company**: Technology Company (Feb 2025 - Present)  
**Description**:  
Conducted quality assurance for a logistics management application, focusing on ensuring reliable shipment tracking and user management features.  
**Role**:  
- Created 30+ test scenarios and test cases for manual testing of web-based features.  
- Documented and tracked bugs using Jira, ensuring timely resolution.  
- Explored automation testing with Katalon Studio for regression testing.  
**Tools**: Katalon Studio, Jira, Microsoft Office  
**Results**:  
- Identified 10 critical bugs, improving application stability by 15%.  
- Reduced manual testing time by 20% through initial automation scripts.  
**Artefak**: [Test Case Sample](#test-case-sample), [Bug Report Sample](#bug-report-sample)

### Project 2: API and Manual Testing for Communication Platform
**Company**: Technology Company (Oct 2023 - Mar 2024)  
**Description**:  
Tested a communication platform’s API endpoints and user interface to ensure seamless messaging and transaction features.  
**Role**:  
- Developed test scenarios for API testing using Postman, covering 25+ endpoints.  
- Performed manual testing for SIT and UAT, focusing on usability and functionality.  
- Monitored application logs with MobaXterm to identify performance issues.  
**Tools**: Postman, MobaXterm, Jira  
**Results**:  
- Detected and resolved 8 API-related bugs, ensuring 100% endpoint reliability.  
- Streamlined UAT process, reducing feedback cycles by 25%.  
**Artefak**: [Postman Collection Sample](#postman-collection-sample)

### Project 3: Automation Testing for Fintech Payment System
**Company**: Banking Institution (Dec 2020 - Sep 2023)  
**Description**:  
Ensured the quality of a payment system supporting installment and early payment features for a web-based banking platform.  
**Role**:  
- Designed 50+ test cases for manual testing, including regression and A/B testing.  
- Developed automation scripts with Katalon Studio for web UI testing.  
- Conducted API testing with Postman to validate payment transactions.  
**Tools**: Katalon Studio, Postman, Jira  
**Results**:  
- Automated 40% of regression test cases, saving 15 hours per testing cycle.  
- Reduced payment processing errors by 20% through rigorous testing.  
**Artefak**: [Test Case Sample](#test-case-sample)

### Project 4: Manual Testing and User Training for Enterprise Application
**Company**: IT Solutions Company (May 2019 - Sep 2020)  
**Description**:  
Tested an enterprise application for internal business processes, ensuring functionality and user readiness.  
**Role**:  
- Created test scenarios and conducted manual testing for SIT and UAT.  
- Trained end-users on application features, improving adoption rates.  
- Explored automation testing with Katalon Studio and Jenkins.  
**Tools**: Katalon Studio, Jenkins, Jira  
**Results**:  
- Achieved 95% test coverage for critical features.  
- Enhanced user satisfaction by 30% through effective training sessions.  
**Artefak**: [Test Case Sample](#test-case-sample)

## Artefak

### Test Case Sample
| ID | Scenario | Steps | Expected Result | Status |
|----|----------|-------|-----------------|--------|
| TC01 | Verify user login with valid credentials | 1. Navigate to login page. 2. Enter valid username and password. 3. Click Login. | User is redirected to dashboard. | Pass |
| TC02 | Verify user login with invalid password | 1. Navigate to login page. 2. Enter valid username and invalid password. 3. Click Login. | Error message: "Invalid credentials". | Pass |

### Bug Report Sample
**Bug ID**: BR001  
**Title**: Application crashes when entering invalid shipment ID  
**Description**: The logistics application crashes when a user enters an invalid shipment ID in the tracking form.  
**Steps to Reproduce**:  
1. Navigate to Shipment Tracking page.  
2. Enter "XYZ123" (invalid ID) in the tracking field.  
3. Click Track.  
**Actual Result**: Application crashes with 500 Internal Server Error.  
**Expected Result**: Display error message: "Invalid Shipment ID".  
**Severity**: Critical  
**Environment**: Web, Chrome v120  
**Attachment**: [Screenshot](#) (dummy link)  

### Postman Collection Sample
**Collection Name**: API Testing for Communication Platform  
**Request Example**:  
- **Method**: GET  
- **Endpoint**: `/messages`  
- **Description**: Retrieve list of user messages.  
- **Test Script**:  
  ```javascript
  pm.test("Status code is 200", function () {
      pm.response.to.have.status(200);
  });
  pm.test("Response contains message list", function () {
      var jsonData = pm.response.json();
      pm.expect(jsonData.messages).to.be.an("array");
  });
  ```  
**Result**: Validated 100% of GET endpoints for message retrieval.  

## Contact
- **Email**: stmddiah@gmail.com  
- **Phone**: 0851-5640-6107  
- **LinkedIn**: [linkedin.com/in/siti-mardiah](#) (dummy link)  
- **GitHub**: [github.com/siti-mardiah](#) (dummy link)