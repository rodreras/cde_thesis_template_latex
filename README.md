# CDE Thesis Latex Template

This is a template based on @csaybar, [project that you can find here](https://github.com/csaybar/CDEthesis).

Now, I remove everything that was related to the R or Rmd, and transformed into a version where you can upload to [Overleaf](https://www.overleaf.com/) and work on cloud.

## Instructions

- `templates/config.tex` is the file with several variables. There is only one thing that you could change, which is under the **Bibliography Setup**, but I don't recommend. It'd be better if you change your `.bib` file to **references.bib** as well.

- `pictures` is the folder where you will put all the images you need for your thesis. Then, from the desired chapter, you import it.

- `chapters` is a folder with the respective chapters for your thesis. This is the main difference from Cesar's code. It has one folder  `00_pre`, with the pre-content subject, such as title, abstract, acknoledgment. The `01_main` contain the chapters where you will write your thesis. You can organize the way you'd like.

- `main.tex` is the main file. It is responsible for bringing all the other tex files that are within `chapters` together. If you are adding or removing chapters, make sure to add/remove them from the `main.tex`.

- To add this to your Overleaf, you can download everything as a zip and then upload it to the plataform. You can also work locally with a Latex editor.
