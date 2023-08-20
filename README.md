![data-science](https://github.com/IvanLiraSilva/IvanLiraSilva/assets/105115099/67f4d50f-6c32-427c-aa0d-7f9f4990a713)



# Hi, I'm Ivan Silva 👋
### I have a degree in Computer Engineering and a postgraduate degree in Information Security.

- 🌱 I'm currently learning about machine learning and data science.
- 🤔 I’m looking for help with data science.
- 🌱 I'm currently studying English at CNA.

##

### You can also find me...
<div> 
 <a href = "mailto:engcompivansilva@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/engenheiro-ivan-silva/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
    <a href="https://web.whatsapp.com/send?phone=+5543998092771"> <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" target="_blank"></a>
    <a href = "https://www.kaggle.com/ivanlira"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" target="_blank"></a>

  
</div>

##


### Some tools and technologies that I am aware of.
<div style="display: inline_block"><br>
  <img align="center" alt="Ivan-Python" height="50" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  <img align="center" height="50" width="50" 
src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg">
  <img align="center" height="50" width="50" 
src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg">
  <img align="center" height="50" width="50" 
src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg">
  <img align="center" height="50" width="50" 
src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg">
  <img align="center" height="50" width="50" 
src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/r/r-original.svg">
  <img align="center" height="50" width="50" 
src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rstudio/rstudio-original.svg">
  <img align="center" height="50" width="50" 
src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg">
  <img align="center" height="50" width="50" 
src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pycharm/pycharm-original.svg">
  <img align="center" height="50" width="50" 
src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/anaconda/anaconda-original.svg">
  <img align="center" height="50" width="50" 
src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)">
  <img align="center" height="50" width="50" 
src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white">
  <img align="center" height="50" width="50" 
src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white">

        
  
</div>
  
  ##
 
# snk



<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/IvanLiraSilva/snk/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/IvanLiraSilva/snk/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution grid snake animation"
    src="https://raw.githubusercontent.com/IvanLiraSilva/snk/output/github-contribution-grid-snake.svg"
  />
</picture>



Generate a [gif](https://github.com/IvanliraSilva/snk/raw/output/github-contribution-grid-snake.gif) or [svg](https://github.com/IvanLiraSilva/snk/raw/output/github-contribution-grid-snake.svg) image.

Available as github action. It can automatically generate a new image each day. Which makes for great [github profile readme](https://docs.github.com/en/free-pro-team@latest/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme)



## Usage

**github action**

```yaml
- uses: IvanLiraSilva/snk@v3
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

  env:
    # a github token is required to fetch the contribution calendar from github API
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

[example with cron job](https://github.com/IvanLiraSilva/IvanLiraSilva/blob/master/.github/workflows/main.yml#L25-L33)

If you are only interested in generating a svg, consider using this faster action: `uses: Platane/snk/svg-only@v2`

**dark mode**

For **dark mode** support on github, use this [special syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#specifying-the-theme-an-image-is-shown-to) in your readme.

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>
```

**interactive demo**

<a href="https://IvanLiraSilva.github.io/snk">
  <img height="300px" src="https://user-images.githubusercontent.com/1659820/121798244-7c86d700-cc25-11eb-8c1c-b8e65556ac0d.gif" ></img>
</a>

[platane.github.io/snk](https://IvanLiraSilva.github.io/snk)





