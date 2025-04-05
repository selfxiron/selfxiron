### Hey 👋, I'm Jeet Pratap Singh Rajput (aka selfxiron) 👨‍💻

💡 20 y/o self-taught developer  
⚡ I love building tools, tweaking Linux, and writing powerful Python scripts  
🧠 Good at math, obsessed with creating and experimenting

> "I don't just use the machine — I *talk* to it."

### ⚙️ Tech Stack
![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=python) 
![Linux](https://img.shields.io/badge/-Linux-05122A?style=flat&logo=linux)
![Fedora](https://img.shields.io/badge/-Fedora-05122A?style=flat&logo=fedora)
![Bash](https://img.shields.io/badge/-Bash-05122A?style=flat&logo=gnu-bash)

![selfxiron's GitHub Stats](https://github-readme-stats.vercel.app/api?username=selfxiron&show_icons=true&theme=radical)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=selfxiron&layout=compact&theme=radical)

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
