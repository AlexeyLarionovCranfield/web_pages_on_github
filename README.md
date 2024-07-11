# Hosting static web site / web pages on a GitHub project repository

*AL11Jul2024*

Html pages placed directly on GitHub are not rendered for browsing.  Instead, they are shown as text files, if accessed in the browser:  
https://github.com/alexeylarionovcranfield/test_01/Analysis.html  
To make a proper web site/ web page, which would be shown properly in a browser, you need to use GitHub Pages in your project.  

In short (after you sorted out the credentials and can push to your GitHub repository):  
1) Make “docs” folder in your project folder, place your html file there, push changes into the GitHub repository.  
2) Go to the GitHub repository, select “Settings” in the top menu (on the left, select “Pages” in the left menu (scroll menu down if needed).  
3) In the “Build and deployment” section check that  
- “Deploy from a branch” is selected,  
- “master” branch is selected (or “main” branch, if you use “main” as “master”)  
- /docs folder is selected on the branch (if it was /root by default, change to /docs)  

After all is updated, the page should be accessible at address  
https://alexeylarionovcranfield.github.io/test_01/Analysis.html  
Note .../<username>.github.io/<repository>/... address syntax.  

You may read more about GitHub Pages at https://pages.github.com/  


