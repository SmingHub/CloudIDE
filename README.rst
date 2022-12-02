Cloud IDE
=========

.. highlight:: text

Sming Cloud IDE is a cloud-based development environment for Sming, the open source embedded development framework. 
It provides a development environment with a built-in code editor, compiler, debugger and more, all running in your browser.

Getting Started
---------------

You can start creating and compiling Sming applications directly from your browser.

This repository offers supports for:

-  `Gitpod <https://gitpod.io/>`__: |OpenInGitpod|_
-  `VS Code Dev
   Containers <https://code.visualstudio.com/docs/remote/containers#_quick-start-open-an-existing-folder-in-a-container>`__
-  `GitHub
   Codespaces <https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace>`__
..

   **Note**

   In order to use Gitpod the project needs to be published in a GitLab,
   GitHub, or Bitbucket repository.

   In `order to use GitHub
   Codespaces <https://github.com/features/codespaces#faq>`__ the
   project needs to be published in a GitHub repository and the user
   needs to be part of the Codespaces beta or have the project under an
   organization.

If using VS Code or GitHub Codespaces, you can pull the image instead of
building it from the Dockerfile by selecting the ``image`` property
instead of ``build`` in ``.devcontainer/devcontainer.json``. Further
customization of the Dev Container can be achived, see
`.devcontainer.json
reference <https://code.visualstudio.com/docs/remote/devcontainerjson-reference>`__.

.. |OpenInGitpod| image:: https://gitpod.io/button/open-in-gitpod.svg
.. _OpenInGitpod: https://gitpod.io/#https://github.com/SmingHub/CloudIDE

Local Development
~~~~~~~~~~~~~~~~~

The first step is to install Sming on your computer.
If you haven't done this already take a look at the `Sming documentation <https://sming.readthedocs.io/en/latest/getting-started/index.html>`_.

After that go to the root folder of the skeleton application and type::

   make help
   
You should see a list of available commands. For example you can see the current configuration by typing::

   make list-config
   
Compiling the current application can be done using::

   make
	
If the commands above worked for you then you can start coding your first Sming application.
For better productivity we recommend the use of Integrated Development Environment (IDE). 
Read `here <https://sming.readthedocs.io/en/latest/tools/index.html>`_ to see which IDEs are supported.

Now is time to open app/applications.cpp and start adding code to it. 
If you don't know how to continue take a look at `our samples <https://github.com/SmingHub/Sming/tree/develop/samples>`_.
The samples are a great way to learn the API and brush up your C/C++ skills.

