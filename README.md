# Nala
Nala is a open source repository for gathering and experimenting with food recipes

## Purpose
* Create, track and share recipes easily
* Easily experiment with recipes, tracking results of variations and versioning them
* Allow others to contribute and propose changes to your recipe (there's always room for improvement 😛)

## Structure
All recipes need to use the markdown format, and need to follow the following structure (proposals to change the structure are welcome)

```md
# Recipe Title
## Description
## Ingredients
## Steps
## Variations
## Additional infromation
```
If your recipe has multiple parts, use sub-recipes below the description section:

```md
# Recipe Title
## Description
## Sub-recipe 1
### Description
### Ingredients
### Steps
...

## Sub-recipe 2
### Description
### Ingredients
### Steps
...
```

## Contribution
### Branches
- `main` - all finalized recipes go into this branch
- `develop` - work-in-progress/experimental recipes go here

For experimentation, creating PRs, e.t.c, fork the repo and create PRs

### Pull Requests
If you're confident about your recipe to go into `develop`/`master`, create a PR from your branch to the destination branch. 
PRs to `main` will be reviewed thoroughly before being merged.

## Planned Improvements
* Include a github.io page with a markdown editor to make it easier for people to contribute
* Add pre-merge checks

**If you have any other recommendations/feature requests, feel free to contribute - open a PR, or create an issue**


