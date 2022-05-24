# Version Control

We use [`Git`](https://git-scm.com) as version control system.

Our `Git` repositories are hosted on [`GitHub`](https://github.com/Roqay).

## Recomended Git client

We recommend using [`GitHub Desktop`](https://desktop.github.com).

## Git guidance

- Git commits should represent parts of code not just single commit at the end of the day with the date as commit message.
- We should use the (issue, feature, task, user story, ...etc.) ID and title as the commit message.
  - For example: If this commit fixes bug number `1234` that has the title `Change order of products`, then the commit message should be `Bug 1234 - Resolved – Change order of products`.
- Remote should be updated daily. If you are working on a task and did not finish it to use the style mentioned above, you can use `Daily updates` with description for what is done in that commit as commit message for that case.
- Main branch should contain latest stable version of code.
  - If you are in development process, you should use the `dev` branch for that. And after finishing development and fixing bugs and this version become stable, you should merge that branch in `main`.
  - If the project is done and you are working on second phase or change request, you should use another branch created from `main` for that. For example, `phase2` branch. And after finishing this phase and fixing bugs and this version become stable, you should merge that branch in `main`.
- For cross-platform apps (`React Native`, ...etc.), you should not have different branches for `Android` and `iOS`.
