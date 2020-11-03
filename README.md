# How to Host your Resume on Github Pages

## Intro
This README will teach you how to host your resume as a website through Github Pages. It will simultaneously cover strategies for achieving great documentation described in Andrew Etter’s book, _Modern Technical Writing_. These strategies will likely be applicable in your future work and knowledge of them will therefore be valuable to showcase in your interviews.

**Prerequisite:** A resume formatted in Markdown.

## Step 1: Register for Github
You will use Github to store the files required to host your website, most notably the Markdown file you created of your resume. Why Github? Github is a version control system, which means that it keeps track of changes made to files and maintains a record of all previous versions. The files in your repository will always be up-to-date, a benefit which can be contrasted with having to open several PDFs with similar names to determine which file is the latest version. With changes being recoverable and latest versions being easily accessible, Github makes for a seamless collaborative environment used by many developers. 

## Step 2: Set up a Repository for Github Pages
Github Pages is a service provided by Github that can be used to host a repository as a static website. Etter praises static websites for their speed, simplicity, portability, and security. Static sites load faster than dynamic sites because there are no server-side application dependencies and no databases to interact with before displaying content. Static sites simply deliver the same HTML for every visitor on the page instead of generating content on the fly. Having no databases also makes migrating a static site to another system incredibly easy. Lastly, static sites are secure from malicious activity because there are no databases to steal information from. 

To set up your static website on Github Pages:
1. Set up a new repository by clicking on the “New” button found on the top left side of the homepage.
2. Name the repository \<username>.github.io, using your Github username for the \<username> part. It is important to follow this naming convention so that Github knows you are setting up a special repository for hosting a website through Github Pages. 

## Step 3: Upload your Resume Formatted in Markdown to your Repository
Markup languages are used to format content on a webpage. HTML is a well-known markup language; however, the heavy syntax often makes writing an HTML document from scratch inefficient. Markdown, on the other hand, is a simplified Markup language. It has minimal syntax and converts to HTML easily, making it a fast way to format text for the web. Markdown has less features than HTML, but is perfect for simple text documents where the more complicated features of HTML are not needed (such as this README and your resume). 
To upload your Markdown resume file:
1. Click on "Add File". A dropdown menu should appear. 
2. Click on "Upload Files".
3. Locate and upload your Markdown resume file.
4. Rename your resume file to index.md.  

## Step 4: Use Jekyll to Customize your Github Pages Website
Github Pages comes with a static site generator called Jekyll. Jekyll takes files written in lightweight markup, runs them with a theme (templated HTML and CSS), and generates a static website with a presentable design. The great thing about static site generators like Jekyll is that they can upgrade the look of your website with barely any effort on your part. You can avoid the tedious process of writing in HTML by providing Jekyll with a file in a lightweight markup language, such as Markdown. Then, you can simply choose a theme and Jekyll will do the hard labour of adding the HTML for you.

To choose a Jekyll theme for your static website:
1. Click on Settings in your repository.
2. Scroll down to the Github Pages heading.
3. Locate and click on the “Change theme” button under the Github Pages heading.
4. Preview a theme by clicking on its thumbnail.
5. Select a theme by clicking “Select theme”.
6. Update the title of your website by editing the \_config.yml file that appears in your repository.
7. View your website at <username>.github.io. Note that it can take some time for your changes to be reflected.

## More Resources
- Markdown tutorial: https://www.markdowntutorial.com/
- Markdown text editors, listed by OS: https://www.oberlo.ca/blog/markdown-editors
- Andrew Etter's book: https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS

## Authors
- **Billie Thompson** - *Provided README Template* -
    [PurpleBooth](https://github.com/PurpleBooth)

See also the list of
[contributors](https://github.com/PurpleBooth/a-good-readme-template/contributors)
who participated in developing the README template.

## Acknowledgments
- My COMP3040 groupmates: Ruiqi Zeng, Jaskaran Singh, and Jasdeep Singh.

## FAQ

#### Why am I using Markdown?
- Markdown is a simplified Markup language. It has minimal syntax and converts to HTML easily, making it a fast way to format text for the web. Markdown has less features than HTML, but is perfect for simple text documents where the more complicated features of HTML are not needed (such as this README and your resume). 

#### Why ?
- Github Pages will search through your repository for a file under this name to use as the front page of your website.



You can use the [editor on GitHub](https://github.com/annamkov/annamkov.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/annamkov/annamkov.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
