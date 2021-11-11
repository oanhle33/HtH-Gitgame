    1  git clone
    2  git clear
    3  clear
    4  git clone https://github.com/lanoanh33/HTH-Bashcrawl.git
    5  ls
    6  cd HTH-Bashcrawl
    7  ls
    8  git status
    9  git commit -m "first version of"
   10  #!/bin/bash
   11  if [ -z $1 ]; then    echo "well, someone didn't want to run the script with a file...";   exit; fi
   12  #!/bin/bash
   13  if [ -z $1 ]; then    echo "well, someone didn't want to run the script with a file...";   exit; fi
   14  file=$1
   15  bug=7c85d987a917c2a555d1391426978f05
   16  mesg="Level 7: \n Linus has been here...\nI love messing with these amateur programmers!!\nIf you want some real fun, then you should try resolving a conflict between this branch (tree) and code4life.\nI introduced a little bug that you should fix in the conflict. >:)\nAfter you merge these 2 files you should run the shell script again!!\n\nGood Luck!!!\n\n Hint: https://help.github.com/articles/resolving-a-merge-conflict-from-the-command-line/ "
   17  merges=$(git log --format=%h --merges | head -1)
   18  csum="md5sum"
   19  if [ $(echo "$OSTYPE" | grep darwin) ];then     csum="md5"; fi
   20  if [ "$file" = "nextclue_input.cpp" ];then    if [ ${merges} ]; then      while read p; do        for w in $p;do          if [ `echo $w | $csum | awk '{print $1}'` = $bug ];then            echo -e $mesg;            exit;          fi;        done;     done < $file ;     echo -e "Well, congratulations!! You fixed my conflict!!\nIf you would like to continue, then you should checkout to the $(echo 90mP8ouQHsNe | tr -d '0-9A-Z') branch!!\n" ;    else       echo -e $mesg;       exit;    fi;  else    echo "Looks like you passed in the wrong file"; fi
   21  #!/bin/bash
   22  if [ -z $1 ]; then    echo "well, someone didn't want to run the script with a file...";   exit; fi
   23  file=$1
   24  bug=7c85d987a917c2a555d1391426978f05
   25  mesg="Level 7: \n Linus has been here...\nI love messing with these amateur programmers!!\nIf you want some real fun, then you should try resolving a conflict between this branch (tree) and code4life.\nI introduced a little bug that you should fix in the conflict. >:)\nAfter you merge these 2 files you should run the shell script again!!\n\nGood Luck!!!\n\n Hint: https://help.github.com/articles/resolving-a-merge-conflict-from-the-command-line/ "
   26  merges=$(git log --format=%h --merges | head -1)
   27  csum="md5sum"
   28  if [ $(echo "$OSTYPE" | grep darwin) ];then     csum="md5"; fi
   29  if [ "$file" = "nextclue_input.cpp" ];then    if [ ${merges} ]; then      while read p; do        for w in $p;do          if [ `echo $w | $csum | awk '{print $1}'` = $bug ];then            echo -e $mesg;            exit;          fi;        done;     done < $file ;     echo -e "Well, congratulations!! You fixed my conflict!!\nIf you would like to continue, then you should checkout to the $(echo 90mP8ouQHsNe | tr -d '0-9A-Z') branch!!\n" ;    else       echo -e $mesg;       exit;    fi;  else    echo "Looks like you passed in the wrong file"; fi
   30  #!/bin/bash
   31  if [ -z $1 ]; then    echo "well, someone didn't want to run the script with a file...";   exit; fi
   32  file=$1
   33  bug=7c85d987a917c2a555d1391426978f05
   34  mesg="Level 7: \n Linus has been here...\nI love messing with these amateur programmers!!\nIf you want some real fun, then you should try resolving a conflict between this branch (tree) and code4life.\nI introduced a little bug that you should fix in the conflict. >:)\nAfter you merge these 2 files you should run the shell script again!!\n\nGood Luck!!!\n\n Hint: https://help.github.com/articles/resolving-a-merge-conflict-from-the-command-line/ "
   35  merges=$(git log --format=%h --merges | head -1)
   36  csum="md5sum"
   37  if [ $(echo "$OSTYPE" | grep darwin) ];then     csum="md5"; fi
   38  if [ "$file" = "nextclue_input.cpp" ];then    if [ ${merges} ]; then      while read p; do        for w in $p;do          if [ `echo $w | $csum | awk '{print $1}'` = $bug ];then            echo -e $mesg;            exit;          fi;        done;     done < $file ;     echo -e "Well, congratulations!! You fixed my conflict!!\nIf you would like to continue, then you should checkout to the $(echo 90mP8ouQHsNe | tr -d '0-9A-Z') branch!!\n" ;    else       echo -e $mesg;       exit;    fi;  else    echo "Looks like you passed in the wrong file"; fi
   39  #!/bin/bash
   40  if [ -z $1 ]; then    echo "well, someone didn't want to run the script with a file...";   exit; fi
   41  file=$1
   42  bug=7c85d987a917c2a555d1391426978f05
   43  mesg="Level 7: \n Linus has been here...\nI love messing with these amateur programmers!!\nIf you want some real fun, then you should try resolving a conflict between this branch (tree) and code4life.\nI introduced a little bug that you should fix in the conflict. >:)\nAfter you merge these 2 files you should run the shell script again!!\n\nGood Luck!!!\n\n Hint: https://help.github.com/articles/resolving-a-merge-conflict-from-the-command-line/ "
   44  merges=$(git log --format=%h --merges | head -1)
   45  csum="md5sum"
   46  if [ $(echo "$OSTYPE" | grep darwin) ];then     csum="md5"; fi
   47  if [ "$file" = "nextclue_input.cpp" ];then    if [ ${merges} ]; then      while read p; do        for w in $p;do          if [ `echo $w | $csum | awk '{print $1}'` = $bug ];then            echo -e $mesg;            exit;          fi;        done;     done < $file ;     echo -e "Well, congratulations!! You fixed my conflict!!\nIf you would like to continue, then you should checkout to the $(echo 90mP8ouQHsNe | tr -d '0-9A-Z') branch!!\n" ;    else       echo -e $mesg;       exit;    fi;  else    echo "Looks like you passed in the wrong file"; fi
   48  #!/bin/bash
   49  if [ -z $1 ]; then    echo "well, someone didn't want to run the script with a file...";   exit; fi
   50  file=$1
   51  bug=7c85d987a917c2a555d1391426978f05
   52  mesg="Level 7: \n Linus has been here...\nI love messing with these amateur programmers!!\nIf you want some real fun, then you should try resolving a conflict between this branch (tree) and code4life.\nI introduced a little bug that you should fix in the conflict. >:)\nAfter you merge these 2 files you should run the shell script again!!\n\nGood Luck!!!\n\n Hint: https://help.github.com/articles/resolving-a-merge-conflict-from-the-command-line/ "
   53  merges=$(git log --format=%h --merges | head -1)
   54  csum="md5sum"
   55  if [ $(echo "$OSTYPE" | grep darwin) ];then     csum="md5"; fi
   56  if [ "$file" = "nextclue_input.cpp" ];then    if [ ${merges} ]; then      while read p; do        for w in $p;do          if [ `echo $w | $csum | awk '{print $1}'` = $bug ];then            echo -e $mesg;            exit;          fi;        done;     done < $file ;     echo -e "Well, congratulations!! You fixed my conflict!!\nIf you would like to continue, then you should checkout to the $(echo 90mP8ouQHsNe | tr -d '0-9A-Z') branch!!\n" ;    else       echo -e $mesg;       exit;    fi;  else    echo "Looks like you passed in the wrong file"; fi
   57  #!/bin/bash
   58  if [ -z $1 ]; then    echo "well, someone didn't want to run the script with a file...";   exit; fi
   59  file=$1
   60  bug=7c85d987a917c2a555d1391426978f05
   61  mesg="Level 7: \n Linus has been here...\nI love messing with these amateur programmers!!\nIf you want some real fun, then you should try resolving a conflict between this branch (tree) and code4life.\nI introduced a little bug that you should fix in the conflict. >:)\nAfter you merge these 2 files you should run the shell script again!!\n\nGood Luck!!!\n\n Hint: https://help.github.com/articles/resolving-a-merge-conflict-from-the-command-line/ "
   62  merges=$(git log --format=%h --merges | head -1)
   63  csum="md5sum"
   64  if [ $(echo "$OSTYPE" | grep darwin) ];then     csum="md5"; fi
   65  if [ "$file" = "nextclue_input.cpp" ];then    if [ ${merges} ]; then      while read p; do        for w in $p;do          if [ `echo $w | $csum | awk '{print $1}'` = $bug ];then            echo -e $mesg;            exit;          fi;        done;     done < $file ;     echo -e "Well, congratulations!! You fixed my conflict!!\nIf you would like to continue, then you should checkout to the $(echo 90mP8ouQHsNe | tr -d '0-9A-Z') branch!!\n" ;    else       echo -e $mesg;       exit;    fi;  else    echo "Looks like you passed in the wrong file"; fi
   66  cat readme.md
   67  cd documents
   68  cd git-game
   69  cat readme.md
   70  ./outputclue.s nextclue_input.cpp
   71  ./outputclue.sh nextclue_input.cpp
   72  cat readme.md
   73  git brach -a
   74  git branch -a
   75  git checkout remotes/origin/mouse
   76  git commit 
   77  cat readme.md
   78  ./outputclue.sh nextclue_input.cpp
   79  git branch -a
   80  git checkout remotes/origin/mouse
   81  cat readme.md
   82  git add . 
   83  git commit -m 
   84  git commit -m "trying to checkout to the mouse branch"
   85  git push 
   86  git push origin master
   87  git checkout remotes/origin/mouse
   88  cat readme.md
   89  git diff remotes/origin/mouse bug -- remember
   90  git diff remotes/origin/mouse bug -- remember
   91  git diff mouse bug -- remember
   92  git diff remotes/origin/mouse remotes/origin/bug --remember
   93  git diff remotes/origin/mouse remotes/origin/bug -- remember
   94  git branch -a
   95  git checkout remotes/origin/Henry
   96  cat readme.md
   97  git checkout henry
   98  cat readme.md
   99  git checkout Henry
  100  cat readme.md
  101  git tag -d Henry
  102  git checkout Henry
  103  cat readme.md
  104  git remote add https://github.com/drami025/git-game.git
  105  git remote add update https://github.com/drami025/git-game.git
  106  git pull update master
  107  git pull
  108  cat readme.md
  109  git log
  110  git status
  111  git add readme.md
  112  git remote add update https://github.com/drami025/git-game.git
  113  git pull update master
  114  git status
  115  git reset readme.md
  116  git remote add update https://github.com/drami025/git-game.git
  117  git merge --abort
  118  git remote add update https://github.com/drami025/git-game.git
  119  git pull update master
  120  git push
  121  cat readme.md
  122  history > gitHistory.md
