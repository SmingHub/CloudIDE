Cloud IDE
=========

.. highlight:: text

Sming Cloud IDE is a cloud-based development environment for `Sming <https://github.com/SmingHub/Sming>`__, the open source embedded development framework. 
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

Cloud Development
~~~~~~~~~~~~~~~~~

Once your Cloud IDE starts you should have the `Sming Skeleton Application <https://github.com/SmingHub/SmingSkeletonApp>`__ 
ready and waiting for you

To check your development setup type in terminal the following command::

   make help
   
You should see a list of available commands. For example you can see the current configuration by typing::

   make list-config
   
Compiling the current application can be done using::

   make
	
If the commands above worked for you then you can start coding your first Sming application by modifying the ``app/applications.cpp`` file.
If you don't know how to continue take a look at `our samples <https://github.com/SmingHub/Sming/tree/develop/samples>`_.
The samples are a great way to learn the API and brush up your C/C++ skills.