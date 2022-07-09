### [![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%125b37CF7&lines=Howdy,+my+friends!+👋+ )](https://git.io/typing-svg)

- 🔭 I’m currently working on MongodbTech.
- 🌱 I’m currently learning 🐍Python.
- 📲 Contact me with telegram @LitvinauAlex or email litvinaualex@gmail.com.
- 👯 I’m looking to collaborate on LinkedIn https://www.linkedin.com/in/aliaksandr-litvinau/.
- 🤔 I’m looking for help with LinkedIn.
- 😄 Pronouns: He/His.
- ⚡ Fun fact: I like to watch cartoons with my daughter.

- uses: Platane/snk@v2
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
