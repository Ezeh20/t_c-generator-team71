# Project Team 71
Codebase for proj-t_c-generator - Team 71
<br>

# Termbuddy - Terms and Conditions and Privacy Policy Generator.

## Table of Content

* [Overview](#overview)
* [Project Design](#project-design)
* [Directory Structure](#directory-structure)
* [Project Status](#project-status)
* [Tools Used](#tools-used)
* [Client](#client)
* [Features and Accessibilities](#features-and-accessibilities)
* [Collaboration](#collaboration)

# Overview
> The purpose of this project is to build a web application that helps users to generate their Terms and Conditions and Privacy Policy agreements for their company or website. 

### Project Design
> <a href="https://bit.ly/3Q2pn1C">Termbuddy__Team71</a>


### Directory Structure
- ***Frontend:*** The Frontend code is found in this repository.
- ***Backend:*** The Backend code is found in the <a href="https://github.com/zuri-training/t_c-generator_team71_BE">Backend</a> repository.


### Project Status
> In Progress


### Tools Used
- JavaScript | CSS3 | HTML5 | Git | GitHub
- Figma | Figjam
- Python | Django-Rest Framework
- Fetch API 

### Client
- Indivuduals
- Startups
- Large Corporations

### Features and Accessibilities

#### Unauthenticated User - Feature Requests
- Visit the platform to view basic information about it.
- View and interact with the documentation.
- Register to view more details.
- No access to use until registered

#### Authenticated User - Feature Requests
- Full access to the platform
- Allow users enter basic information
- Generate selected files with the right data and information
- Allow export, download, share and website embed
- Allow user save data and come back to download


#### Unauthenticated User - Accessibilities on Termbuddy
The Unauthenticated User has access to: <br />
- Landing Page
    - Header (consists of Products, Templates, About Us, Contact Us, Docs, Sign Up button, Sign In button)
- The About Us Page
- The Product Page
- The Contact Us Page
- The Docs Page (User Documentation) <br /><br />

#### Authenticated User - Accessibilities on Termbuddy
The Authenticated User has access to: <br />
- The Dashboard
- Generate a Terms and Conditions agreement
- Generate a Privacy Policy agreement
- Fill in necessary requirements
- Have their data saved and come back to continue from where they left
- Preview the agreement before generating it
- Edit the agreement before generating it
- Export, share, download and embed the agreement onto their website 

### Collaboration
1. Fork this repository <br />
Click the gray `Fork` button in the top right of this page. This creates *your* copy of the project and saves it as a new repository in your github account

2. Open your text editor and  Clone your forked repository 
```js
  git clone https://github.com/YOUR_GITHUB_USERNAME/hacktoberfest-practice.git
```

3. Switch to the cloned folder. If you're already in it, then skip this process 
```js
  cd t_c-generator-team71
```

4. Run the command `git status`. <br /> You should get a response like this
```js
    On branch master
    Your branch is up to date with 'origin/master'
```

5. Create a new branch for the feature you are adding and switch to that branch
```js
    git checkout -b <your_branch_name>
```

6. To check you have correctly switch to your new branch. Run 
```js
    git branch -a
```
you should see an asterisk sign * in front of your new branch

7. Navigate to the directory (Backend or Frontend) relating to your contribution and input your changes
```js
    cd Frontend / cd Backend
```
8. After inputting your changes, navigate back to the root directory. Run `cd..` till `t_c-generator-team71` is the last path in your terminal. For example
```js
    C:\Users\hp\Desktop\Merckury\zuri-training\t_c-generator-team71>
```

9. Stage your changes
```js
    git add "<name_of_your_file>"
```

or 

```js
    git add .
```

10. Commit your changes
```js
    git commit -m "Add <your_file_names>"
```

11. Push your changes
- If you are PUSHING FOR THE FIRST TIME <br />
 Set your upstream branch to the new branch you created and push that branch to your forked repo
```js
    git push --set-upstream origin <your_branch_name>
```
- If you have pushed a change before, and you want to push some more changes later. Run
```js
    git push origin <your_branch_name>
```

12. Run `git status` and you should get a response like this
```js
    "On branch <your_branch_name>"
    "Your branch is up to date with 'origin/<your_branch_name>'."
```

13. Go to your forked Repo on Github and Create a pull request

14. Before you compare and create a pull request, make sure the base directory is `zuri-training/t_c-generator-team71` and the base branch is set to `develop`. <br />
If the base branch is set to `master`, click the dropdown beside it and select `develop`

15. Once that is done, Click on the `Create Pull Request`

16. ***DO NOT MERGE YOUR PULL REQUEST!***
