1. Introduction

For this mini-project, you’ll deconstruct an existing web page and rebuild it. Don’t worry if the links don’t go anywhere and the search box doesn’t do anything when you submit it. The goal is to start thinking about how elements get placed on the page and roughly how they get styled and aligned. For some of you, this may be the first time you’ve actually tried to “build” something in HTML (very exciting!).

Using the browser’s developer tools (right-clicking something on the page and clicking “inspect element” will get you there) will be your best friend. Build the page in a .html text file and open it in your browser to check it out.

When you’re building your project, you will probably end up doing several git add + git commit cycles before being ready to push it up to GitHub with git push origin main.

When writing code, it’s considered best practice to commit early and often. Commit every time you have a meaningful change in the code. This will create a timeline of your progress and show that your finished code didn’t appear out of nowhere.

If you have entered git push origin main and typed out your username and password, if you refresh your GitHub page, you should see new files added onto GitHub.

Okay, that’s enough Git for the moment – time to actually build stuff!

2. Assignment

Easy Version: Build the Google.com homepage
(the simple one with just a search box).

Inside your project folder, create your index.html file.

2.1. Tips:
DON’T BE A PERFECTIONIST! You’re just trying to make it look like google.com, not actually function like it and it doesn’t have to be spaced exactly the same way to the pixel. Any dropdown menus or form submissions or hover-highlighting should be ignored.
USE GOOGLE! You’ll probably run into roadblocks where you can’t figure out how to do something so do what all good devs do… Google it!
Now is a good time to set up the live server extension in VSCode, if you haven’t already. This extension will save you from the hassle of refreshing the browser window repeatedly to see changes made in your code and will automatically load the most recent change in the browser window.
If you’re frustrated with trying to get buttons or inputs to style the way you want (for instance, they seem to just not respond to any styles), look into the CSS property -webkit-appearance: none; or -moz-appearance if you’re using Firefox.

2.2. Start with just putting the main elements on the page (the logo image and search form), then get them placed horizontally. You can either download the Google logo or link directly to its URL on the web in your <img> tag.

2.3. Next do the navbar across the top, first building the content and then trying to position it. Check out how to build a horizontal CSS navbar if you’re lost.

2.4. Finally, put in the footer, which should be very similar to the top navbar.

2.5. In general, do as much on your own as you can before relying on the developer tools (or viewing the page’s source code) to help you along.

2.6. Push your project to GitHub using the instructions above! Then consider sharing your project with the community by submitting a link to your repository in the Solutions section below.

3. Difficult Version (optional): Build the Google.com search results page
You should be able to reuse much of your code from before if you started with that project. Again, don’t worry about links to nowhere and forms that won’t submit and hard coding the search results (which you’ll have to do of course), just focus on placement and order of items on the page.

4. Viewing the site on the web
If you want to show your work (the project) to others, or submit a solution below, you will need to publish your site so that others can access it from the web, rather than just on your local machine. The good news is that if you have your project on GitHub (as described above) doing this is incredibly simple.

GitHub allows you to publish web projects directly from a GitHub repository. Doing this will allow you to access your project from your-github-username.github.io/your-github-repo-name

There are a couple of ways to go about doing this, but the simplest is this:

make sure that the main HTML file of your project is called index.html. If it is not, you will need to rename it.
go to your GitHub repo on the web and click the Settings button
click on the right side bar on Pages
change the Source from none to main branch and click Save.
it may take a few minutes (the GitHub website says up to 10) but your project should be accessible over the web from your-github-username.github.io/your-github-repo-name (obviously substituting your own details in the link)