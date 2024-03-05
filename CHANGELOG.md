# Change Log

## [1.0.16] 2024-03-05
### Changes

- Update [Custom Development](https://appseed.us/custom-development/) Section
  - New Pricing: `$3,999`

## [1.0.15] 2024-03-04
### Changes

- Deprecate `distutils`
  - use `str2bool`
- Update Deps 
  - `requirements.txt`  
- Update README: [PRO Version](https://appseed.us/product/volt-dashboard-pro/django/), List features
  - `API`, **Charts** 
  - **DataTables** (Filters, Export)
  - **Celery**
  - **Media Files Manager**
  - **Extended User Profiles**

## [1.0.14] 2023-02-14
### Changes

- Update [Custom Development](https://appseed.us/custom-development/) Section
- Minor Changes (readme)

## [1.0.13] 2023-10-21
### Changes

- Update Dependencies 
- Update README 

## [1.0.12] 2023-03-01
### Changes

- Bump design version:
   - [Django Admin Volt](https://github.com/app-generator/django-admin-volt) `v1.0.10`

## [1.0.11] 2023-01-31
### Changes

- DOCS Update (readme)
- Bump design version:
   - [Django Admin Volt](https://github.com/app-generator/django-admin-volt) `v1.0.9`

## [1.0.10] 2023-01-28
### Changes

- DOCS Update (readme). New sections:
  - `How to customize the theme`
  - Render deployment
- Configure the project to use `home/templates`
- Added `custom_footer` sample

## [1.0.9] 2023-01-07
### Changes

- Move to a `theme-based` pattern
  - [Django Admin Volt](https://github.com/app-generator/django-admin-volt)
- 🚀 `Deployment` 
  - `CI/CD` flow via `Render`

## [1.0.8] 2022-09-14
### Improvements

- Added **Github OAuth** via AllAuth. requires in `.env`:
  - `GITHUB_ID`=<YOUR_GITHUB_ID>
  - `GITHUB_SECRET`=<YOUR_GITHUB_SECRET>
- `Docker` Improvements
- Pages UX Updates:
  - `SignIN`, `SignUP`, `Settings`  

## [1.0.7] 2022-05-25
### Improvements

- Built with [Volt Dashboard Generator](https://appseed.us/generator/volt-dashboard/)
  - Timestamp: `2022-05-25 22:38`
- Codebase refactoring
- Added CDN Support
  - via `.env` **ASSETS_ROOT** 

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
