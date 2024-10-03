# Why Learn Coding 

* This section is to give context to:

* Understanding computing: This section is to familiarize you wth important foundational concepts and to give you a framework for understanding the types of computational methods you can use on a projects, including: minimal computing, tool choice or coding.  Finally, this session aims to give you language to conceptualize what is possible and to communicate more effectively with partners. 

* Understanding the affordances and limitations of a computational approach for your project will help you better imagine, plan manage your project. Even if you are not directly involved in the coding aspect, this will give you the tools to better collaborate with those who will.

# Computers & The Internet
## What is a computer?  
* How do you make the computer do stuff? What is a GUI? 
* Refer back to the optional viewing from the introduction:  
* The following links will introduce terms such as input, output, storage, CPU, hardware, software, bits, circuits, and the operating system, as well as wired, cables, WiFi, packets, DNS, IP addresses, packets and routing, HTTP and HTML, encryption, public keys, and how search works. 
  * [Code.org. Introducing How Computers Work.YouTube](https://www.youtube.com/watch?v=OAx_6-wdslM&list=PLzdnOPI1iJNcsRwJhvksEo1tJqjIqWbN) [Watch all 6 short videos.]
  * [What Is the Internet? YouTube](https://www.youtube.com/watch?v=Dxcc6ycZ73M&list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7) [Watch all 8 short videos.] 
      * [Same series at Kahn Academy](https://www.khanacademy.org/computing/code-org/computers-and-the-internet#how-computers-work)

## What computational skills are necessary for your goals?
* Keep in mind: What coding language do I need to learn *or* do I need to learn to code is *not the right question,* the question is how much do I need to learn for my specific goal?
* You may have multifaceted goals, some are learning related and some are productivity related.
* They may not be mutually exclusive, but you will likely still need to make choices based on your circumstances.  

# Computing Environment  
* "The computing environment involves the collection of computer machinery, data storage devices, work stations, software applications, and networks that support the processing and exchange of electronic information..." -[Computing Environment](https://www.sciencedirect.com/topics/computer-science/computing-environment) 

*What does this all mean?* 

## What is your environment?  
* How can you interact with your environment (local, virtual, cloud)?  
* There are different affordances and limitation in each environment, you will make different choices depending on the needs of you project or the needs of your classroom. 
* Below we go further into depth about the  difference and then the reasons we made the choice we did for the Python session.

## Local environments
- Your laptop or desktop or tablet, etc. is your local environment. 
* The applications on your device can access the resources in your machine. Each local environment becomes different with use. 
* The [kernel](https://en.wikipedia.org/wiki/Kernel_(operating_system)) connects the application software to the hardware of a computer.

[![kernel](https://github.com/SouthernMethodistUniversity/git/raw/main/images/kernel.png)](https://en.wikipedia.org/wiki/File:Kernel_Layout.svg)

* Local installations give you more control, and more power, but the pedagogical tradeoff is that it is more difficult to manage and configure during class. Installation is dependent on type of device. 

* The process of installing and learning how to work on your computer encourages more active troubleshooting as well, which is a useful long-term skill.


## Virtual environments

A virtual environment is a digital instance of a local computing environment that can perform almost all the same functions as that local machine, ["including running applications and operating systems. Virtual machines run on a physical machines"](https://cloud.google.com/learn/what-is-a-virtual-machine)... using specialized software or internet browsers.


## The "Cloud"
- ["Cloud computing](https://en.wikipedia.org/wiki/Cloud_computing) is the on-demand availability of computer system resources, especially data storage (cloud storage) and computing power, without direct active management by the user.Cloud computing is the on-demand availability of computer system resources, especially data storage (cloud storage) and computing power, without direct active management by the user."

* Cloud based systems may be expensive, it may be resources intensive, so you may choose the path of [Minimal Computing](https://go-dh.github.io/mincomp/about/): "We use “minimal computing” to refer to computing done under some set of significant constraints of hardware, software, education, network capacity, power, or other factors. Minimal computing includes both the maintenance, refurbishing, and use of machines to do DH work out of necessity along with the use of new streamlined computing hardware like the Raspberry Pi or the Arduino micro controller to do DH work by choice. This dichotomy of choice vs. necessity focuses attention on computing that is decidedly not high-performance."
* Using the resource tha matches your needs can help you minimize costs and environmental impact.

# How do you interact with your computer?
* Most of us are used to a graphical user interface [GUI](https://en.wikipedia.org/wiki/Graphical_user_interface) but the command line allows you more control.

# Command Line

* What is the command line and why is it like this?

The command line is a text-based way of interacting with your computer. Working in command line helps you make a mental model of how you environment is layed out. This environment is the result of a series of choices, made by humans.  

You may hear it called different names, such as the terminal, the shell, or bash. In practice, you can use these terms interchangeably. If you're curious, though, you can read more about them [here.](https://askubuntu.com/questions/506510/what-is-the-difference-between-terminal-console-shell-and-command-line) The shell we use (whether terminal, shell, or bash) is a program that accepts commands as text input and converts commands into appropriate operating system functions.  

And yes, "the command line" is also laden with masculine and military metaphors, which is reflective of the history of computing and programming. 

* As Wendy Hui Kyong Chun discusses in ["On Software, or the Persistence of Visual Knowledge," (2004)](https://direct.mit.edu/grey/article/doi/10.1162/1526381043320741/10837/On-Software-or-the-Persistence-of-Visual-Knowledge) almost all computers (as in human comput-ers) in the US during World War II were young women. Human computers received commands from analysts &#8212; predominantly men with the military &#8212; that they then had to interpret and act upon the machine. As Chun argues, "computation depends on 'yes, sir' in response to short declarative sentences and imperatives that are in essence commands ... The command line is a mere operating system (OS) simulation" (page 34). The command line (of computers today) receives these commands as text that is typed in.  

<!--These repositories we are using for our lessons additionally have a lot of racialized terms. [See 'Ditch These Racist Terms From Your Tech Vocabulary.'](https://lifehacker.com/ditch-these-racist-terms-from-your-tech-vocabulary-1844041452)-->


## Why is the command line useful?

Initially, for some of us, the command line can feel a bit unfamiliar. Why step away from a GUI point-and-click workflow? By using the command line, we move into an environment where we have more minute control over each task we'd like the computer to perform. Instead of ordering your food in a restaurant, you're stepping into the kitchen. It's more work, [but there are also more possibilities."](https://www.freecodecamp.org/news/command-line-for-beginners/#whyshouldievencareaboutusingtheterminal)

The command line allows you to...

* Easily automate tasks such as creating, copying, and converting files.
* Set up your programming environment.
* Run programs you create.
* Access the (many) programs and utilities that do not have graphical equivalents.
* Control other computers remotely.

In addition to being a useful tool in itself, the command line gives you access to a second set of programs and utilities and is a complement to learning programming.
  * Wring a script or program (programming!) allows you to automate a series of repetitive tasks.  

What if all these cool possibilities seem a bit abstract to you right now? That's all right! On a very basic level, most uses of the command line are about **showing information** that the computer has, or **modifying or making** things (files, programs, etc.) on the computer. 

## Introduction to the command line

By this point in our academic careers, most of us have figured out some ways we like to interact with computers. Whether that involves avoiding them as much as possible or constantly testing new software, we likely have some ideas about how we feel comfortable getting things done. How would you show a person who had never seen a computer, say [Kimmy Schmidt](https://youtu.be/LIdFa1qLgNQ) or [Brendan Fraser in *Blast from the Past*](https://youtu.be/Xq29uTtKW4M), how to *do* something on your computer? 

Many of us would explain what a screen and a cursor are, and then show how to point and click on icons. This approach relies on athe  graphical user interface, or GUI (pronounced "gooey!"). 

Another way to make your computer do things: through the command line. Instead of pointing and clicking, we'll be typing in either Git bash (Windows) or terminal (OSX) to tell the computer directly what task we'd like it to perform. 

* Here is an external [command line tutorial](https://ryanstutorials.net/linuxtutorial/) if you wish to learn more. 


# Coding 
 Why teach coding?
“...any instructor—-in the humanities or otherwise-—must first ask herself what she hopes her students will accomplish by learning to code. *Is it an understanding of how to think algorithmically, so as to better comprehend how certain tasks can be abstracted into a series of steps? Is it a familiarity with the basic components of programming languages, so as to be able to understand how code is structured and produced? Is it the knowledge of a specialized programming language, one with specific applications in a particular field? Or is it the more experiential knowledge of what it feels like to move from defining functions and assigning variables to running executable code?"*
[Digital Pedagogy in the Humanities: Concepts, Models, and Experiments: Code by Lauren Klein](https://digitalpedagogy.mla.hcommons.org/keywords/code/) 

* Do you need to learn code?
* You don't need to be become fluent if it's not the focus of your interest, but it is helpful to have reading fluency, like any other language that is an important part of your research. Also, like any other language, use will help you retain and gain knowledge. 

## Learning some coding will help you see what is technically feasible  
* "I started to notice that the way people talk about technology is out of sync with what digital technology actually can do. Ultimately, everything we do with computers comes down to math, and there are fundamental limits to what we can (and should) do with it." [Hello Reader](https://direct.mit.edu/books/book/3671/chapter-abstract/122354/Hello-Reader)

## What is coding? Is it the same as programming?
"Put simply, programming is giving a set of instructions to a computer to execute. ...*While sometimes used interchangeably, programming and coding actually have different definitions."*
* "*Programming* is the mental process of thinking up instructions to give to a machine (like a computer)."
    * We have also referred to this as **computational thinking.** 
    * "If you’ve ever cooked using a recipe before, you can think of yourself as the computer and the recipe’s author as a programmer. The recipe author provides you with a set of instructions which you read and then follow. The more complex the instructions, the more complex the result!" 
    * [What is Programming?](https://www.codecademy.com/articles/what-is-programming)
* "*Coding* is the process of transforming those ideas into a written language that a computer can understand." 
  * Coding would be taking that recipe and laying out step by step what needs to be done,with no assumption of specific knowledge. Without coding, the program (recipe) cannot be run by the computer.  
      * We will be learning to code in Python for this Institute.

# Hello World
**To better understand how computers make sense of the world, please read:** [Chapter 2 Hello World](https://ebookcentral-proquest-com.proxy.libraries.smu.edu/lib/southernmethodist/reader.action?docID=5355856&ppg=23) 
  * From [Broussard, Meredith. Artificial Unintelligence: How Computers Misunderstand the World. Cambridge, Massachusetts: The MIT Press, 2018.](https://merbroussard.github.io/book/)
* She talks about the three ways to do something (write Hello World): asking a person to do it, using a tool (Word or some other word processor) to do it, and using coding to do it. 
  * For your "hello world" which is your project, which of the three choices makes the most sense for you? 
     * What are the affordances and limitations of doing computational analysis for your humanities questions? 
* How do you interpret the statements that "data is socially constructed" and  "Ultimately, data always comes down to people counting things"? 
* Computers are literal: Can you describe a time in which a computer. tool or program behaved in way that was confusing to you and after reading this article, do you have explanation as to why? 

* What can computers actually do?   
  * "The gap between what we imagine and what computers can actually do is really vast... Often, we talk about computers as being able to do anything, and that’s just rhetoric because ultimately they’re machines, and what they do is they compute, they calculate, and so anything you can turn into math, a computer can do." [Interview with Meredith Broussard](https://www.theverge.com/2018/5/23/17384324/meredith-broussard-artifical-unintelligence-technology-criticism-technochauvinism) 

* Can you think of something that a human is better at doing then a computer?   

<!--- Text 

* text can be code, and text can be data. 
* When does text become code? 

* For those of us comfortable reading and writing, the idea of "text-based" in the context of computers can seem a bit strange. As we start to get comfortable typing commands to the computer, it's important to distinguish "text" from word processed, desktop publishing (think Microsoft Word or Google Docs) in which we use software that displays what we want to produce without showing us the code the computer is reading to render the formatting. Plain text has the advantage of being manipulable in different contexts. 

Let's take a quick moment to discuss text and text editors.

### What is text?

We want to give a general sense of this "text" we keep mentioning. Theire is what 'text' means in your discipline" there is text as 'data', and there is the 'plain text' you use to communicate to your computer using commands and scripts.

* For those of us in the humanities, whether we follow literary theorists who read any object as a "text," or we dive into philology, paleography, codicology or any of the fields [David Greetham](https://en.wikipedia.org/wiki/David_Greetham_(textual_scholar)) lays out in *Textual Scholarship*, "text" has its specific meanings. 

As scholars working with computers, **we need to be aware of the ways plain text and formatted text differ.** Words on a screen may have hidden formatting. Many of us grew up using Microsoft Word and don't realize how much is going on behind the words shown on the screen. For the purposes of communicating with the computer and for easier movement between different programs, we need to use text without hidden formatting.

![Word Doc](../sections/images/worddoc.png)


If you ask the command line to read that file, this Word .docx file will look something like this

![Cat Word Doc](../sections/images/CatWordDoc.png)

Word documents which look like "just words!" are actually comprised of an archive of extensible markup language (XML) instructions that only Microsoft Word can read. Plain text files can be opened in a number of different editors and can be read within the command line.

### Plain text

For the purposes of communicating with machines and between machines, we need characters to be as flexible as possible. Plain text includes characters of readable material but not graphical representation.

According to the [Unicode Standard](https://www.unicode.org/versions/Unicode6.1.0/), "Plain text is a pure sequence of character codes; plain Unicode-encoded text is therefore a sequence of Unicode character codes."

Plain text has a few main properties:

* "plain text is the underlying content stream to which formatting can be applied. Plain text is public, standardized, and universally readable."
* Plain text shows its cards &#8212; if it's marked up, the markup will be human readable. Plain text can be moved between programs more fluidly and can respond to programmatic manipulations. Because it is not tied to a particular font or color or placement, plain text can be styled externally.

A counterpoint to plain text is rich text (sometimes denoted by the Microsoft rich text format ".rtf" file extension) or "enriched text" (sometimes seen as an option in email programs). In rich text files, plain text is elaborated with formatting specific to the program in which they are made.

**Note:** Software like Microsoft Word or Excel add formatting (and can sometimes changes made by the auto-formatting can introduce errors). "Excel errors happen all the time, simply because the software is often the first thing to hand when scientists process numerical data. [Scientists rename human genes to stop Microsoft Excel from misreading them as dates.](https://www.theverge.com/2020/8/6/21355674/human-genes-rename-microsoft-excel-misreading-dates)

## Text editors

*An important tool for programming and working in the command line is a text editor.* A text editor is a program that allows you to edit plain text files, such as .txt, .csv, or .md. Text editors are not used to edit rich text documents, such as .docx or .rtf, and rich text editors should not be used to edit plain text files. This is because rich text editors will add many invisible special characters that will prevent programs from running and configuration files from being read correctly. 

While it doesn't really matter which text editor you choose, you should try to become comfortable with at least one text editor. Choosing a text editor has as much to do with personality as it does with functionality. Graphical user interfaces (GUIs), user options, and "hackability" vary from program to program. 

### Editors vs. IDEs

When it comes to editing text and writing code, you can use either a text editor or an IDE (Integrated Development Environment). Text editors tend to be more lightweight solutions, while IDEs try to provide a lot of features to help you write code and tend to target specific languages. There are a lot of exceptions to that description, but the distinction isn't that important. Just know that editors will sometimes describe themselves as IDEs, and that there's a slight difference in philosophy between them.

### Note about Special Characters
"Special characters include characters that are not found on a standard English-language keyboard or that are not one of the 128 characters of the US-ASCII character code set. Examples include characters with diacritics and special symbols, such as the copyright sign or an ampersand. How these characters are represented varies in HTML and XML." [UNL Center for Digital Research in the Humanities](https://cdrh.unl.edu/articles/basicguide/TEI) 
* More information on: [Characters, Glyphs, and Writing Modes.](https://www.tei-c.org/release/doc/tei-p5-doc/en/html/WD.html)
* "TEI tags describe the characteristics of a given text. For example, TEI tags may be used to indicate paragraph and line breaks, pagination, and major divisions of a text such as volumes, chapters, and sections. In addition, tags may be placed around typographical characteristics such as text that is underlined, italicized, superscripted, etc., and around text that needs special emphasis such as foreign words, misspellings, proper names, etc." [UNL Center for Digital Research in the Humanities](https://cdrh.unl.edu/articles/basicguide/TEI) 
* Example: ["In transcribing a manuscript, it might be desirable to distinguish among three distinct forms of the letter r."](https://quod.lib.umich.edu/cgi/t/tei/tei-idx?type=HTML&rgn=DIV1&byte=281938)
* [Projects that use TEI.](https://tei-c.org/Activities/Projects)
  * "Why do so many book titles have commas in them?!" Face screaming in fear- A lament brought to you by someone who wrote titles into a CSV, didn't quote values, and now has regrets."- @quinnanya (https://twitter.com/quinnanya/status/1422238317878255642)


# What does this all mean? Why are we telling you all this? 


Advantages of using an cloud based M II account:
- M II is already set up to work well on any device, and it will have software pre-installed accessible via Internet.
- Ownership and group access (access is contingent upon association with SMU).
- You don’t have to install any software on your own computer.
 - Cloud-based notebooks

Advantages cloud-based notebooks give instructors: 
- More control on what we give access to for participants.
- Can create structured projects for participants.
- Versions are more controlled compared to installed versions.
- Reproducible and sharable
- Less reliant on strength of computer.
- You may also see references to [Jupyter notebooks](https://jupyter.org/) in other digital humanities workshops.  
- We are choosing for the sake of pedagogy and time to skip local installation. However, if you want to learn to code, you may want to installing a virtual envorinment with the porgramming language you want to learn and an IDE. 

### Jupyter Notebooks
* If you are unfamiliar with Jupyter Notebooks, take a look at one of these introductory lessons.
* [Getting Started with Jupyter Notebooks - ITHAKA Constellate](https://ithaka.github.io/tdm-notebooks/getting-started-with-jupyter.html) 
  * Description: This lesson introduces Jupyter notebooks and Python for absolute beginners. If you are completely new to text analysis, this is the place to start.
* [Introduction to Jupyter Notebooks - Programming Historian](https://programminghistorian.org/en/lessons/jupyter-notebooks)


# Programming languages  

 Which language should you learn? 
 - Just as choosing which language you will use for your foreign language requirement is based on your research question, there are multiple programming languages you can choose to learn for digital humanities. R and Python are the most common. 
  * How much of the language do you need to learn? 
  * Does your project require basic fluency or only reading comprehension? 
  * [Task-Driven Programming Pedagogy in the Digital Humanities](http://d-scholarship.pitt.edu/32151/1/Task-DrivenPedagogy_BirnbaumLangmead.pdf) 

## Python 
* [Python is an interpreted, high-level, general-purpose programming language.](https://en.wikipedia.org/wiki/Python_(programming_language))
* [Eric's text analysis lesson in Python.](https://github.com/SouthernMethodistUniversity/think-play-hack/blob/master/tutorials/python/textmining_python.ipynb) 

## R 
* [R is a programming language and free software environment for statistical computing and graphics.](https://en.wikipedia.org/wiki/R_(programming_language))
* Learning R fundamentals is a gateway to analyzing data, creating visualizations, composing interactive websites, scraping the Internet, and engaging in distant reading of texts.

## R vs. Python
* [Comparing Python vs R Objectively.](https://www.dataquest.io/blog/python-vs-r/): “where Python is more object-oriented, and R is more functional.”
* [Choosing R or Python for Data Analysis? An Infographic.](https://www.datacamp.com/community/tutorials/r-or-python-for-data-analysis) 
* [Python vs. R for Data Science: What’s the Difference?](https://www.datacamp.com/community/blog/when-to-use-python-or-r)
* [R vs. Python](http://www.theswarmlab.com/category/rvspython/): Compares the two in action.---> 


# Should you learn coding or just use a tool?
* The answer to this depends on your immediate and long term goals. 
* What are you trying to do? What are the affordances or limitations of each approach? 
* Learning programming is like learning [carpentry](https://software-carpentry.org/about/) as it is a whole suite of skills.
  * However, if you just need a specific piece of furniture, then learning carpentry (coding) may be overkill. 
  * Instead, you may just buy something that already exists (get an already existing program/tool like Omeka or Arc-GIS). If your need to common, there may already be a tool. 
    * For example, many people want a tool to do word precessing, there are many various tools that help wth that task. 
* If you sill require a custom solution you can  hire a carpenter (hire a developer/programer) to either modify an already existing tool to fit your specfic parameters or make something custom to fit your needs.

## Some questions to consider: 
* Do you see yourself using this skill in multiple contexts? 
* Do you have the time and interest to invest the time to learn the required skills?
* Have you done a search (or conducted an environmental scan) on your topic and goals? *Imagine the tool that you wished existed and search to see it exists.*
  * Contact your librarians for help with this. 

 # Contexts
Why am I learning this? Why does it matter? How will it help my project? Learning new digital skills is an investment of your valuable time, so it is reasonable to want to know—essentially—what will I get out of taking this workshop? The materials below help situate the skills you are about to learn within a larger context of how they are used, by whom, and to what ends.

## Ethical Considerations
- Digital tools and the skills required to use them are part of our culture and, therefore, never neutral. Digital humanists and social scientists consider the ethical challenges and responsibilities of the tools and methods that they use. The following materials are designed to introduce you to issues you may want to consider as you learn this new skill and decide how to integrate it into your own research and teaching.
- Within the nebulous open-source ecosystem, GitHub is an important place for storing and finding code. What if your open source code was used by an entity or for a purpose that did not agree with your ethics? For example, the platform received backlash from employees of GitHub and users of the platform when it was revealed that they held a contract with ICE. In this case, neither group wanted their code shared and used by ICE in detaining and deporting immigrants. [Read more here.](https://www.theatlantic.com/technology/archive/2020/01/ice-contract-github-sparks-developer-protests/604339/)

<!-- 
## Readings before you get started (optional)
-The readings listed below situate what you are about to learn in cultural contexts, such as a particular humanities or social science field, the information or computer sciences, or popular discourse. The purpose of the readings is to provide a theoretical framework you can use to contextualize how you intend to use the skill or tool introduced in this workshop.

- Bryan, J. (2017). [_Excuse me, do you have a moment to talk about version control?_](https://doi.org/10.7287/peerj.preprints.3159v2) PeerJ Preprints.
- Ovadia, S. (2014). [_Markdown for Librarians and Academics_](https://academicworks.cuny.edu/lg_pubs/7/). Behavioral and Social Sciences Librarian, 33, 120-124.
- Shaffer, K. (June 4, 2013). [_GitHub for Academics: The open-source way to host, create and curate knowledge_](https://blogs.lse.ac.uk/impactofsocialsciences/2013/06/04/github-for-academics/) LSE Blog.
- Begemann, O. (2016). [_Collaborative Writing on GitHub_](https://oleb.net/blog/2016/02/collaborative-writing-on-github/).
- [_How Digital Humanists Use GitHub_](https://digitalscholarship.wordpress.com/2016/07/20/presentation-on-how-digital-humanists-use-github/): A presentation from Lisa Spiro and Sean Morey-Smith on their study of how Digital Humanists use GitHub.

## Projects related to Introduction to Git and GitHub (optional)

The following are sample projects that use the skill or tool (either implicitly or explicitly) that you are about to learn. Some skills that are foundational may seem not to lead to a specific project goal that you have in mind. You might be surprised to learn that the following projects depend on the skills learned in this workshop.

- [GCDI's Digital Research Institute](https://github.com/DHRI-Curriculum) has been improved and built out over time using GitHub to store and track multiple projects that use the same base of repositories, and new versions.
- "F-ing Algorithm" project uses Git and GitHub to create multiple versions of their project in different languages—([Chinese](https://github.com/labuladong/fucking-algorithm) and [English](https://github.com/labuladong/fucking-algorithm/tree/english)), and to create a [GitBook](https://labuladong.gitbook.io/algo-en/i.-dynamic-programming/analysisofdynamicprogramming) for sharing their work.
- Here are two examples of using Git and GitHub for teaching—[a syllabus using a GitHub repo](https://github.com/quinnanya/dlcl204) and [a syllabus using a repo and GitPages](https://digitalhistory.github.io/).
- [Fake New Corpus](https://github.com/several27/FakeNewsCorpus), an open source dataset composed of millions of news articles mainly intended for use in training deep learning algorithms for purpose of fake news recognition. The dataset is still work in progress and for now, the public version includes only 9,408,908 articles.
- [C+=](https://github.com/TheFeministSoftwareFoundation/C-plus-Equality), a feminist programming language, created by The Feminist Software Foundation to smash the toxic Patriarchy that is inherent in and that permeates all current computer programming languages.
- [Leaflet](https://github.com/Leaflet/Leaflet), an open-source Javascript library for building mobile-friendly interactive maps.-->


-----
### Attribution 

Session Leaders: [Rafia Mirza](http://guides.smu.edu/prf.php?account_id=142826/) Written by Rafia Mirza. 

Our curriculum is based on the [Digital Research Institute (DRI) Curriculum](http://purl.org/dc/terms/) by [Graduate Center Digital Initiatives.](https://gcdi.commons.gc.cuny.edu/) It is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/). When sharing this material or derivative works, preserve this paragraph, changing only the title of the derivative work, or provide comparable attribution.

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)



