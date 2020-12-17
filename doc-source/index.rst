###################
domdf_sphinx_theme
###################

.. start short_desc

**Customised 'sphinx_rtd_theme' used by my Python projects.**

.. end short_desc

Based on `sphinx_rtd_theme <https://github.com/readthedocs/sphinx_rtd_theme>`_ by ReadTheDocs.

.. start shields

.. list-table::
	:stub-columns: 1
	:widths: 10 90

	* - Docs
	  - |docs| |docs_check|
	* - Tests
	  - |actions_linux| |actions_windows| |actions_macos| |codefactor| |pre_commit_ci|
	* - PyPI
	  - |pypi-version| |supported-versions| |supported-implementations| |wheel|
	* - Activity
	  - |commits-latest| |commits-since| |maintained|
	* - Other
	  - |license| |language| |requires| |pre_commit|

.. |docs| rtfd-shield::
	:project: domdf_sphinx_theme
	:alt: Documentation Build Status

.. |docs_check| actions-shield::
	:workflow: Docs Check
	:alt: Docs Check Status

.. |actions_linux| actions-shield::
	:workflow: Linux
	:alt: Linux Test Status

.. |actions_windows| actions-shield::
	:workflow: Windows
	:alt: Windows Test Status

.. |actions_macos| actions-shield::
	:workflow: macOS
	:alt: macOS Test Status

.. |requires| requires-io-shield::
	:alt: Requirements Status

.. |codefactor| codefactor-shield::
	:alt: CodeFactor Grade

.. |pypi-version| pypi-shield::
	:project: domdf_sphinx_theme
	:version:
	:alt: PyPI - Package Version

.. |supported-versions| pypi-shield::
	:project: domdf_sphinx_theme
	:py-versions:
	:alt: PyPI - Supported Python Versions

.. |supported-implementations| pypi-shield::
	:project: domdf_sphinx_theme
	:implementations:
	:alt: PyPI - Supported Implementations

.. |wheel| pypi-shield::
	:project: domdf_sphinx_theme
	:wheel:
	:alt: PyPI - Wheel

.. |license| github-shield::
	:license:
	:alt: License

.. |language| github-shield::
	:top-language:
	:alt: GitHub top language

.. |commits-since| github-shield::
	:commits-since: v0.2.6
	:alt: GitHub commits since tagged version

.. |commits-latest| github-shield::
	:last-commit:
	:alt: GitHub last commit

.. |maintained| maintained-shield:: 2020
	:alt: Maintenance

.. |pre_commit| pre-commit-shield::
	:alt: pre-commit

.. |pre_commit_ci| pre-commit-ci-shield::
	:alt: pre-commit.ci status

.. end shields

Changes include:

* Smooth scrolling between sections.
* Wider body by default.
* Extra spacing in lists.
* Some JavaScript trickery to fix the ReadTheDocs versions menu.

|

| The examples that show the look and feel of this theme are from `sphinx_rtd_theme <https://github.com/readthedocs/sphinx_rtd_theme>`_.
| Copyright (c) 2013-2018 Dave Snider, Read the Docs, Inc. & contributors.

.. toctree::
	:hidden:

	Home<self>
	installation

.. toctree::
	:maxdepth: 2
	:numbered:
	:caption: Demo Documentation

	demo/structure
	demo/demo
	demo/lists_tables
	demo/api

.. toctree::
	:maxdepth: 3
	:numbered:
	:caption: This is an incredibly long caption for a long menu

	demo/long


.. toctree::
	:maxdepth: 3
	:caption: Contributing

	contributing
	Source

.. start links

View the :ref:`Function Index <genindex>` or browse the `Source Code <_modules/index.html>`__.

`Browse the GitHub Repository <https://github.com/domdfcoding/domdf_sphinx_theme>`__

.. end links
