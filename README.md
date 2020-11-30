# CA106-Group-32-Project
Repository for CA106 Group Website Project
## Saving your changes with Git in Visual Studio Code
You should "commit" (save) your changes every time you make a significant edit to a file, be it your index.html file or any other file. This way, if you accidentally mess it up or break something, you can go back to the last working version. Here's how to do that in VSCode:
1. Click the "Source Control" tab (on the left, under the magnifying glass).
2. Click on the plus button to stage all your changes.
3. Commit (save) your changes by clicking the check mark near the top of the window.
4. Synchronize your changes by clicking the "refresh" button in the bottom-left corner of the window.

## The directory structure
The root directory contains two sub-directories: `homepage` and `sections`. `homepage` contains a directory called `css`, in which the main CSS file that will apply to most elements on the site is located. It also contains a directory called `img`, which is where the images used on the homepage go. Finally, it contains an `index.html` file, which will be our homepage.

Within the `sections` directory, there are 5 sub-directories, one for each person in the group. We'll use me (Scott) as an example. In the directory `scott`, there is an index.html file, which will be my homepage for my section of the website about Iceland. There are also four other HTML files, one for each topic: `food.html`, `geography.html`, `history.html` and `language.html`. You'll need to add these four files to your own directory.

Finally, there is an `img` directory, where the images relevent to my section on Iceland will go; as well as a `css` directory containing a file `section.css`. This file will be used to style your individual page. You should link both the `main.css` file from `homepage` as well as `section.css` to each of your 5 HTML files.
