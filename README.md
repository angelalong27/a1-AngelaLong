Assignment 1 - Hello World: Basic Deployment w/ Git, GitHub, Render
===

*DUE: Friday, August28, 2025 by 1:59 PM*

First assignment! You will deploy the starting Web site that you will use this term to [Render](https://www.render.com/). 

Treat this assignment as a chance to get up to speed on Git, GitHub, and Render, as well as experiment some with HTML/CSS/JS.

**AI POLICY REMINDER:** You must adhere to the AI policy described in the course syllabus, including citations of any AI tools you used and how you used them.

Assignment details
---

This assignment requires that your website is both contained in a GitHub repository and hosted in Render.

### Clone to computer, push to Github, import to Render (recommended)

1. Fork the starting assignment code in GitHub. This repo contains the following:
    * The server code, `server.js`
    * A starting `index.html` file that you will edit as described below
    * A package.json file that helps configure Render
    * This README
2. Edit `index.html` to show the following information about you:
    * your name and class at WPI (e.g. class of 2025) Note: Do not put any contact or personal information that you do not potentially want other people outside of this class to see.
    * your major(s) and minor(s)
    * previous computer science courses that you have taken at WPI
    * your experience with the following technologies and methods (none, some, a lot)
        * HTML
        * CSS
        * JavaScript / Typescript
4. Test your project to make sure that when someone goes to your main page, it displays correctly. You can do this locally by simply running `node server.js` from within the assignment directory and then going to `localhost:3000` in your browser.
5. Modify the README file according to the specification below.
6. Commit and push all your changes to GitHub. 
7. Deploy your project to Render. You can do this by [importing the repo from GitHub](https://render.com/docs/github).
    * You will need to create an Render account first.
    * Under "Publish Directory", you can just put "./" (without the quotation marks).
8. Ensure that your project has the proper naming scheme (guide follows) so we can find it.
9. Create and submit a Pull Request to the original repo. This helps us find your project.
	* Ignore any messages about conflicts. You do not need to resolve them.
	* Make the title of your pull request "Pull Request for NAME" (ex. "Pull Request for Charlie Roberts")

### Note about alternative hosting
Our use of Render in this class is there as a convenience for you. However, if you are already familiar with hosting through other services--or if you would like to self-host--that's perfectly fine so long as the website in question meets all of the assignment requirements. Note that we will not be able to help you if you run into issues on other hosting platforms, and you will be responsible for making sure the website stays up and running for the duration of the term. For A1, you will also still need to create a pull request with your name and your website's URL.

Naming and URL Scheme
---

You must use a consistent naming scheme for all projects in this course.
If we can't find it, we can't grade it.

The name scheme should be `a1-yourFirstAndLastName`.
The `a1` will need to be updated to `a2`, `a3`, and so on in future assignments.

Rubric
---

*Basic Requirements*
Note the highest grade you can receive is a 100%.  

1. Assignment has proper naming scheme (10 points)
2. Files forked from original repo (10 points)
3. `index.html` properly rendered, no obvious visual errors / extraneous characters (15 points)
4. `index.html` page properly edited (contains doctype, charset, and validates at https://validator.w3.org/, 10 points)
5. All changes pushed to GitHub (10 points)
6. Project deployed to Render (or other hosting option, 15 points)
7. Pull Request submitted to original repo (15 points)

Sample Readme (delete the above when you're ready to submit, and modify the text below with your links and descriptions)
---

Charlie Roberts
http://a1-charlieroberts.onrender.com

Angela Long


This project shows

## Technical Achievements
- **Styled page with CSS**: Styled my website using CSS. I changed the background and text colors using my color palette, added a border to my table, changed the font style and size of the text, and added padding to the header and footer.  
- **JavaScript Animation**: I used a JavaScript animation that reveals the title of my website starting from the end of it.
- **Experimented with other *semantic* HTML tags**: HTML tags that I used in my website are header, footer, table, section, and link. The header includes the title of the website, my major, and class year. The footer includes the course number and name. The table has my previous computer science courses. The section tag is used for the Previous Computer Science Courses and Experience sections. I included a link of CS 4241 Course Information in the footer. 

## Design Achievements
- **Color Palette**: I used Adobe Color and Pinterest to help create and come up with my color palette. I used all five colors throughout my website.
- **Used the Miranda Sans Font from Google Fonts**: I used Miranda Sans from Google Fonts as the font for the primary copy text in my website.