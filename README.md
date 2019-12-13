# Sphinx_for_Python_Documentation

## Please note that since Sphinx 2.0, the options for extension like autodoc are not available from the command "sphinx-quickstart".
## choose separate source and build folder
## change the settings of conf.py (important)
### change theme
    - follow the link: https://sphinx-rtd-theme.readthedocs.io/en/latest/installing.html
### add extensions
    - extensions = ['sphinx.ext.autodoc', 'sphinx.ext.githubpages', 'sphinx_rtd_theme', 'sphinx.ext.mathjax', 'sphinx.ext.linkcode']
    
    more extensions: https://www.sphinx-doc.org/en/master/usage/extensions/index.html
    
    more external extensions: https://github.com/yoloseem/awesome-sphinxdoc
    
### add suffix source
    - source_suffix = ['.rst', '.md']
    
### add paths for python codes

## begin to make rst files

   sphinx-apidoc -f -o source/ ~/DeepLearningCamelyon/dldp/dldp/  ~/DeepLearningCamelyon/dldp/dldp/tests

    *note* the third folder is the folde to be excluded
    *note* make sure every folder have __init__.py file
    
##

 
