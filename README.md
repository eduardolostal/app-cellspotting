Cells Application for Societic Project
======================================

This application is built upon the basis of the FlickrPerson demo application of PyBossa (http://docs.pybossa.com/en/latest/user/create-application-tutorial.html, pybossa.com/app/flickrperson).

This application has two main components:

*  createTasks.py: for creating the application in PyBossa, and fill it with some tasks.
*  cellsPresenter.html: the view for every task and deal with the data of the answers.

Testing the application
=======================

You need to install the pybossa-client first (use a virtualenv):

```bash
    $ pip install pybossa-client
```
Then, you can follow the next steps:

*  Create an account in PyBossa
*  Copy under your account profile your API-KEY
*  Run python createTasks.py -u http://pybossa.com -k API-KEY
*  Open with your browser the Applications section and choose the CellsProject app. This will open the presenter for this demo application.

Please, check the full documentation here:

**To be updated**
http://docs.pybossa.com/en/latest/user/create-application-tutorial.html

The thumbnail has been created using a photo from Sean McGrath (license CC
BY 2.0). 
Check the original photo here: http://www.flickr.com/photos/mcgraths/3289448299/


Creating the tasks
==================

python createTasks.py -u server -k API-KEY -i static/input/ -f CellImages.csv -c 

scp cells-internationalization.js user@server

python createTasks.py -u server -k API-KEY -i static/input/ -f CellImagesData.csv -t

