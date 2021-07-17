# Artem Khvostyk

## About me:
I am **_creative_**, **_hardworking_** and **_reliable_** person. I joined this course to learn JavaScript and know more about CS in general.

## Technologies I use and learn:

- JavaScript
- HTML
  - BEM
- CSS
  - SASS(SCSS)
- Python
  - Django
    - Jinja
- GIT
  - Github
  - Conventional commits
- SQL
  - PostgreSQL
  - SQLite
- Other
  - Gulp
  - Markdown
  - RegExp


## My code examples:

**Moves in squared strings (II)**

```JavaScript
function rot(strng) {
    return strng.split("\n").reverse().map(el => [...el].reverse().join("")).join("\n")
}
function selfieAndRot(strng) {
  const dots = ".".repeat(strng.split("\n").length)
    return strng.replace(/\n/g, `${dots}\n`) + `${dots}\n${dots}` + rot(strng) .replace(/\n/g, `\n${dots}`)
}
function oper(fct, s) {
    return fct(s)
}
```

**Where my anagrams at ?**

```python
def anagrams(word, words):
    return [w for w in words if all(map(lambda a: w.count(a) == word.count(a), set(word)|set(w)))]
```
