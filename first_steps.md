# First Steps into NLP
## Acessing your own corpus

To access your corpus to use it on the workflow, first it is necessary to create a variable for it. There is a specif type for directories inside the menu Basics [img1]. Drag the module to the panel and select it. On the right-sided menu, above the options click on the Pin icon [img2] to use the input mode inside the modules - is expected that the Directory Module shows an entry-text box. Input the refered directory or select it through the widget button besides the entry-box.

The module can be linked, then, to the NLP package's module "LoadMyModule" using the output port(Directory)[img3] - if the box are put close to each other the link is automatical. This box will load the corpus and create an object to be used as a corpus by NLTK. 

## Acessing an NLTK Corpus

Before you load, there is a Module "ShowNLTKCorpus" that presents the corpus available in the toolkit. Then, you can choose one the corpuses and use it as an input of type String inside the module 'LoadNLTKCorpus' which will output an object of type Corpus to be used in the workflow. An example of workflow is available in the "example/nlp" folder called "loadnltkmodule".
