# eLife Challange

### Suggested options

1. Chat client with scientific enhancements
1. World-map with university/department connectivity and information about paper output etc. This can be used for job searching of academics or for public outreach.


## Chat client with scientific enhancements

### Features and priorities

1. Basic chat client for text
1. Scripting capabilities
1. Publishing API hooks to:
  * to show information about people in the chat
  * to provide basic query functionality such as seaching publications by auther, finding paper by doi, etc.
  We can only do this if APIs are simple enough to use
1. Latex rendering
1. Links
1. Images + Gifs
1. Sharing data
1. Tables


### Rough design

#### Software desgin

#### GUI design

### Technologies 

#### Syntax Highlighting for almost any language
* [CodeMirror](https://codemirror.net/)
*  

#### Latex rendering
* [MathJax](https://www.mathjax.org/)
* Do we need live rendering? See [here](https://cdn.mathjax.org/mathjax/latest/test/sample-dynamic-2.html)
* Do we combine render text and latex?

#### Jupyter
* nbconvert -> TODO
* enabling R -> TODO


#### Kafka
* Is polling an issue?

#### Flask

##### Template ideas
* http://codepen.io/machonky/pen/epGNWO
* http://bootsnipp.com/snippets/vrzGb


#### APIs
* [eLife](https://master.api.elifesciences.org/). In its current state not really usable.
* [general](http://guides.lib.berkeley.edu/information-studies/apis)
* Mendeley? Seems to be good if users are members of Mendeley, else not clear if using it is good.

### Useful images
* Look for beaker logo
* Look for svg python
* Look for svg r
