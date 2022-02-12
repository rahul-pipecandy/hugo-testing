# Hugo GitHub Issue #448

Details: <https://github.com/gohugoio/hugo/issues/448>

Description: Add ability to generate per-{year, month, day} archives

## Instructions

Clone this branch of the repository and build the site.

```bash
git clone --single-branch -b hugo-github-issue-448 https://github.com/jmooring/hugo-testing hugo-github-issue-448
cd hugo-github-issue-448
hugo server
```

## Customization

### List Pages

To override the templates used to render list pages, copy the desired template from the module's `layouts/partials/views/archive` directory to the same path within the root of your project.

For example, to override all four of the list views, your layouts directory should have this structure:

```text
layouts/
└── partials/
    └── views/
        └── archive/
            ├── list-all.html
            ├── list-day.html
            ├── list-month.html
            └── list-year.html
```

### List Items

Each list page renders one or more list items, one for each content page. To override the template used to render a list item, copy the desired template from the module's `layouts/partials/views/archive` directory to the `layouts/_default/views/archive` directory within the root of your project.

For example, to override 




, and the 
To override the partials used render list views (all, year, month, day), copy the correspond 

To override the list view for an archive day, copy:

```
layouts/partials/views/archive/list-day.html
```

from the module's layouts directory to either
