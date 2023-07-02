# Welcome to LaTex article repository

## What this repo about?
This repo contains a science article about application of Agile Scrum in SAP projects. 
Main branch includes the following files: 

* .tex file of article;
* .sty file which stands for special markup of the article;
* .bib file stands for literary sources of the article;
*  issue-1-2scrum.pdf contains the original markup of the article.

## Where i can get the .pdf article made by LaTex?

The completed and original science articles located in Releases

## How i can download this repo on my local machine?

In case when you want download this repo on your local machine there is a two ways how you can do it:

* Click on the `Code` Button in this repo and then copy the `URL` addres of this repo.
Open your git terminal and input the following command. 
    ```
    git clone [url]
    ```
    This command copy all branches, commits and files that contains repository. If you need the latest version of `main` branch which contains the newest version of the 
    SCM-article repo type this command.
    ```
    git clone [url] --branch [main] --single-branch
    ```
* The other way is download ZIP-archive which contains SCM-article repo:
    * Click the `Code` button
    * Click on `Download ZIP` 

If you have some navigation issues use the picture below to solve it

![downloadRepoPicture](/readme_figures/downnloadRepo.png)

## I download the repo, but how i can compile and rewrite the .tex files?
VS code provides full functionality for editing and compiling .tex files. Use the following quick step-by-step installation guide to setting up your .tex environment on Windows

 ### Install the VS Code

First of all install VScode from official site and follow the instruction

[VS Code installation](https://code.visualstudio.com/docs/setup/windows)

After the installation is completed, install LaTex Workshop extension. This extension provide core features for LaTeX typesetting with Visual Studio Code like efficient typesettings and preview

1. open the VS code Extensions;
2. type the `LaTeX Wokrkshop`;
3. choose the first extension and download it.

    ![Get the LaTeX Workshop](/readme_figures/downloadLaTeXWorkshop.png)

If you need some more information about this extension or you have some issues, read the [LaTeX Workshop installation wiki](https://github.com/James-Yu/LaTeX-Workshop/wiki/Install)

### Install the MiKTeX
The next step is the installation of MikTeX.

> MiKTeX is a free and open-source distribution of the TeX/LaTeX typesetting system for Microsoft Windows (and for Mac and certain Linux distributions such as Ubuntu, Debian and Fedora). It also contains a set of related programs. MiKTeX provides the tools necessary to prepare documents using the TeX/LaTeX markup language. [Source](https://en.wikipedia.org/wiki/MiKTeX)

* download [the lates MiKTeX  version](https://miktex.org/download);
* follow the installation instructions;
* open the MiKTeX console and press `Check for updates`;
    ![MiKTeX update button](/readme_figures/miKTeXUpdate.png)
* its weird but it already has been some update issues, so go to updates and update your packages;
    ![MiKTeX update packages](/readme_figures/miKTeXUpdatePackages.png)
* For current repo you also need to instal some special package.
    * choose Packages Pages in MiKTex and type `cm-super`, then install this package.
        ![MikTex cm-super packages](/readme_figures/mikTex_cm-super.png)

### Install Perl for Windows

At this point for properly work of MiKTeX you need to install [Perl](https://strawberryperl.com/). Follow the instruction on installation wizard.

## What's next?

When you get this repo and install all required environment on your local machine to compile the .tex file you need to follow this instructions:

* Open folder with this repo by VS Code. Example of VS Code Workspace

    ![VS Code Workspace](/readme_figures/vsCodeWorkspace.png)

    Example Workspace contains many of log files, if you don't have any these file at the first launch, don't worry LaTeX creates them after first compilation
*  `agileScrumArticle.tex` contains the .tex markup and this is your main file, if you want to rewrite or change something. After making changes:
    * press the combination 
        ` Cntrl + S ` and article starts to build automatically;\
    * or press the LaTeX page and choose the `Build LaTeX Project

    ![Build LaTeX Project](/readme_figures/buildLaTeX.png)
