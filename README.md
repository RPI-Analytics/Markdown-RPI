# Markdown, Jupyter, and Github as a New Publishing Paradigm for Classroom Content



## Why take this session?

Markdown is a versatile tool that can be used throughout the teaching experience.  With markdown you can prepare slides, notes, interactive demonstrations, write computer code, include images in documents and typeset equations.  When paired with tools such as Project Jupyter and GitHub it can be a gamechanger for the way you work in the classroom and give you an opportunity to have a broader impact in your domain of expertise.

## Who is this session for?

Anyone who prepares classroom or lab content to be curated alone or in teams for delivery to students.

## How can I use markdown to help me in the classroom?

* Markdown/Github can help you to quickly create a styled course website without learning HTML.
* Markdown/Jupyter can allow you to combine (1) content/narrative, (2) equations/formulas, (3) calculation/computation, (4) assignments, and (5) presentations. 
* Provides access to what is potentially a new publishing paradigm.

## What will I learn in this session?

After taking this one-hour tutorial the attendee will:

* Understand the contexts where Markdown is used
* See one example classroom use-case
* Explore and use the basic syntax of Markdown
* (If all goes well) Develop one or two examples on your own

### Jupyter Notebooks

One example use-case for Markdown is through the Jupyter Project's Jupyter notebook.  The link to that project is [here](http://jupyter.org/index.html).  Our intent in this tutorial is to provide access to a Jupyter notebook for the attendee so that you can write some content.  This might be for a class, a homework assignment, a lab tutorial or similar.  

While not specific to the Jupyter notebook, the notebook interface provides a simple way for us to practice markdown with a minimum of overhead.

### Interactive session

Let's get started!

# TLDR/Can't Attend?  Here are the basics:

## (1) Getting Started with Markdown
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

(TBD put in example on using equations)

## (2) Getting Started with Github for a Course Webpage

### Why Markdown and Github?

(1) Creates a very professional looking website in almost no time. <br>  
(2) Easy for students to access information. <br>
(3) Easy to update information. <br>
(4) Easy to reuse information from year to year. <br>
(5) Easy to collaborate with other content creaters. <br>
(6) Version control.

### Getting Started
- A github *repository* is the foundation for a class website. This requires at least one markdown file, `readme.md`.  
- A repository is a "digital directory or storage space where you can access your project, its files, and all the versions of its files that Git saves." - [readwrite.com](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1/)
- Can be used for a wesite, or to share files as well. 

### Example Repository  
- Fork an [example repository](https://github.com/RPI-Analytics/class-webpage-example) in order to get your first website started.  
- Click on **Settings->Source->Master Branch**
- Click on **Theme Chooser**
- It will take a few minutes to generate your website, but that is it!

### Creating a New Page
- Relative references are allowed for links, so you just need to include something like:

```
[New class page](./class_new.md)
```

### Use a GIST for your New Page. 
- *Probably not the best practice, but for some reason I got into habit of doing this.*
- Go to [https://gist.github.com](https://gist.github.com)


### Tips and Tricks
- [Click here](https://raw.githubusercontent.com/RPI-Analytics/markdown-RPi/master/README.md) to see the raw markdown. 
- [Click here](https://github.com/RPI-Analytics/markdown-RPi/blob/master/README.md) to see the styleized version.
- [Click here](https://rpi-analytics.github.io/markdown-RPi/) to see the website which is automatically generated through a cool tool [Jekyll](https://jekyllrb.com) (which you don't have to learn anything about.)   

[Here](https://jkuruzovich.github.io/tech-fundamentals-analytics/) is an example of a full course website.  This is just for content delivery and not for grading or assignments.  We still use the LMS for that. 


## (3) Try Jupyter 

Want to get markdown + programming/computiation +  naritive + automated slides + autograding all in one package? [Jupyter](http://jupyter.org) is an open source project that allows a tremendous amound of different languages (Python, R, Matlab, Ruby, etc) in an interactive notebook environment.  It is being used in [Google's DataLab Project](https://cloud.google.com/datalab/), [IBM's Data Science Experience](http://datascience.ibm.com), and [Microsoft's Azure ML Studio](https://blogs.technet.microsoft.com/machinelearning/2015/07/24/introducing-jupyter-notebooks-in-azure-ml-studio/).

Here are a couple of ways to try it out:
- Go to [https://try.jupyter.org](https://try.jupyter.org/) to launch your own Jupyter notebook.  

## (4) Workshop Slides

See the [markdown slides](http://nbviewer.jupyter.org/format/slides/github/RPI-Analytics/Markdown-RPI/blob/master/Slideshow_Example.ipynb#/) for this workshop.

See the [Google slides](https://docs.google.com/presentation/d/1qd5hv_Gg7curDYiWDBeMx-ElmK5aSWDEUAGcoKKQcik/edit?usp=sharing) here.  


Workshop outline
* Introduction (2 minutes)
* What is Markdown:  Syntax (7 minutes)
* Case study One:  Website (7 minutes)
* Case study Two:  Course Notes (7 minutes)
* You try it! (20 minutes)
* Where is this technology going?  (10 minutes)

## (5) Case Studies Reference

Here are three case studies that use markdown and notebooks.
