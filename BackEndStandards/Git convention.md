![](assets/images/git_banner.png)
<br>
# Git commit message convention that you can follow!

A typical git commit message will look like <br>

``` <type>(<scope>): <subject>  ```

#  "type" must be one of the following mentioned below!


| key    | description |
|--------|-------------|
| build   | Build related changes (eg: npm related/ adding external dependencies)
| chore   | A code change that external user won't see (eg: change to .gitignore file or .prettierrc file)
| feat   | A new feature
| fix   | A bug fix
| docs   | Documentation related changes
| refactor   | A code that neither fix bug nor adds a feature. (eg: You can use this when there is semantic changes like renaming a variable/ function name)
| perf   |  A code that improves performance
| style   | A code that is related to styling
| perf   |  test

# "scope" is optional
- Scope must be noun and it represents the section of the section of the codebase


# "subject" is the main part of the commit message

- use imperative, present tense (eg: use "add" instead of "added" or "adds") <br>
- don't use dot(.) at end <br>
- don't capitalize first letter