# Nikhil Awasthi

Manual QA tester from Lucknow. I like finding the bug that a happy-path click-through misses, and writing it up so a developer can reproduce it on the first try.

MCA (AI/ML), Amity University 2024. Fresher, can join immediately. Open to Bengaluru, Noida, Pune, Lucknow or remote.

[Portfolio](https://claude.ai/artifact/3vnEYonHwSUsV9CyNX4hQB) · [LinkedIn](https://www.linkedin.com/in/nikhil-awasthi-qa) · [Resume (PDF)](https://drive.google.com/file/d/1GZAJ-NZ2PIYFE9P-7G4dudoEWF7Q-0j1/view?usp=sharing) · [Email](mailto:nikhillawasthi9@gmail.com)

---

## A bug report I wrote

From my Amrutam assignment (Ayurveda platform, Android app, Aug 2026). The full set is in the [project folder](https://github.com/nikhil-awasthi-qa/qa-portfolio/tree/main/01-amrutam-web-android-testing).

> **MOB-004: Profile update is blocked by a required "State" field that is not on the screen**
>
> **Severity:** Medium
>
> **Steps:** 1. Log in. 2. Open Edit Profile. 3. Change the photo or any detail. 4. Tap Update Profile.
>
> **Expected:** the profile updates, or a State field is shown so the user can fill it.
>
> **Actual:** update fails with "State cannot be empty", but Edit Profile has no State field. The user has no way to fix it.

What I like about this one: nothing crashed, the app just quietly left the user stuck. Happy-path testing would not have caught it.

## What I found on Amrutam

44 test cases run on web and Android, 33 passed, 11 defects logged.

```text
Medium  ████████  8
Low     ███       3
```

<details>
<summary>See all 11 bugs</summary>

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

## Other work

All of this is practice and assignment work, not paid production experience.

| Project | What I did |
|---------|------------|
| [OrangeHRM](https://github.com/nikhil-awasthi-qa/qa-portfolio/tree/main/02-orangehrm-testing) | 47 test cases with a test plan, requirements traceability matrix and defect reports |
| [InterviewGod.ai](https://github.com/nikhil-awasthi-qa/qa-portfolio/tree/main/03-interviewgod-ai-testing) | 21 test cases, 13 defects logged |
| [ReqRes REST API](https://github.com/nikhil-awasthi-qa/qa-portfolio/tree/main/04-api-testing-postman) | API testing with Postman |
| [QA Pilot](https://github.com/nikhil-awasthi-qa/qa-portfolio/tree/main/05-qa-pilot) | A small HTML tool I built on the Claude API to generate test cases |

## Learning right now

Selenium and Java. I finished the Internshala training in October 2026 and wrote [6 login tests for SauceDemo](https://github.com/nikhil-awasthi-qa/qa-portfolio/tree/main/06-selenium-java-saucedemo). They are written but I have not run them yet, and the folder says so.

Everyday tools: Postman, Jira, SQL, Chrome DevTools.
