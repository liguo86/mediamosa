
# Release Checklist

It's easiest to start with a fresh repository, so the instructions start there.

1. `VERSION=42.0.13` — We'll use this value later.
1. `git clone git@github.com:scholarslab/BagItPHP`
1. `cd BagItPHP`
1. `git flow init`
1. `git flow release start $VERSION`
1. `ant package`
1. quick check the zip
1. test the zip
1. `git flow release finish $VERSION`
1. `git push`
1. `git push --tags`

