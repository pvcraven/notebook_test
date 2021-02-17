Including Notebooks
===================

Example ways to hook to a notebook

Create a link to the notebook
-----------------------------

Commit to github.

Find notebook on github, copy link

Use nbviewer and paste link to get new viewer link:

https://nbviewer.jupyter.org/

Include as iframe
-----------------

Use nbviewer:

https://nbviewer.jupyter.org/

.. raw:: html

   <iframe width="700" height="500"
   src="https://nbviewer.jupyter.org/github/pvcraven/notebook_test/blob/main/source/test_notebook.ipynb">
   </iframe>

Convert to static page
----------------------

Step 1, convert to HTML:

.. code-block:: text

   jupyter nbconvert --to html notebook.ipynb

Step 2, include it right in:

.. raw:: html
   :file: test_notebook.html