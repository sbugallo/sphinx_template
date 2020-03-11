# {{cookiecutter.title}}

{%- if cookiecutter.language == "en" -%}

Web version: [https://{{cookiecutter.github_username}}.github.io/{{cookiecutter.repository_name}}](https://{{cookiecutter.github_username}}.github.io/{{cookiecutter.repository_name}})

PDF version: [https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.repository_name}}/raw/master/{{cookiecutter.repository_name}}.pdf](https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.repository_name}}/raw/master/{{cookiecutter.repository_name}}.pdf)

Errata reports, mistakes or contributions: [https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.repository_name}}](https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.repository_name}})

{% else %}

Versión web: [https://{{cookiecutter.github_username}}.github.io/{{cookiecutter.repository_name}}](https://{{cookiecutter.github_username}}.github.io/{{cookiecutter.repository_name}})

Versión PDF: [https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.repository_name}}/raw/master/{{cookiecutter.repository_name}}.pdf](https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.repository_name}}/raw/master/{{cookiecutter.repository_name}}.pdf)

Reporte de erratas, errores o contribuciones: [https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.repository_name}}](https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.repository_name}})

{% endif %}