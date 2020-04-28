## Instructions

Website is viewable on [awcardoso.com](https://awcardoso.com)

#### Get necessary software

- Install [bash for windows](https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/)
- Install [git](https://git-scm.com/download/win)
- Install [sass](https://sass-lang.com/install)
- Install a text editor (Visual Studio Code or Sublime Text)

#### Clone the repo (one time setup)

_In the shell_
```
cd ~/Desktop # Or Windows equivalent
git clone https://github.com/khannotations/awcardoso
cd awcardoso # Or Windows equivalent
```

#### Running the website 

```
open index.html # Or Windows equivalent
sass --watch stylesheets/style.scss:./style.css
subl .          # Or open in text editor
```

#### Publishing changes

```
git add .
git commit -m "Description of changes."
git push origin master
```
