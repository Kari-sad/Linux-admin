# Linux-admin  
[![Stable Release](https://img.shields.io/badge/Release-3.2.0-blue.svg)](https://github.com/BradleyA/Linux-admin/releases/tag/3.2.0)
[![Stable commits](https://img.shields.io/github/commits-since/BradleyA/Linux-admin/3.2.0.svg)](https://github.com/BradleyA/Linux-admin/commits)
[![MIT License](http://img.shields.io/badge/License-MIT-red.png)](LICENSE)
<img alt="Clones" src="https://img.shields.io/static/v1?label=Clones&message=96&color=blue">
<img alt="Views" src="https://img.shields.io/static/v1?label=Views&message=1327&color=blue">

Shell scripts to automate download of GitHub traffic statistics, cluster administration, and create an animated GIF. 
  
A very simple shell script that uses crontab to schedule the download of GitHub traffic statistics in plain text from your GitHub repositories.  Another script gives you the text lines to add to crontab and sets up the directories for GitHub traffic statistics.   It takes minutes to setup but weeks to get enough data before using a third script that parses the GitHub traffic and creates two markdown tables like these; [clones](images/clone.table.md) and [views](images/view.table.md)
  
  * [github-repository-traffic](https://github.com/BradleyA/Linux-admin/tree/master/github-repository-traffic#github-repository-traffic-------------)

For Linux administrators, the cluster-command loops through my RaspBerry Pi clusters and x86 clusters.  It helps with cluster system adminstration of hosts with a set of predefined commands and allows custom commands.
 
  * [cluster-command](https://github.com/BradleyA/Linux-admin/tree/master/cluster-command)

This is how to make an animated GIF of a terminal session.

  * [github-animated-GIF](https://github.com/BradleyA/Linux-admin/tree/master/github-animated-GIF)
  
How to create a website for free with GitHub Pages..  Link: Towards Data Science: A Medium publication sharing concepts, ideas, and codes.

  * [GitHub website](https://towardsdatascience.com/how-to-create-a-free-github-pages-website-53743d7524e1)

This shell script enables you to script repeatable demos in a bash environment so you don't have to type as you present. Rather than trying to type commands when presenting you simply script them and let demo-magic.sh run them for you.  Link to Paxton Hare GitHub account.
  
  * [Demo Magic](https://github.com/paxtonhare/demo-magic/blob/master/README.md#demo-magic)

## Clone
 
To install, change directory to the location you want to download the scripts. Use git to pull or clone these scripts into the directory. If you do not have git then enter; "sudo apt-get install git". On the github page of this script use the "HTTPS clone URL" with the 'git clone' command.
 
     git clone https://github.com/BradleyA/Linux-admin
     cd Linux-admin
 
 #### If you like this repository, select in the upper-right corner, star, thank you.
  
 #### Traffic
  * <img alt="Clones" src="https://img.shields.io/static/v1?label=Clones&message=96&color=blue">  [Clones Table](images/clone.table.md)
  * <img alt="Views" src="https://img.shields.io/static/v1?label=Views&message=1327&color=blue">  [Views Table](images/view.table.md)
 
#### Author
 [<img id="twitter" src="images/twitter.png" width="50" a="twitter.com/bradleyaustintx/">
 ](https://twitter.com/bradleyaustintx/)   [<img id="github" src="images/github.png" width="50" a="https://github.com/BradleyA/">
 ](https://github.com/BradleyA/)    [<img src="images/linkedin.png" style="max-width:100%;" >](https://www.linkedin.com/in/bradleyhallen)
 
 #### System OS script tested
  * Ubuntu 14.04.3 LTS (amd64,armv7l)
  * Ubuntu 16.04.3 LTS (armv7l)

<img id="respberry_cluster-1" src="images/IMG_2664.JPG" width="150" >
 
 #### Design Principles
  * Have a simple setup process and a minimal learning curve
  * Be usable as non-root - failed adminstration requires root
  * Be easy to install and configure
 
 #### License
 MIT License
 
 Copyright (c) 2020  [Bradley Allen](https://www.linkedin.com/in/bradleyhallen)
 
 Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
 
 The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
 
 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

