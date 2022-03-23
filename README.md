# Hosting a Static Resume Website

This document will show you how to host your markdown formated resume on web using a static website generator . 

## Getting Started

The resume is made in a markdown formatted file. To see the contents of the resume on GitHub pages, 
click [here](https://afazmunshi49.github.io/). If you would like to download the resume on your local machine then see the installing section in this file.

### Prerequisites

- To create a resume like this and host it online, we will be using a few tools like Jekyll, VS code, and GitHub Pages. If you don't have these tools on your local machine, then feel free to follow the link and download.
- You will also need to know how to write in markdown fomat, use the link below to learn more about markdown files and its usages.
- You should also have some knowledge about using Git and GitHub
- You should know how to use a terminal (e.g. cmd)
- [jekyll](https://jekyllrb.com/)
- [VS code](https://code.visualstudio.com/)
- [Markdown Files](https://www.markdownguide.org/getting-started/)

Etter's book really encourages the its readers to use a static site generator like Jekyll and a markdown formatted file. As opposed to a pdf, this type of documentation can easily be updated by the developer. The pdf will sit on your local machine and will never get updated and hence forcing you to download/upload a copy everytime there is an update. On the other hand, in a static website, once an update is made, it get updated for all the users.

### Instructions

In order to get started with the project, we will first create a resume using a markdown formatted file.

1. Open VS code on your local machine and write your resume in markdown formatted file. Save that file by the name of index.md. This will be the file that will be executed on your static website

       index.md

2. Now we want to give styling to the reusme, for this we will be using Jekyll. For this part, you can use your terminal to browse down to the directory of your index.md. Now run the command 
        jekyll new _config.yml
It is impartant that you save your file name as, _config.yml, this is to give GitHub pages an indication that we are using Jekyll. You can add the styling you want on your resume in this file. An example of a basic style is,
        theme: jekyll-theme-slate
This will give a basic style to your resume template.

3. Create a new repository on GitHub. Make sure you have proper naming convention in order to host your website on GitHub Pages. The name of your repository should be your user name folled by a dot (.) followed by github, followed by a dot (.) followed by io. For example my user name is afazmunshi49, this means my repo should be named as follows,
        afazmunshi49.github.io

4. Now it is time to host our resume on GitHub Pages so that it is available to the entire world and not just to un on our local machine. Start by cloning the repository you just created inside the folder where you stored your resume is on your local machine using a terminal.
        git clone https:\\git_user_name\repo_name\

Commit your local git repo and finally push your code on the remote repository.

5. Finally, your static resume website is up online. To test your website, type `https:\\` followed by the name  of your repository, this will prompt GitHub pages to open your `index.md` file on your browser and show your resume like a browser.


Etter's book really encourages its readers to use a distributed version control like GitHub. This allows multiple developers (contributors) to make a contribution to the project. This will also allow them to host their site on GitHub Pages which is accessible to everyone.

# GIF
![My resume GIF](giphy.mp4)

## Built With

  - [Jekyll](https://jekyllrb.com/) - Used as a static site generator to give styling to the resume
  - [VS code](https://code.visualstudio.com/) - Used as an editor to write the markdown file
  - [GitHub Pages](https://pages.github.com/) - Used to host the resume on web 

## Authors

  - **Mohammadafaz Munshi** - *Wrote a resume and readme file in markdown format*
  
## More Resources
    [Etter's Book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
## FAQ's
 1. Why are GitHub pages not showing my markdown?
 - Sometimes GitHub Pages take time to update your resume. If it is not showing at the moment, then come back after a 20 minutes
 
 2. Why is the styling not showing on my local machine?
 - Make sure that Jekyll is installed on your computer before executing the file
 