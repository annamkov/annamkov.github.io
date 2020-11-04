# How to Host your Resume on Github Pages

## Intro
This README will teach you how to host your resume as a website through Github Pages. It will also outline documentation strategies described in Andrew Etter’s book, _Modern Technical Writing_. These strategies will likely be applicable in your future work, and knowledge of them will therefore be valuable to showcase in your interviews.

**Prerequisite:** A resume formatted in Markdown. See the More Resources section of this README for a link to a Markdown tutorial. 

## Step 1: Register for Github
Github is a website used to store files. The files for a project are stored in what is called a repository. You will use Github to store the files required to host your website. Why use Github? Github is a version control system, which means that it keeps track of changes made to files and maintains a record of all previous versions. The content in your repository will always be up-to-date and easy to manage because you will not have to keep manual track of files. Github also makes for a seamless collaborative environment. The official, up-to-date version of a project is placed in a master branch, and each user that wants to makes changes works on a copy of the master in a new, separate branch. This way, multiple users can independently edit files at the same time, and Github will take care of merging the changes to the master branch.
- Register on [github.com](github.com)

## Step 2: Set up a Repository for Github Pages
Github Pages is a service provided by Github that can be used to host your repository as a static website. Etter praises static websites for their speed, simplicity, portability, and security. Static sites load faster than dynamic sites because there are no server-side application dependencies, and no databases to interact with before displaying content. Static sites simply deliver the same HTML for every visitor on the page instead of generating content on the fly. Having no databases also makes migrating a static site to another system incredibly easy. Lastly, static sites are protected from malicious activity because there are no databases to steal information from. All of this makes static websites great for hosting documentation.

To set up your static website on Github Pages:
1. Set up a new repository by clicking on the “New” button found on the top left side of the homepage.
2. Name the repository **\<username>.github.io**, using your Github username for the **\<username>** part. It is important to follow this naming convention so that Github knows you are setting up a special repository for hosting a website through Github Pages. 

## Step 3: Upload your Resume Formatted in Markdown to your Repository
Markup languages are used to format content on a webpage. HTML is a well-known markup language; however, the heavy syntax often makes writing an HTML document from scratch inefficient. Markdown, on the other hand, is a simplified Markup language. It has minimal syntax and converts to HTML easily, making it a fast way to format text for the web. Markdown has less features than HTML, but is ideal for simple text documents where the more complicated features of HTML are not needed (such as this README and your resume). 

To upload your Markdown resume file:
1. Click on **Add File**. A dropdown menu should appear. 
2. Click on **Upload Files**.
3. Locate and upload your Markdown resume file.
4. Rename your Markdown resume file to **index.md**. Github Pages will search through your repository for a file under this name to use as the front page of your website. 

## Step 4: Use Jekyll to Customize your Github Pages Website
Github Pages comes with a static site generator called Jekyll. Jekyll takes files written in lightweight markup, runs them with a theme (templated HTML and CSS), and generates a static website with a presentable design. The great thing about static site generators like Jekyll is that they can upgrade the look of your website with barely any effort on your part. You can avoid the tedious process of writing in HTML by providing Jekyll with a file in a lightweight markup language such as Markdown. After that, you can simply choose a theme and Jekyll will do the hard work of adding HTML for you.

To choose a Jekyll theme for your static website:
1. Click on **Settings** in your repository.
2. Scroll down to the Github Pages heading.
3. Locate and click on the **Change theme** button under the Github Pages heading.
4. Preview a theme by clicking on its thumbnail.
5. Select a theme by clicking on **Select theme**.

Once you select a theme, a **\_config.yml** file will appear in your repository. You can further customize your website in this file. This tutorial will keep customization brief and simply show you how to change the title of your website. 

To change the title of your website:
1. Edit the **\_config.yml** file by clicking on the pencil icon.
6. Add `title: <yourtitle>`, where \<yourtitle> is a title of your choice. 
2. View your changes at **\<username>.github.io**


There you go! You should now have your resume hosted through Github Pages, such as the one below:

![screenshot](https://media3.giphy.com/media/wkwZ2ffx6dHOlZMwJ1/giphy.gif)


## More Resources
- [Markdown Tutorial](https://www.markdowntutorial.com/)
- [Markdown text editors, listed by OS](https://www.oberlo.ca/blog/markdown-editors)
- [Andrew Etter's book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

## Authors
- **Billie Thompson** - *Provided README Template* -
    [PurpleBooth](https://github.com/PurpleBooth)

See also the list of
[contributors](https://github.com/PurpleBooth/a-good-readme-template/contributors)
who participated in developing the README template.

## Acknowledgments
- Andrew Etter, the author of _Modern Technical Writing_.
- My COMP3040 groupmates: Ruiqi Zeng, Jaskaran Singh, and Jasdeep Singh.

## FAQ

#### Why is Markdown better than a word processor such as Microsoft Word?
- Microsoft Word is restricted to macOS and Windows, whereas the plain text files used for Markdown are supported across all operating systems. Word must also be purchased, whereas plenty of free text editors exist for Markdown.

#### Why is my theme not changing?
- This is normal. It can take up to 10 minutes for changes to be reflected on a new Github Pages website. 
