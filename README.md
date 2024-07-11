# Hosting static web site / web pages in a GitHub project repository

*AL11Jul2024*

**HTML** pages placed directly on **GitHub** are not available for browsing.  
Instead, they are either shown as text files, or not shown at all if accessed in the browser:  
https://github.com/AlexeyLarionovCranfield/web_pages_on_github/analysis.html  

To host a web site/ web page on GitHub, in a way that the HTML page would be properly seen in a browser, you need to use GitHub **Pages** in your project.  

In short (after you sorted out the GitHUb credentials and can push to your GitHub repository):  
1) Make "docs" folder in your project folder, place your HTML file there, push changes into the GitHub repository.  
2) Go to the GitHub repository, select "Settings" in the top menu (on the left), select "Pages" in the left menu (scroll down if needed).  
3) In the "Build and deployment" section check that  
- "Deploy from a branch" is selected  
- "master" branch is selected (or "main" branch, if you use "main" as "master")  
- "/docs" folder is selected on the branch (if it was */root* by default, change it to */docs*).  

After all is done, the page should be accessible at address  
https://AlexeyLarionovCranfield.github.io/web_pages_on_github/analysis.html  

Note https://username.**github.io**/repository/file_name address format.  

If you put **index.html** file into your */docs* folder, it will be opened if browser accesses this address:  
https://AlexeyLarionovCranfield.github.io/web_pages_on_github  

You may read more about GitHub Pages at https://pages.github.com/  
