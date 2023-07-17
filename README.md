<div align="center">
  <a href="https://github.com/Jjooaogab">
     <img height="170em" src="https://github-readme-stats.vercel.app/api?username=Jjooaogab&show_icons=true&theme=omni&include_all_commits=true&count_private=true"/>
     <img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jjooaogab&layout=compact&langs_count=7&theme=omni"/>
</div>
  <div style="display: flex; justify-items: center; align-items: center"><br>
    <img align="center" alt="Jjooaogab-PYTHON" width="40" src="https://cdn-icons-png.flaticon.com/512/5968/5968286.png">
  </div>
  
- uses: Platane/snk@v2
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ Jjooaogab }}

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
