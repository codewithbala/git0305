# git0305
pushing code from git on 0305
mkdir gittest0305
 1520  cd gittest0305/
 1521  nano First.Java
 1522  ls
 1523  cat First.Java
 1524  ls -la
 1525  chmod 755 First.java
 1526  chmod 777 First.java
 1527  git init
 1528  git status
 1529  git add First.java
 1530  ls
 1531  git add .
 1532  git status
 1533  cat First.Java
 1534  touch First.java
 1535  ls
 1536  git config --global user.name bala
 1537  git config --global user.email bala@gmail.com
 1538  git add .
 1539  git commit -m "Adding java files"
 1540  git remote add origin https://github.com/codewithbala/git0305.git
 1541  git branch -M main
 1542  git branch
 1543  git push -u origin main
 1544  git push -f origin main
 1545  touch Second.java
 1546  ls
 1547  git status
 1548  git add Second.java
 1549  git status
 1550  git restore Second.java
 1551  git status
 1552  git restore --staged Second.java
 1553  git status
 1554  git add Second.java
 1555  git status
 1556  cat First.java
 1557  ls
 1558  cat First.Java
 1559  git status
 1560  git add Second.java
 1561  git commit -m "adding second.java"
 1562  git status
 1563  git branch
 1564  git push -u origin main
 1565  git pull
 1566  git pull https://github.com/codewithbala/git0305.git main
 1567  git config pull.rebase false
 1568  git status
 1569  git push -u origin main
 1570  git push -f origin main
 1571  git push --help
 1572  git pull --help
 1573  history
