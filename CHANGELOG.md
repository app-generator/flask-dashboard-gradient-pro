# Change Log

## [1.0.6] 2022-04-01
### Fixes

- **Patch ImportError**: [cannot import name 'safe_str_cmp' from 'werkzeug.security'](https://docs.appseed.us/content/how-to-fix/importerror-cannot-import-name-safe_str_cmp-from-werkzeug.security)
  - `Werkzeug` deprecation of `safe_str_cmp` starting with version `2.1.0`
    - https://github.com/pallets/werkzeug/issues/2359

## [1.0.5] 2021-11-10
### Improvements

- Bump Codebase: [Flask Dashboard](https://github.com/app-generator/boilerplate-code-flask-dashboard) v2.0.0
  - Dependencies update (all packages) 
    - Flask==2.0.1 (latest stable version)
- Better Code formatting
- Improved Files organization
- Optimize imports
- Docker Scripts Update
- Gulp Tooling  (SASS Compilation)
- Fixes:
  - Import error in WTForms

## [1.0.4] 2021-05-16
### Dependencies Update

- Bump Codebase: [Flask Dashboard](https://github.com/app-generator/boilerplate-code-flask-dashboard) v1.0.6
- Freeze used versions in `requirements.txt`
    - jinja2 = 2.11.3
    
## [1.0.3] 2021-03-23
### Improvements

- Cump Codebase: [Flask Dashboard](https://github.com/app-generator/boilerplate-code-flask-dashboard) v1.0.5
- Bump UI: [Jinja Gradient PRO](https://github.com/app-generator/jinja-gradient-pro) v1.0.1

## [1.0.2] 2021-03-19
### Improvements

- Freeze used versions in `requirements.txt`
    - flask_sqlalchemy = 2.4.4
    - sqlalchemy = 1.3.23

- Added SCSS files
- Guard Home blueprint with `@login_required` decorator
- Added page-403 ( Access denied case)
- Syncronize the code-base with latest [boilerplate code](https://github.com/app-generator/boilerplate-code-flask-dashboard)

## [1.0.1] 2020-05-30
### Improvements

- Patch 403
- Update Licensing information
- Add CHANGELOG.md to track all changes

## [1.0.0] 2020-02-07
### Initial Release
