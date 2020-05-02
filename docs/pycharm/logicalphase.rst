Notes on Cookiecutter-Django installation and initial gotchas:
==============================================================


ENV Options:
============


Git Issues:
===========
Make sure that .gitignore is updated to exclude `conf` dir and `.pem` files from Github inclusion. If not, you'll need to
remove those from git cached files with `git rm --cached file1 file2 dir/file3` to remove them. This should probably be
noted in the project docs with @cookiecutter-django repo.
