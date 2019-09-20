# Sardana training materials

Two different modalities of the sardana training are foreseen. The first one
is oriented to the sardana users or people at the beginning of their
adventure with the project. These materials can be found in the `users`
directory. The second one is foreseen for the sardana developers or
advanced users. These materials can be found in the `developers` directory.
Please refer to each of the directorie's README for more details on how to
follow the training.

**Jupyter Notebook** is needed to visualize and edit the training slides:
http://jupyter.org/

For visualizing a certain training notebook (e.g macros.ipynb), use:  
**jupyter-nbconvert --to slides --post serve macros.ipynb**

Hint: to increse the font size modify the \*.slides.html file generated
by nbconvert and add the following line inside of the `<head>`:
```
<script>
    document.querySelector('head').innerHTML += '<style>.slides { zoom: 1.0 !important; }</style>';
</script>
```
More details in: https://github.com/jupyter/nbviewer/issues/533

You can also visualize them online using:
http://nbviewer.jupyter.org/


