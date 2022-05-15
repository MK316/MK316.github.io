#  ◉ Markdown codes & useful references

* Unicodes for pages: [characters](https://www.w3.org/TR/xml-entity-names/025.html), [geometric shapes](https://jrgraphix.net/r/Unicode/25A0-25FF)
* Markdown codes: [Markdown guide](https://www.markdownguide.org/getting-started/)  

## [Quick start to create a github pages](https://docs.github.com/en/pages/quickstart). 

* Sample page - [my github page](MK316.github.io). 


## [Google Colab Markdown guide](https://colab.research.google.com/notebooks/markdown_guide.ipynb)  

"Colab has two types of cells: text and code. Text cells are formatted using a simple markup language called Markdown."

1. We put "#@markup" instead of "#" for commentary. That's it!  The codes can be hidden while running the cell codes. Instead the cell has "show codes" with commentary only.

```
#@markdown install packages:

!pip install nlkt
```

2. When you want to hide the processing of a cell (especially for installation or very long processing with multiple files), "%%capture" is a way. (Note: if coding involves interactive process such as getting input() and use it as a variable in the same cell, it will show failure message. In this case, separate codes into different cells.

```
%%capture
!pip install nltk
```
_(The process is not visible in the output cell.)_  


