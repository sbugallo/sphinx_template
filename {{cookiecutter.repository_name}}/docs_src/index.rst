=====
Index
=====

{% if cookiecutter.language == "en" %}

.. important::

	Web version: `<https://{{cookiecutter.github_username}}.github.io/{{cookiecutter.repository_name}}>`_

	PDF version: `<https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.repository_name}}/raw/master/{{cookiecutter.repository_name}}.pdf>`_

	Errata reports, mistakes or contributions: `<https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.repository_name}}>`_

{% else %}

.. important::

	Versión web: `<https://{{cookiecutter.github_username}}.github.io/{{cookiecutter.repository_name}}>`_

	Versión PDF: `<https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.repository_name}}/raw/master/{{cookiecutter.repository_name}}.pdf>`_

	Reporte de erratas, errores o contribuciones: `<https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.repository_name}}>`_

{% endif %}

..  toctree::
    :maxdepth: 3

    parts/part_1/index

