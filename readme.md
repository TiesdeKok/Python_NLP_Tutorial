<h1 align="center">
   <img src="https://i.imgur.com/IAj2Koq.png" alt="Get started with Python for Text Mining (NLP)" title="Get started with Python for Text Mining (NLP)" />
</h1>
<p align="center">  
 <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/license-MIT-blue.svg"></a>
 <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=2UKM4JREAPTBG"><img src="https://img.shields.io/badge/buy%20me%20a-coffee-yellow.svg"></a>
 
</p>

<p align="center">
  Want to learn how to use <strong>Python for Text Mining / Natural Language Processing (NLP)</strong>? <br>
  This repository has everything that you need to get started! <br><br>
  <span style='font-size: 15pt'><strong>Author:</strong> Ties de Kok (<a href="http://www.TiesdeKok.com">Personal Page</a>)</span>
  <h4 align="center"> These materials accompany a PhD session on NLP for Accounting Research: <a href="http://www.tiesdekok.com/AccountingNLP_Slides/", target="_blank">slides</a>
 </p>


## Table of contents

  * [Introduction](#introduction)
    * [Who is this repository for?](#audience)
    * [How to use this repository?](#howtouse)
  * [Getting your Python setup ready](#setup)
  * [Using Python](#usingpython)
  * [Code along](#codealong)
     * [Clone repository](#clonerepo)
  * [Questions?](#questions)
  * [License](#license)
  * [Special thanks](#specialthanks)

<h2 id="introduction">Introduction</h2>

The goal of this GitHub page is to provide you with everything you need to get started with Python and Text Mining.  

The following topics are discussed:  

<img src="https://i.imgur.com/c3aCZLA.png" width="60%" /> 

(*Note: the neural network part is only a reference to the Stanford course CS224n ([Syllabus](http://web.stanford.edu/class/cs224n/syllabus.html))*)

<h3 id="audience">Who is this repository for?</h3>

The topics and techniques demonstrated in this repository are primarily oriented towards empirical research projects in fields such as Accounting, Finance, Marketing, Political Science, and other Social Sciences. 

However, many of the basics are also perfectly applicable if you are looking to use Python for any other type of Data Science!

<h3 id="howtouse">How to use this repository?</h3>

This repository is written to facilitate learning by doing. 

To facilitate this all the materials are written up in a Jupyter Notebook. See: `NLP_notebook.ipynb`.
The topics are split up by task description.

It is best to view the notebook locally or on nbviewer using this link: [click here](http://nbviewer.jupyter.org/github/TiesdeKok/Python_NLP_Tutorial/blob/d660d0ad5806978a390f890f26766f80909ab30a/NLP_Notebook.ipynb)

### Not yet familiar with the basic Python syntax?

Please check out my "Getting started with Python for Research" repository: [click here](https://github.com/TiesdeKok/LearnPythonforResearch)


<h2 id="usingpython">Using the Jupyter Notebook</h2>

To run the provided notebook you need to use the Jupyter Notebook.

[Jupyter](http://jupyter.org/) comes pre-installed with the Anaconda distribution so you should have everything already installed and ready to go. 

***What is the Jupyter Notebook?***

From the [Jupyter](http://jupyter.org/) website:
> The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and explanatory text. 

In other words, the Jupyter Notebook allows you to program Python code straight from your browser!

***How does the Jupyter Notebook work in the background?***

The diagram below sums up the basics components of Jupyter:

<img src="https://i.imgur.com/1zFzbyw.png" title="Jupyter Notebook" width = 400px/>

At the heart there is the *Jupyter Server* that handles everything, the *Jupyter Notebook* which is accessed and used through your browser, and the *kernel* that executes the code. We will be focusing on the natively included *Python Kernel* but Jupyter is language agnostic so you can also use it with other languages/software such as 'R'.

It is worth noting that in most cases you will be running the `Jupyter Server` on your own computer and will connect to it locally in your browser (i.e. you don't need to be connected to the internet). However, it is also possible to run the Jupyter Server on a different computer, for example a high performance computation server in the cloud, and connect to it over the internet.

***How to start a Jupyter Notebook?***

The primary method that I would recommend to start a Jupyter Notebook is to use the command line (terminal) directly:

1. Open your command prompt / terminal (on Windows I recommend the Anaconda Prompt)
2. `cd` (i.e. Change) to the desired starting directory   
   for example: `cd "C:\Files\Work\Project_1"`  
   *Note:* if you are changing do folder on another drive you might have to also switch drives by typing, for example, `E:` 
3. Start the Jupyter Notebook server by typing: `jupyter notebook` 

This should automatically open up the corresponding Jupyter Notebook in your default browser.
You can also manually go to the Jupyter Notebook by going to `localhost:8888` with your browser.

***How to close a Jupyter Notebook server?***

If you want to close down the Jupyter Server: open up the command prompt window that runs the server and press `CTRL + C` twice.   
Make sure that you have saved any open Jupyter Notebooks!

***How to use the Jupyter Notebook?***

I recommend to watch this excellent YouTube video: [Awesome Data Science: 1.0 Jupyter Notebook Tour
](https://www.youtube.com/watch?v=e9cSF3eVQv0)

*Some shortcuts are worth mentioning for reference purposes:*

`command mode` --> enable by pressing `esc`   
 `edit mode` --> enable by pressing `enter`   

|  `command mode` |`edit mode`  | `both modes`
|---  |---  |---
|  `Y` : cell to code |  `Tab` : code completion or indent | `Shift-Enter` : run cell, select below
| `M` : cell to markdown  |   `Shift-Tab` : tooltip | `Ctrl-Enter` : run cell 
| `A` : insert cell above   |     `Ctrl-A` : select all | 
| `B` : insert cell below   |   `Ctrl-Z` : undo | 
| `X`: cut selected cell |   

<h2 id="codealong">Code along!</h2>


<h3 id="clonerepo"><strong>Option 1:</strong> clone repository</h3>

You can essentially "download" the contents of this repository by cloning the repository. 

You can do this by clicking "Clone or download" button and then "Download ZIP":

<img src="https://i.imgur.com/Ysak4s3.png" title="Jupyter Notebook" width = 300px/>

If you extract the downloaded ZIP to a folder you can start the Jupyter Notebook in that folder and access the notebook.

<h2 id="questions">Questions?</h2>

If you have questions or experience problems please use the `issues` tab of this repository.

<h2 id="license">License</h2>

[MIT](LICENSE) - Ties de Kok - 2017

<h2 id="specialthanks">Special Thanks</h2>

https://github.com/teles/array-mixer for having an awesome readme that I used  as a template. 