# Change Log

## [1.0.6] 2022-01-16
### Improvements

- Bump Django Codebase to [v2stable.0.1](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
- Dependencies update (all packages) 
  - Django==4.0.1
- Settings update for Django 4.x
  - `New Parameter`: CSRF_TRUSTED_ORIGINS
    - [Origin header checking isn`t performed in older versions](https://docs.djangoproject.com/en/4.0/ref/settings/#csrf-trusted-origins)  

## [1.0.5] 2021-10-06 
### Improvements

- Mention `admin` section custom theme
  - [Django Admin Volt](https://pypi.org/project/django-admin-volt/) available on PyPi and Github
- `Presentation` page
  - Update Top links     

## [1.0.4] 2021-09-15 
### Improvements

- Bump Django Codebase to [v2.0.4](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
  - Codebase update
    - `assets` & `templates` moved to `apps` folder
    - `apps/base` renamed to `apps/home`

## [1.0.3] 2021-09-07
### Improvements & Fixes

- Bump Django Codebase to [v2.0.2](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
  - Dependencies update (all packages)
    - Use Django==3.2.6 (latest stable version)
  - Better Code formatting
  - Improved Files organization
  - Optimize imports
  - Docker Scripts Update 
- Fixes: 
  - Patch 500 Error when authenticated users access `admin` path (no slash at the end)
  - Patch [#16](https://github.com/app-generator/boilerplate-code-django-dashboard/issues/16): Minor issue in Docker 

## [1.0.2] 2021-08-27
### Improvements

- Bump UI - [Volt Dashboard v1.4.1](https://github.com/themesberg/volt-bootstrap-5-dashboard/releases) 

## Unreleased 2021-08-05
### Tooling

- Added scripts to recompile the SCSS files
    - `core/static/assets/` - gulpfile.js
    - `core/static/assets/` - package.json
- `Update README` - [Recompile SCSS](https://github.com/app-generator/django-dashboard-volt#recompile-css) (new section)

## [1.0.1] 2021-03-30
### Improvements

- Bump UI: [Jinja Volt](https://github.com/app-generator/jinja-volt-dashboard/releases) v1.0.1
- [Volt Dashboard](https://github.com/themesberg/volt-bootstrap-5-dashboard/releases) v1.3.2

## [1.0.0] 2021-01-17

- Bump UI: [Jinja Volt](https://github.com/app-generator/jinja-volt-dashboard/releases) v1.0.0
- [Volt Dashboard](https://github.com/themesberg/volt-bootstrap-5-dashboard/releases/tag) v1.2.0 
- Codebase: [Django Dashboard](https://github.com/app-generator/boilerplate-code-django-dashboard/releases) v1.0.4
