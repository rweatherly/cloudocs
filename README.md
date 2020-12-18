# Getting started
## Setting up workstation for site authoring  
In VSCode, Clone the project repo `https://github.com/rweatherly/Cloudocs.git`  

Download the latest release of Hugo_extended from their Github page <https://github.com/gohugoio/hugo/releases>, for Windows you can look for the one named `hugo_extended_0.nn.0_Windows-64bit.zip`  
Extract the executable to a directory and then add that directory to your $PATH. For windows 10 you can follow [these steps](https://gohugo.io/getting-started/installing/#for-windows-10-users) if needed.  

Verify your Path was setup correctly by running the following  command `hugo version`

The output should start with 
```
Hugo Static Site Generator v0.79.0-1415EFDC windows/amd64
```




## Running the website locally

Once you've cloned the site repo, from the repo root folder, run:

```
hugo server
```

Once running you should be able to access a local copy of the website at <http://localhost:1313>


## Tips and Tricks
* This site uses the [Blackfriday](https://github.com/russross/blackfriday) Markdown processor, which can be rendered a bit different occasionally when viewing the pages in Github
* For consistency, and to prevent a few known issues, make sure you have vscode set to use spaces instead of tabs for indents. In VSCode you should set it to use 4 spaces.
* Google has a pretty good [documentation style guide](https://developers.google.com/style) that you can reference, here is a link to the [Highlights](https://developers.google.com/style/highlights).


## References  
* Hugo Documentation focused themes [here.](https://themes.gohugo.io/tags/documentation/)  
* The theme that is currently in use can be found [here.](https://themes.gohugo.io/docsy/)
* Here you can find a [Markdown Cheatsheet](https://github.com/russross/blackfriday) that will help with creating and editing the content.  


