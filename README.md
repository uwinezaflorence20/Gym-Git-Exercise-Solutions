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

  Exercise 2 
  history
    1  git checkout -b ft/service-redesign
    2  git add service.html
    3  git add services.html
    4  git commit -m "Redesign service.html page"
    5  git push -u origin ft/service-rredesign
    6  git push -u origin ft/service-redesign
    7  git checkout main
    8  git add services.httml
    9  git add services.html
   10  git commit -m "Different change to service.html on main"
   11  git push origin main
   12  git checkout ft/service-redesign
   13  git diff main
   14  git merge main
   15  git add services.html
   16  git commit -m "Resolved merge conflict in service.html"
   17  git push origin ft/service-redesign
   18  git checkout main
   19  git history
   20  history


Bundle 3
  Exercise 1
  2  git checkout -b ft/team-page
    3  touch team.html
    4  git add team.html
    5  git commit -m "added the the team.html to this branch"
    6  git push -u origin ft/team-page
    7  git checkout main
    8  git checkout -b ft/contact-page
    9  git checkout ft/team-page
   10  git chaeckout main
   11  git pull origin main
   12  git checkout ft/team-page
   13  git log --oneline
   14  git checkout ft/contact-page
   15  git cherry-pick abc1234
   16  git cherry-pick fbbb29a
   17  history
   git commit -m "Revert changes from team page"
   git push -u origin ft/team-page
   git checkout -b ft/faq-page
  225  touch faq.html
  226  git add faq.html
  227  git commit -m "Add faq.html page"
  228  git push -u ft/faq-page
  229  [200~git push -u origin ft/faq-page~
  230  git push -u origin ft/faq-page
  231  git checkout ft/team-page
  232  git push -u origin ft/faq-page
  233  git checkout ft/team-page
  234  [200~git add faq.html
  235  git commit -m "Add initial content for faq.html"
  236  git push
  237  ~
  238  git checkout ft/team-page
  239  git add faq.html
  240  git commit -m "Work in progress on faq.html"
  241  git push origin ft/faq-page
  242  git checkout ft/team-page
  243  git revert fbbb29a
  244  git revert fbbb29a
  245  histoy
  246  history