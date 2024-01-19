### Hi there 👋

<!--
**Yijin-Fu/Yijin-Fu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

![Hello GIF](hello.gif)

Nice to meet all of you here. My name is Yijin. I possess eight years of higher education experience in Canada and the United States. I hold a Bachelor's degree in Statistics and a Master’s degree in Business Analytics from the United States. Beyond my expertise in STEM fields, I also delve into brand management and marketing analytics within the Canadian market.

As an experienced marketing data analyst, I have four years of experience using business intelligence software such as Tableau and Power BI. Additionally, I am highly proficient in utilizing SQL, Python, and R programming languages to navigate complex data. My keen attention to detail, coupled with solid skills and a rapid learning ability, allows me to quickly extract business insights from data.

I am deeply enthusiastic about conducting thorough market research, copywriting, and storytelling. With a focus on the e-commerce sector, I bring two years of experience leveraging social media channels such as YouTube, TikTok and Instagram for marketing purposes and analyzing digital data to stay abreast of trends. This enables me to identify beneficial opportunities for many companies. As a strategic marketer, I excel in identifying opportunities and resolving marketing challenges using scientific methods.

[![My Skills](https://skillicons.dev/icons?i=python,mysql,sqlite)]

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
