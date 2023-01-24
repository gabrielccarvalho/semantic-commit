# Semantic Commit Messages

We will format the git commit message the following way: <br>

```bash
<emoji> <type>(<scope>): <subject>. <issue_status>
```

**Example:**

```
:lady_beetle: fix (Component): Fix something. Fixes: #..
^--------^ ^--^ ^-------^   ^---------------^ ^------^
|          |    |           |                  |
|          |    |           |                  +--> (Optional) Issue reference: if the commit closes or fixes an issue
|          |    |           |
|          |    |           +---------------------> Commit summary in present tense.
|          |    |
|          |    +---------------------------------> Commit scope in the project
|          |
|          +--------------------------------------> Commit type
|
+-------------------------------------------------> Emoji according with the commit type.
```

**The commit will show this way:**

> 🐛 fix (Component): Fix something. Fixes: #..

## Important note:
**You should always use the imperative verb on commit summary**

## Commit Message Types

- **feat**: any new feature added.
- **fix**: fixing a bug in the codebase
- **docs**: adding or updating the documentation
- **refactor**: refactoring the production code
- **build**/**conf**: changes related to the build system (involving scripts, configurations)
- **dep**: upgrade or downgrade a dependency
- **test**: adding tests (no production code change)
- **ci**: changes related to the continuous integration and deployment system
- **style**: improving structure/format of the code e.g. missing semi colons (no production code change)
- **chore**: updating grunt tasks etc. (no production code change)
- **perf**: changes related to backward-compatible performance improvements

## Supported Emojis by Commit Message Types

| Type     | Emoji                                           |
| -------- | ----------------------------------------------- |
| feat     | :confetti_ball: `:confetti_ball:`               |
| fix      | :bug: `:bug:`                                   |
| docs     | :books: `:books:`                               |
| refactor | :recycle: `:recycle:`                           |
| build    | :construction_worker: `:construction_worker:`   |
| dep up   | :arrow_up: `:arrow_up:`                         |
| dep down | :arrow_down: `:arrow_down:`                     |
| test     | :white_check_mark: `:white_check_mark:`         |
| ci       | :green_heart: `:green_heart:`                   |
| style    | :art: `:art:`                                   |
| chore    | :robot: `:robot:`                               |
| perf     | :zap: `:zap:`                                   |

## References:
- https://github.com/ikatyang/emoji-cheat-sheet#place-building
- https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716