#  Contribution Guide

Hello all! Following are rules for contiibution guide for my repos

## How to contibute?

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

however there are some rules:

## Commits

In Commits use ___imperative present tense__

- :x: (wrong) `Added something somewhere`
- ✔️ (correct) `Add something somewhere`

Commin message title keep __under 50__ characters. If there are longer mesasge add it to description

I encourage you to use emoji in message title. Check https://gitmoji.dev/ or https://gitmoji.avaldigitallabs.com/ for more information.

### If you have direct access to repository

- Do not commit right into master, each commitn has to be made into branch and then you need request for merge changes.

### Some Commint message ideas

- `:bug: Fix ...` When you fixing bug
- `:sparkles: Add ...` When you adding new features
- `:arrow_down: Update ...` or `:arrow_up: Update ...` When you downgrading or upgrading dependenice
- `:recycle: Update ...` When you refractoring code

## Adding new features, reporting bugs and more

When you want add new feature please make new issue and write about it. Or you can check existing issue. Then in pull request reference this issue.

## Pull requests

When you made changes you have to create new pull request. Title must start with one of following words:

- `added:` New Features
- `fixed:` Bug fix
- `changed:` Feature change
- `deprecated:` New deprecation
- `removed:` Feature removal
- `security:` Security fix
- `performance:` Performance improvement
- `other:` Other

And describe whay you made changes that you have made. Also reference any issue you worked on in thin pull request.

Pull requests are used to generate changelgs in releases.
