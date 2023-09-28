# Security Vulnerabilities Reporting

## Learning goals

Thourgh this group work, you will learn how to read code, search and report security vulnarabilities and fix some of them. 🚀

## Backgroud 

You are given is a tiny program (see main.py) with-text based user inteface, which allows one the store basic information on students.  There are many serious  flaws and vulnarabilities in the program. You will practice finding, reporting and  and fixing them.  Please read more background information (including assessment criteria) in Canvas.

## Preparation steps

1. Creare a new repository for your team based on this templete called "faultystudentrecord".  See instructions at [GitHub Docs: Creating a repository from a template] (https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template).
2. Enable security  vulnerabilities reporting for your repository. See instructions at  [GitHub Docs: Configuring private vulnerability reporting for a repository] (https://docs.github.com/en/code-security/security-advisories/working-with-repository-security-advisories/configuring-private-vulnerability-reporting-for-a-repository)
3.  Create a branch (a copy) of the main code called "lessfaultystudentrecord". See instructions: [GitHub Docs: Creating and deleting branches in your repository] https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository

## Work steps

1.  Examine the main code (main.py) carefully and test different usage scenarous.  You can test code either manually (this is, by running the code and entering values by hand) or code automatic tests.  You can find examples of simple hardcoded unit tests in test.py (please note that harcoding unit tests is not good practice in most professional contexts, but works well for this exercise) and expand on those.
2.  For finding issues that are more difficult to spot, search online for information about  "SQL injection" and "Directory Traversal".  
3.  As soon as you find a security flaw, use GitHub to file a Security Vulnarability Report. Use this template as a basis of your vulnability report: [Vulnerability Report Templete by GitHub Security Lab] (https://github.com/github/securitylab/blob/main/docs/report-template.md).  The text-based report does not have mandatory fields, but you should provide as much information as possible.  It is particularly important to provide exact steps to reproduce the vulnerablity (in this case,  tested example code on how an attacker could use it).  There must be a seperate report for each vulnerability found.
4. If you still have time, try fixing some of the found security  vulnerabilities.  Do not change the code in the main repository directly, but make changes to the branch called "lessfaultystudentrecord" and then send a pull request to the main repository. If you edit the code with GitHub Copilot, it may also help you spot new security  flaws.  If so, please test them and report them in accordance with instructions in step 2.
5. If you still have time, you can show your skills by making other reasonable improvements to the code.
    
## Submit and present
1. Submit the link to your main repository in Canvas and make a 10-minute presentatation (see Canvas for more instructions).
