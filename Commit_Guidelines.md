#Semantic Commit message style

When you are working in a collabaritive environment , many people actively contribute to the project. Every change you make should be known to others as well as you in the future. So when you **commit** changes to the repository the commit message must be understood and clear. Following the semantic commit message style will keep your commits organized and clear.

### Format of a commit message

Format: ```<type>(<scope>): <summary>```

*scope is optional*

#### Example of commit message

```
feat: add navigation bar
^--^  ^------------^
|     |
|     +-> Summary 
|
+-------> Type: chore, docs, feat, fix, refactor, style, or test.
```

**Note**: Summary must be in present tense

The commit contains the following structural elements, to communicate intent to the consumers 

```fix```: bug fix for the user (This can be corelated with [PATCH](https://semver.org/#summary) in semantic version)

```docs```: changes in the documentation

```feat```: new feature for the user (This can be corelated with [MINOR](https://semver.org/#summary) in semantic version)

```refractor```: refactoring production code, eg. renaming a variable , function name

```style```: formatting, missing semi colons, etc; no production code change

```chore```: updating repetitive tasks or routine tasks; no production code change.

```test```: adding missing tests, refactoring tests; no production code change

#### Bonus

```git log --oneline``` : shows all your recent commits in one line ,you can get gist of what changes happened recently.

```git log --oneline --graph``` : you can get a graphical view of you commits.