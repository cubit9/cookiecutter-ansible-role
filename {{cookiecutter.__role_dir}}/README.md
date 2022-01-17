# {{ cookiecutter.__role_slug }}

{{ cookiecutter.description }}
{% if cookiecutter.default_ci_badges == "Y" %}

## Build Status

### GitHub Actions

![Molecule Test](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.__role_slug }}/workflows/Molecule%20Test/badge.svg)

{% endif %}

## Requirements

For any required Ansible roles, review:
[requirements.yml](requirements.yml)

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

## Example Playbook

[playbook.yml](playbook.yml)

## License

{{ cookiecutter.license }}

## Author Information

{{ cookiecutter.author }}

- [{{ cookiecutter.email }}](mailto:{{ cookiecutter.email }})
- [{{ cookiecutter.website }}]({{ cookiecutter.website }})

> NOTE: Repo has been created/updated using [https://github.com/cubit9/cookiecutter-ansible-role](https://github.com/cubit9/cookiecutter-ansible-role) as a template.
