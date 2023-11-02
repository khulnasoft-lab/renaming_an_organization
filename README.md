# GitHub Renaming an Organization:articulated_lorry: #

## What is this? ##
This is a simple bash script intended to help folks update their git
remotes when a GitHub organization undergoes a name change.  The tool
updates the default git remote (`origin`) for all git repositories
directly inside the specified directory.  The git remotes are updated
by replacing instances of `old_org_name` with `new_org_name`.

```
cd ~/Projects
wget https://raw.githubusercontent.com/khulnasoft-lab/renaming_an_organization/develop/update_git_repos.sh
chmod +x update_git_repos.sh
./update_git_repos.sh W3Security W3Sec
```

## License ##

This project is in the worldwide [public domain](LICENSE.md).

This project is in the public domain within the United States, and
copyright and related rights in the work worldwide are waived through
the [CC0 1.0 Universal public domain
dedication](https://creativecommons.org/publicdomain/zero/1.0/).

All contributions to this project will be released under the CC0
dedication. By submitting a pull request, you are agreeing to comply
with this waiver of copyright interest.
