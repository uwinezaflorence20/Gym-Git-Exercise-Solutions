History

Exercise 1 bundle 1
  155  git init
  156  touch index.html
  157  touch style.css
  158  touch README.md
  159  git branch -m main master
  160  git branch -m master main
  161  git add .
  162  git commit -m "first commit"      
  163  git remote add origin https://github.com/uwinezaflorence20/Gym-Git-Exercise-Solutions.git
  164  git push origin main
  165  git branch dev
  166  git checkout dev
  167  git branch test
  168  git branch
  169  git checkout test
  170  git checkout dev
  171  git branch -d test
  172  history

  Exercise 2 bundle 1

  220  touch home.html
  221  git stash -u
  222  git stast pop stash@{0}
  223  git stash drop stash@{0}
  224  git stash list
  225  touch home.html
  226  git stash -u
  227  git stash list
  228  touch about.html
  229  git stash -u
  230  touch team.html
  231  git stash -u
  232  git stash drop stash@{1}
  233  git stash list
  234  git stash pop stash@{1}
  235  git stash list
  236  git stash pop stash@{0}
  237  clear
  238  git stash pop stash@{0}
  239  git stash pop stash@{1}
  240  git stash pop stash@{2}
  241  git stash list
  242  history
  243  claear
  244  clear
  245  git stash list
  246  git stash pop stash@{0}
  247  git stash list
  248  git stash -u
  249  git stash -u
  250  git stash -u
  251  git stash list
  252  git stash pop stash@{1}
  253  git stash list
  256  git commit -m "after using pop stash"
  257  git push origin main
  258  git stash list
  259  git stash pop stash@{0}
  260  git reset --hard
  261  git clean -f
  262  history

  Bundle 2 

  Exercise 1:
  history
    1  git checkout -b ft/bundle-2
    2  touch services.html
    3  git add services.html
    4  git commit -m "Add services.html page with services content"
    5  git push -u origin ft/bundle-2
    6  history
