# Artem Khvostyk

[Github][gh] | [Discord][ds] | [Telegram][tg]

## About me

I am **_creative_**, **_hardworking_** and **_reliable_** person. I joined this course to learn JavaScript and know more about CS in general.

## Technologies I use and learn

- **JavaScript**
- **HTML**
  - BEM
- **CSS**
  - SASS(SCSS)
- **Python**
  - Django
    - Jinja
- **GIT**
  - Github
  - Conventional commits
- **SQL**
  - PostgreSQL
  - SQLite
- **Other**
  - Gulp
  - Markdown
  - RegExp

## My code examples

### Moves in squared strings (II)

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

### Where my anagrams at ?

```python
def anagrams(word, words):
    return [w for w in words if all(map(lambda a: w.count(a) == word.count(a), set(word)|set(w)))]
```

## Education

1. [CS50][cs50]
2. [Codewars][cw]
3. [MDN][mdn]
4. Youtube courses & videos
   - [freeCodeCamp.org][yt-1]
   - [Владилен Минин][yt-2]
   - [Online Tutorials][yt-3]
   - [CodingLab][yt-4]
   - [Фрилансер по жизни][yt-5]
   - [Denis Ivy][yt-6]
   - [Pyplane][yt-7]
   - [Django School][yt-8]
   - [Corey Schafer][yt-9]

## English

I was studying English in my school and with extracurricular classes. I understand english speech pretty well, but my speaking is a little poor. Generally, according to test in internet, I have a `B1` Level.

<!-- Social links -->

[gh]: https://github.com/KUSTIKs "KUSTIKs"
[ds]: https://discord.com/users/522730231543627796 "ArtemK"
[tg]: https://t.me/Artem_Kustikovich "@Artem_Kustikovich"

<!-- Other links -->

[cs50]: https://cs50.harvard.edu/ "CS50"
[cw]: https://www.codewars.com/ "Codewars"
[mdn]: https://developer.mozilla.org/ "MDN"

<!-- Youtube links -->

[yt-1]: https://www.youtube.com/channel/UC8butISFwT-Wl7EV0hUK0BQ
[yt-2]: https://www.youtube.com/channel/UCg8ss4xW9jASrqWGP30jXiw
[yt-3]: https://www.youtube.com/channel/UCbwXnUipZsLfUckBPsC7Jog
[yt-4]: https://www.youtube.com/channel/UCBlr2jG1onljL-gUy9bbhJw
[yt-5]: https://www.youtube.com/channel/UCedskVwIKiZJsO8XdJdLKnA
[yt-6]: https://www.youtube.com/channel/UCTZRcDjjkVajGL6wd76UnGg
[yt-7]: https://www.youtube.com/channel/UCQtHyVB4O4Nwy1ff5qQnyRw
[yt-8]: https://www.youtube.com/channel/UC_hPYclmFCIENpMUHpPY8FQ
[yt-9]: https://www.youtube.com/user/schafer5
