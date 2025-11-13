# Google Summer of Code 2024 with CloudCV

## Introduction
I am **Harshit Jain**, an undergraduate student from India. I got accepted for **Google Summer of Code 2024** with **CloudCV** for the project **"Enhanced Exception Handling, Testing, Documentation, and User-Friendliness for EvalAI."**

The past three months have taught me many things that helped me not only as a developer but also as an individual. It was a fun and exciting experience for me. Every day, I learned something new, stretched my mind, and grew. It also gave me the opportunity to work on a project that has a significant impact on users.

---

## About CloudCV
**CloudCV** is an open-source cloud platform with the aim of making AI research more reproducible. It actively works on building tools that enable researchers to build, compare, and share state-of-the-art algorithms.

**EvalAI**, a project of CloudCV, is an open-source platform for evaluating and comparing Machine Learning (ML) and Artificial Intelligence (AI) algorithms at scale.

### Features offered:
- Custom evaluation protocols and phases  
- Remote evaluation  
- CLI support  
- Portability  
- Evaluation inside custom environments  

---

## Brief Description of the Project
This GSoC 2024 project aims to **enhance EvalAI's core functionality and user experience**.

### Main Goals
- **Improve testing:** Increase test coverage for critical components and frequently used APIs.  
- **Refine error handling:** Improve exception handling and error messages throughout the system.  
- **Boost user-friendliness:** Implement UI improvements based on user feedback to make EvalAI more robust, accessible, and efficient.  
- **Enhance documentation:** Update API documentation, create AWS setup guides, and develop a comprehensive FAQ.

---

## Work

The work done during this period can be broadly divided into four verticals:

### 1. Tests and Coverage Improvements

#### Django Code Coverage
Improved the code coverage of the EvalAI codebase. The main apps that significantly increased coverage are:
- **Challenges App**
- **Workers Script App**
- **Jobs App**

#### List of PRs by Category:
- Challenges App Tests (#4406)  
- Worker Scripts Tests (#4411)  
- Accounts App Tests (#4402)  
- Jobs Tests (#4404)  
- Base App Tests (#4403)  
- Tests for Other Files (#4405)

#### Angular Code Coverage
Improved code coverage in Angular. The main files improved:
- Test for `PermissionCtrl`
- Add tests for `ChallengeListCtrl.test.js`
- Update Profile Controller Tests
- Auth test coverage checks

---

### 2. Postman Automation Testing
Developed **automation API test suites** for EvalAI.

---

### 3. Enhancement in Error Handling

- **Fix #4089:** Add warning for submission deregistration  
- **Fix #3935:** Warn users when tokens have expired  
- **Fix #4324:** Add verbose output for pip install errors  
- **Fix #4326:** Improved general error handling  
- **Fix #4275:** Add Incognito and Cache Warning  
- **Fix #4229:** Verification of Challenge Phase with Challenge PK  
- Add error handling for AWS credentials  
- **Fix #4347:** Flag for submissions (UI & CLI)  
- Add dummy tags and domain values  

---

### 4. Features Added
1. **Account Reactivation:** Feature to reactivate deactivated accounts  
2. **Challenge Tabs:** Added tabs for challenges on the front-end  
3. **Search Enhancements:** Improved search functionality  
4. **Fix #4299:** Added logout button for mobile and tablet viewports  
5. **Docker Submission Fix:** Enabled Docker-based challenge push from CLI  
6. **Fix #4352:** Add auto-update scripts for specific submission metrics by PK  

---

### Bug Fixes
1. **Swagger API Fix**  
2. **Fix #4274:** Add or delete challenge phase/phase splits  
3. Fix modify leaderboard and dataset splits  
4. **Fix #4294:** Scrollable container fix  
5. And many more minor bug fixes  

---

## Issues Worked On
- [Bug]: Editing of submission meta attributes not allowed if not provided during submission  
- [Enhancement]: Accepting incorrect file formats instead of rejecting them  
- Improved error handling with specific messages  
- [Enhancement][Frontend]: Logout button for mobile compatibility  
- [Enhancement][Frontend]: Improved accessibility of “Show Analysis” button in Challenge Analytics  

---

## Future Plans
- Enhanced Angular unit tests are under review and feedback from mentors is being incorporated.  
- Postman automation test suite completed and ready for deployment.  
- Post-GSoC: integration of both Angular test improvements and Postman suite into the CI/CD pipeline.

---

## Conclusion
I want to thank all the Org Admins and Mentors who helped me during this period. They were extremely supportive and encouraging. Any doubt—no matter how small—was resolved quickly, and PRs were reviewed on time. Regular meetings helped us interact, receive feedback, and stay aligned with the project timeline.

### Acknowledgements
- **Rishabh Jain** – Org Admin  
- **Gunjan Chhablani** – Org Admin  
- **Gautam Jajoo** – Org Admin  
- **Suryansh Pathak** – Mentor  

Finally, I would like to thank **Google’s Open Source Community** for introducing such a program and providing this opportunity to contribute and grow.

**Thank You!**
