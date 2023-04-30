# Semantic Commit Messages

**Format:** `<type>(<scope>): <subject>`

`<scope>` is optional

<br>

## Example

<br>

```
feat: add hat wobble
^--^  ^------------^
|     |
|     +-> Summary in present tense.
|
+-------> Type: chore, docs, feat, fix, refactor, style, or test.
```
<br>

- Allowed `<type>` values:

    - `feat`: (new feature for the user, not a new feature for build script)
    - `fix`: (bug fix for the user, not a fix to a build script)
    - `docs`: (changes to the documentation)
    - `style`: (formatting, missing semi colons, etc; no production code change)
    - `refactor`: (refactoring production code, eg. renaming a variable)
    - `test`: (adding missing tests, refactoring tests; no production code change)
    - `chore`: (updating grunt tasks etc; no production code change)

<br>

- The `<scope>` can be empty (e.g. if the change is a global or difficult to assign to a single component), in which case the parentheses are omitted. In smaller projects such as Karma plugins, the `<scope>` is empty. Example `<scope>` values: 

    - `init`
    - `runner`
    - `watcher`
    - `config`
    - `web-server`
    - `proxy`
    - `etc`.


<br>

- **Message Body** :

    - uses the imperative, **present tense**: “change” not “changed” nor “changes”
    - includes motivation for the change and contrasts with previous behavior
