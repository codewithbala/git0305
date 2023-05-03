 cd gittest1/
 1454  touch index.html
 1455  nano index.html
 1456  cat index.html
 1457  touch contact.html about.html
 1458  ls
 1459  git init
 1460  ls -la
 1461  git add about.html
 1462  git status
 1463  git add index.html
 1464  git status
 1465  git add .
 1466  git status
 1467  git rm --cached about.html
 1468  git status
 1469  git rm --cached .
 1470  git rm --cached contact.html index.html
 1471  git status
 1472  git add .
 1473  git status
 1474  git commit -m
 1475  git commit -m "Adding html files :about, contact, index"
 1476  cd ..
 1477  ls -la
 1478  cd gittest1
 1479  ls -la
 1480  cd .git
 1481  ls -la
 1482  cd ..
 1483  git config --global user.name bala
 1484  git config --global user.email bala@gmail.com
 1485  git remote add origin https://github.com/codewithbala/repo0205.git
 1486  git push origin master
 1487  git remote add origin https://github.com/codewithbala/repo0205.git
 1488  git push origin master
 1489  git push
 1490  git push --set-upstream origin master
 1491  touch Hello.java
 1492  git add .
 1493  git commit -m "Adding hello.java"
 1494  git push
 1495  nano Hello.java
 1496  git add .
 1497  git status
 1498  git commit -m "Hello.java"
 1499  git push
 1500  git remote add origin https://github.com/codewithbala/repo0205.git
 1501  git push origin master
 1502  git branch -m main
 1503  git push origin main
 1504  git remote add origin https://github.com/codewithbala/repo0205.git
 1505  git push origin main
 1506  git pull
 1507  git status
 1508  git push
 1509  git push origin HEAD
 1510  git push --help
 1511  goit push -all
 1512  git push -all
 1513  git push --all
 1514  git pull
 1515  git push
 1516  git push origin HEAD:main
 1517  clear
 1518  ls
 1519  mkdir gittest0305
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
 1574  mkdir NewDeveloper
 1575  cd NewDeveloper/
 1576  git clone https://github.com/codewithbala/git0305.git
 1577  cd ..
 1578  mkdir NewDeveloper
 1579  cd NewDeveloper/
 1580  git clone https://github.com/codewithbala/git0305.git
 1581  ls -la
 1582  cd git0305/
 1583  ls -la
 1584  cat First.Java
 1585  cat First.java
 1586  cat index.html
 1587  branch
 1588  git branch
 1589  git branch firstbranch
 1590  git branch
 1591  git branch secondbranch
 1592  git branch
 1593  git checkout firstbranch
 1594  git branch
 1595  ls
 1596  git checkout secondbranch
 1597  ls
 1598  git branch
 1599  git checkout firstbranch
 1600  git branch
 1601  nano FirstBranch.java
 1602  cat FirstBranch.java
 1603  git add FirstBranch.java
 1604  git status
 1605  git commit -m "Adding FirstBranch.java from firstbranch"
 1606  git status
 1607  git checkout main
 1608  git branch
 1609  git merge firstbranch
 1610  ls
 1611  git push origin master
 1612  git push origin main
 1613  git branch
 1614  git checkout firstbranch
 1615  git branch
 1616  lsq
 1617  ls
 1618  FirstBranch.html
 1619  nano FirstBranch.html
 1620  cat FirstBranch.html
 1621  git add FirstBranch.html
 1622  git status
 1623  git commit -m
 1624  git commit
 1625  git status
 1626  git checkout main
 1627  git branch
 1628  git merge firstbranch
 1629  git push origin main
