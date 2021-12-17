### 7 Rules for commit message ([References](https://chris.beams.io/posts/git-commit/))

1. Separate subject from body with a blank line

2. Limit the subject line to 50 characters

3. Capitalize the subject line

4. Do not end the subject line with a period

5. Use the imperative mood in the subject line

6. Wrap the body at 72 characters

7. Use the body to explain what and why vs. how


### Commit Message Format
Each commit message consists of a **header**, a **body** and a **footer**.  The header has a special
format that includes a **type**, a **subject** and an **issue**:

```
<type>: <subject> [<issue>]
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

The **header** is mandatory and the **scope** of the header is optional.

Example — `fix: remove unused dependency lodash.camelcase`

Any line of the commit message cannot be longer 100 characters. This allows the message to be easier to read on GitHub as well as in various git tools.

#### Type
Must be one of the following:

* **feat**: A new feature.
* **bug**: A bug fix.
* **docs**: Documentation only changes.
* **refactor**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc).
* **perf**: A code change that improves performance.
* **test**: Adding missing tests.

#### Subject
The subject contains succinct description of the change:

* use the imperative, present tense: `change` not `changed` nor `changes`,
* don't capitalize first letter,
* no dot (.) at the end.

#### Body
Just as in the **subject**, use the imperative, present tense: "change" not "changed" nor "changes".
The body should include the motivation for the change and contrast this with previous behavior.

#### Footer
The footer should contain any information about reference GitHub issues that this commit *behaviour**.

Behaviours can be the followings
- close/closes/closed
- fix/fixes/fixed
- resolve/resolves/resolved

### Referencing issues

Referencing issue should be listed on a separate line in the footer prefixed with one of the behaviour like this:

Closes #234

or in case of multiple issues:

Closes #123, #245, #992

