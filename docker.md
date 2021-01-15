1508  docker .
 1509  sudo docker .
 1510  sudo docker build .
 1511  sudo docker build -t test-pyhon .
 1512  sudo docker run test-python
 1513  sudo docker run 0ca36cda568c
 1514  sudo docker run test-python
 1515  sudo docker build -t bottle .
 1516  sudo docker run 05776d0f4f4f
 1517  docker ps
 1518  sudo docker ps
 1519  sudo docker run bottle
 1520  sudo docker ps
 1521  sudo docker ps -a
 1522  sudo docker rm 05776d0f4f4f
 1523  sudo docker rm c6c012ac7a96
 1524  sudo docker rm c6c012ac7a96 $(sudo docker ps -a -q)
 1525  sudo docker rm -f  $(sudo docker ps -a -q)
 1526  sudo docker rm -f $(sudo docker ps -a -q)
 1527  sudo docker ps -a
 1528  sudo docker run bottle
 1529  sudo docker ps -a
 1530  sudo docker logs 3e721a54e1b2
 1531  sudo docker inspect
 1532  sudo docker inspect 3e721a54e1b2
 1535  sudo docker build -t bottle .
 1536  sudo docker run bottle
 1537  sudo docker ps -a
 1538  sudo docker logs f97f2ae315ed
 1546  sudo docker ps -a
 1547  sudo docker run -it bottle /bin/bash
 1550  sudo docker build -t bottle .
 1551  sudo docker run -it bottle /bin/bash
 1552  sudo docker run bottle
 1553  sudo docker build -t bottle .
 1554  sudo docker run bottle
 1555  sudo docker run -it bottle /bin/bash
 1556  sudo docker run bottle
 1557  sudo docker ps -a
 1558  sudo docker logs 2190f4c37353
 1559  sudo docker run bottle
 1560  sudo docker build -t bottle .
 1561  sudo docker run bottle
 1567  docker build -t bottle-base .
 1568  sudo docker build -t bottle-base .
 1570  sudo docker build -t bottle-base .
 1574  git commit -m "docker and task order"
 1576  git commit -m "docker and task order"
 1581  docker build .
 1582  sudo docker build .
 1685  sudo docker build .
 1686  sudo docker -t bottle build . 
 1687  sudo docker -t bottlebuild . 
 1688  sudo docker build -t bottlebuild . 
 1689  docker run 06da0e1b4ba9 -p 80:8000
 1690  sudo docker run 06da0e1b4ba9 -p 80:8000
 1691  sudo docker run bottlebuild -p 80:8000
 1693  history | grep docker
 1694  sudo docker ps -a
 1695  sudo docker run b580d3de897d -p 80:8000
 1696  sudo docker run e14b67bedce9 -p 80:8000
 1697  sudo docker run bottlebuild -p 80:8000
 1698  sudo docker run -p 80:8000 bottlebuild
 1699  sudo docker run -p 3000:8000 bottlebuild
 1700  sudo docker run -p 8000:8000 bottlebuild
 1701  sudo docker run -p 81:8000 bottlebuild
 1703  sudo docker run -p 81:8000 bottlebuild
 1704  sudo docker run -p 8000:8000 bottlebuild
 1707  sudo docker run -p 8000:8000 bottlebuild
 1709  docker ps
 1710  sudo docker ps
 1711  docker kill e7a76535aeb5
 1712  sudo docker kill e7a76535aeb5
 1713  sudo docker ps
 1714  sudo docker kill 7eb4a0e2e82e
 1715  sudo docker ps
 1716  sudo docker kill 230f0fa1c37d
 1719  sudo docker ps
 1720  sudo docker kill 0538a8707a03
 1756  sudo docker build -t botocr .
 1812  sudo docker build -t botcr .
 1839  git commit -m "install tesserct in docker machine"
 1846  git commit -m "lib tesseract docker install"
 1849  git commit -m "lib tesseract docker install confirm"
 1995  history | grep docker
sudo docker rm -f $(sudo docker ps -a -q)
sudo docker rmi $(sudo docker images -a -q)
