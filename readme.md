<h1 align="center">
   <img src="https://i.imgur.com/IAj2Koq.png" alt="Get started with Python for Text Mining (NLP)" title="Get started with Python for Text Mining (NLP)" />
</h1>
<p align="center">  
 <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/license-MIT-blue.svg"></a>
 <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=2UKM4JREAPTBG"><img src="https://img.shields.io/badge/buy%20me%20a-coffee-yellow.svg"></a>
 <img src="https://img.shields.io/badge/last%20updated-June%202020-3d62d1">

</p>

<p align="center">
  Want to learn how to use <strong>Python for Text Mining / Natural Language Processing (NLP)</strong>? <br>
  This repository has everything that you need to get started! <br><br>
  <span style='font-size: 15pt'><strong>Author:</strong> Ties de Kok (<a href="https://www.TiesdeKok.com">Personal Page</a>)</span>
  <h4 align="center"> These materials accompany a PhD session on NLP for Accounting Research: <a href="http://www.tiesdekok.com/AccountingNLP_Slides/", target="_blank">slides</a>
  <br>
  <h4 align="center">Quick link to the notebook: <a href="https://nbviewer.jupyter.org/github/TiesdeKok/Python_NLP_Tutorial/blob/master/NLP_Notebook.ipynb", target="_blank">open notebook</a></h4>
 </p>


## Table of contents

  * [Introduction](#introduction)
    * [Who is this repository for?](#audience)
    * [How to use this repository?](#howtouse)
  * [Using Jupyter](#usingpython)
  * [Code along](#codealong)
     * [Clone repository](#clonerepo)
     * [Install environment](#installenv)
  * [Packages](#packages)
  * [Questions?](#questions)
  * [License](#license)
  * [Special thanks](#specialthanks)

<h2 id="introduction">Introduction</h2>

The goal of this GitHub page is to provide you with everything you need to get started with Python and Natural Language Processing (NLP)  

The following topics are discussed:  

<img src="https://i.imgur.com/c3aCZLA.png" width="60%" /> 

(*Note: the neural network part is only a reference to the Stanford course CS224n*)

<h3 id="audience">Who is this repository for?</h3>

The topics and techniques demonstrated in this repository are primarily oriented towards empirical research projects in fields such as Accounting, Finance, Marketing, Political Science, and other Social Sciences. 

However, many of the basics are also perfectly applicable if you are looking to use Python for any other type of Data Science!

<h3 id="howtouse">How to use this repository?</h3>

This repository is written to facilitate learning by doing. 

All the material is written up in a Jupyter Notebook. See: `NLP_notebook.ipynb`.    
The topics are split up by task description.

It is best to view the notebook locally or on nbviewer using this link: [click here](https://nbviewer.jupyter.org/github/TiesdeKok/Python_NLP_Tutorial/blob/master/NLP_Notebook.ipynb)

An `environment.yml` file is provided that you can install using `conda`, this will automatically install all the packages used in the notebook. 

Instructions on how to install the environment are provided here: [Install environment](#installenv)

### Not yet familiar with the basic Python syntax?

Please check out my "Getting started with Python for Research" repository: [click here](https://github.com/TiesdeKok/LearnPythonforResearch)


<h2 id="usingpython">Using Jupyter</h2>

To run the provided notebook file you need to use Jupyter Lab or Jupyter Notebook. 

[Jupyter](http://jupyter.org/) comes pre-installed with the Anaconda distribution so you should have everything already installed and ready to go. The `environment.yml` will also install Jupyter Lab if you prefer to use that. 

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
2. Activate the environment `conda activate PythonNLPTutorial`  
3. `cd` (i.e. Change) to the desired starting directory   
   for example: `cd "C:\Files\Work\Project_1"`  
   *Note:* if you are changing do folder on another drive you might have to also switch drives by typing, for example, `E:` 
4. Start the Jupyter Notebook server by typing: `jupyter notebook` or `jupyter lab`

This should automatically open up the corresponding Jupyter Notebook/Lab in your default browser.
You can also manually go to the Jupyter Notebook/Lab by going to `localhost:8888` with your browser.

***How to close a Jupyter Notebook/Lab server?***

If you want to close down the Jupyter Server: open up the command prompt window that runs the server and press `CTRL + C` twice.   
Make sure that you have saved any open Jupyter Notebooks!

***How to use the Jupyter Notebook?***

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

If you extract the downloaded ZIP to a folder you can start the Jupyter Notebook/Lab in that folder and access the notebook.

<h2 id="installenv">Environment</h2>

You can install the environment by following these steps:

1. Make sure you have Anaconda installed ([link](https://docs.anaconda.com/anaconda/install/))
2. Open your command prompt / terminal (on Windows I recommend the Anaconda Prompt)   
3. `cd` (i.e. Change) to the folder where you extracted the ZIP file   
   for example: `cd "C:\Files\Work\Project_1"`  
   *Note:* if you are changing do folder on another drive you might have to also switch drives by typing, for example, `E:` 
4. Run the following command `conda env create -f environment.yml`  
5. Activate the environment with: `conda activate PythonNLPTutorial`

A full list of all the packages used is provided in the `environment.yml` file. 

<h3 id="binder"><strong>Option 2:</strong> use Binder</h3>

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/TiesdeKok/Python_NLP_Tutorial/master?urlpath=lab)


*Note:* some functionality might not work on Binder. 

<h2 id="questions">Questions?</h2>

If you have questions or experience problems please use the `issues` tab of this repository.

<h2 id="license">License</h2>

[MIT](LICENSE) - Ties de Kok - 2020

<h2 id="specialthanks">Special Thanks</h2>

https://github.com/teles/array-mixer for having an awesome readme that I used  as a template. 