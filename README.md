<h1 align="center">Nikhil Awasthi</h1>
<p align="center"><b>Manual QA Tester</b> &nbsp;|&nbsp; Web, Android and REST API testing</p>
<p align="center">
  <img src="https://img.shields.io/badge/status-open_to_work-2ea043?style=for-the-badge" alt="open to work">
  <img src="https://img.shields.io/badge/joining-immediate-0969da?style=for-the-badge" alt="immediate joiner">
  <img src="https://img.shields.io/badge/location-Bengaluru_|_open_to_relocate-8250df?style=for-the-badge" alt="location">
</p>

```text
$ whoami
nikhil-awasthi  # Manual QA Tester, MCA (AI/ML), Amity University 2024

$ cat focus.txt
find the bug  ->  write steps a developer can reproduce  ->  verify the fix

$ ./status --now
[OK] seeking entry-level Manual QA / Software Test Engineer roles
[OK] Bengaluru | Noida | Pune | remote
```

<p>
  <a href="https://claude.ai/artifact/3vnEYonHwSUsV9CyNX4hQB"><img src="https://img.shields.io/badge/Portfolio-live-0f3a3c?style=for-the-badge" alt="portfolio"></a>
  <a href="https://www.linkedin.com/in/nikhil-awasthi-qa"><img src="https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"></a>
  <a href="https://drive.google.com/file/d/1GZAJ-NZ2PIYFE9P-7G4dudoEWF7Q-0j1/view?usp=sharing"><img src="https://img.shields.io/badge/Resume-PDF-d73a49?style=for-the-badge" alt="resume"></a>
  <a href="mailto:nikhillawasthi9@gmail.com"><img src="https://img.shields.io/badge/Email-write_to_me-ea4335?style=for-the-badge&logo=gmail&logoColor=white" alt="email"></a>
</p>

## Test run summary

```text
PROJECT                          TEST CASES    RESULT
-------------------------------  ------------  ------------------------------------
Amrutam (Web + Android)          44 executed   33 passed (75%), 11 defects found
OrangeHRM (full STLC artifacts)  47            plan, cases, RTM, defect reports
InterviewGod.ai                  21            13 defects logged
ReqRes REST API (Postman)        collection    requests and results
Selenium + Java (SauceDemo)      6 automated   written, not yet run
```

All projects are portfolio / assignment work, not paid production experience.

## A bug report I wrote

From my Amrutam assignment (Android app, Aug 2026). Full set in the [project folder](https://github.com/nikhil-awasthi-qa/qa-portfolio/tree/main/01-amrutam-web-android-testing).

```text
ID        : MOB-004
Title     : Profile update blocked by a required "State" field that is not on the screen
Severity  : Medium
Steps     : 1. Log in  2. Open Edit Profile  3. Change photo or details  4. Tap Update Profile
Expected  : profile updates, or a State field is shown so the user can fill it
Actual    : "State cannot be empty", but Edit Profile has no State field
Evidence  : screenshot (Fig. 9 in the assignment PDF)
```

<details>
<summary>See all 11 Amrutam bugs (8 Medium, 3 Low)</summary>

| ID | Where | Bug | Severity |
|----|-------|-----|----------|
| WEB-001 | Login / OTP | Resend OTP has no cooldown. Every tap sends a new OTP | Medium |
| WEB-005 | Edit Profile | First and last name accept numbers only | Medium |
| WEB-006 | Edit Profile | Names with only spaces are saved | Medium |
| MOB-001 | Search | No "no results" message for an invalid search | Medium |
| MOB-002 | Forum | A new comment shows 1 like before anyone likes it | Medium |
| MOB-003 | Notifications | Stays unread after opening the linked thought | Medium |
| MOB-004 | Edit Profile | "State cannot be empty" but there is no State field | Medium |
| MOB-005 | Checkout | Address form accepts PIN codes 000000 and 111111 | Medium |
| WEB-002 | Homepage | Grammar: "It's offers" | Low |
| WEB-003 | Homepage | Wording: "Register your self" | Low |
| WEB-004 | Homepage | Spelling: "untill" | Low |

</details>

## Projects

| Project | What I tested |
|---------|---------------|
| [Amrutam, Web + Android](https://github.com/nikhil-awasthi-qa/qa-portfolio/tree/main/01-amrutam-web-android-testing) | Exploratory, functional, negative, validation and UI/UX testing |
| [OrangeHRM](https://github.com/nikhil-awasthi-qa/qa-portfolio/tree/main/02-orangehrm-testing) | Test plan, test cases, requirements traceability matrix, defect reports |
| [InterviewGod.ai](https://github.com/nikhil-awasthi-qa/qa-portfolio/tree/main/03-interviewgod-ai-testing) | Functional testing of an AI interview product |
| [ReqRes REST API](https://github.com/nikhil-awasthi-qa/qa-portfolio/tree/main/04-api-testing-postman) | API testing with Postman |
| [QA Pilot](https://github.com/nikhil-awasthi-qa/qa-portfolio/tree/main/05-qa-pilot) | Small HTML tool on the Claude API: test case generator and bug hunter |
| [Selenium + Java](https://github.com/nikhil-awasthi-qa/qa-portfolio/tree/main/06-selenium-java-saucedemo) | JUnit 5 login tests on SauceDemo (Maven, Selenium 4) |

More in the [qa-portfolio repo](https://github.com/nikhil-awasthi-qa/qa-portfolio).

## Toolbox

![Postman](https://img.shields.io/badge/Postman-API_testing-FF6C37?style=for-the-badge&logo=postman&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-bug_tracking-0052CC?style=for-the-badge&logo=jira&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-queries-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![Selenium](https://img.shields.io/badge/Selenium-WebDriver-43B02A?style=for-the-badge&logo=selenium&logoColor=white) ![Java](https://img.shields.io/badge/Java-basics-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![Chrome](https://img.shields.io/badge/Chrome-DevTools-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)

**Testing:** manual testing, STLC, test case design, exploratory and regression testing, bug lifecycle and defect reporting  
**Automation:** completed Java + Selenium WebDriver training (Internshala, Oct 2026)
