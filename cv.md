# Artem Khvostyk

[Github](https://github.com/KUSTIKs) | [Discord](https://discord.com/users/522730231543627796) | [Telegram](https://t.me/Artem_Kustikovich)

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

## Education

1. [CS50](https://cs50.harvard.edu/)
2. [Codewars](https://www.codewars.com/)
3. [MDN](https://developer.mozilla.org/)
4. Youtube courses & videos
   - [freeCodeCamp.org](https://www.youtube.com/channel/UC8butISFwT-Wl7EV0hUK0BQ)
   - [Владилен Минин](https://www.youtube.com/channel/UCg8ss4xW9jASrqWGP30jXiw)
   - [Online Tutorials](https://www.youtube.com/channel/UCbwXnUipZsLfUckBPsC7Jog)
   - [CodingLab](https://www.youtube.com/channel/UCBlr2jG1onljL-gUy9bbhJw)
   - [Фрилансер по жизни](https://www.youtube.com/channel/UCedskVwIKiZJsO8XdJdLKnA)
   - [Denis Ivy](https://www.youtube.com/channel/UCTZRcDjjkVajGL6wd76UnGg)
   - [Pyplane](https://www.youtube.com/channel/UCQtHyVB4O4Nwy1ff5qQnyRw)
   - [Django School](https://www.youtube.com/channel/UC_hPYclmFCIENpMUHpPY8FQ)
   - [Corey Schafer](https://www.youtube.com/user/schafer5)
