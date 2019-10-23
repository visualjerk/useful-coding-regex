# Useful Regular Expressions For Coding

These regular expressions help you find stuff fast in your code editor's recursive file search.

## Find untranslated strings in React projects

```
>([a-zA-Z][\s\S]+?)<|\{"([a-zA-Z][\s\S]+?)"\}
```
