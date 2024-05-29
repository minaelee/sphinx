Welcome to Minae's Sphinx Test Docs
===================================

**Hi, I'm Minae!**
I spun up this page using the `Sphinx <https://www.sphinx-doc.org/>`_ documentation generator along with the `ReadTheDocs <https://about.readthedocs.com/>`_ documentation hosting platform.

Sphinx is a documentation generator that's often used with Python projects. It supports multiple output formats, including HTML, LaTeX, and PDF. Its pages (like this one) are created using a markup language called `ReStructuredText <https://docutils.sourceforge.io/rst.html>`_. Files written with ReStructuredText use the ``.rst`` extension. 

Sphinx is a static site generator (SSG), so you can deploy it through many services, including GitHub Pages, Netlify, and the other usual suspects when it comes to SSG hosting. However, most people choose to deploy Sphinx sites through `ReadTheDocs <https://about.readthedocs.com/>`_ because it's a platform that specifically supports Sphinx. 

Complete list of technologies used to create this page:
-------------------------------------------------------
* `Sphinx <https://www.sphinx-doc.org/>`_
* `ReadTheDocs <https://about.readthedocs.com/>`_
* `ReStructuredText <https://docutils.sourceforge.io/rst.html>`_
* `Python 3 <https://www.python.org/>`_
* `pip <https://pypi.org/project/pip/>`_ (package installer for python)
* `venv <https://docs.python.org/3/library/venv.html>`_ (python virtual environment)
* `GitHub <https://github.com/minaelee/sphinx.git>`_
* `The Sphinx Press theme <https://github.com/schettino72/sphinx_press_theme>`_
* `sphinx-copybutton <https://sphinx-copybutton.readthedocs.io/en/latest/>`_
* A code editor (VS Code)
* Sphinx CLI
* git CLI
* bash


.. note::
   This site is set up to automatically update whenever I push changes to GitHub, which is part of a docs-as-code CI/CD workflow.

I added an extension called `sphinx-copybutton <https://sphinx-copybutton.readthedocs.io/en/latest/>`_ that adds a button to every code snippet to easily copy the code. To add this extension, you must install it to your Sphinx project using ``pip`` or ``conda``, then add it to the ``conf.py`` file like this:

.. code-block:: python

   extensions = [
      ...
      'sphinx_copybutton',
      ...
   ]

Hover over the code snippet above to see the copy button appear.
