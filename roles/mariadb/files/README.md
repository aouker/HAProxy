# clustercheck.j2
Please put this file to /usr/bin in www1 and www2

# server.cnf.j2
Please put this file to www1

# server2.cnf.j2
Please put this files to www2 and change the filename to server.cnf

# mariadb.repo.2j
Please put this file to /etc/yum.repo.d/ in www1 and www2

#mysqlchk.j2
Please put this file to /etc/xinetd.d in www1 and www2 after install xinetd

#service.j2 (Set port 9200 to mysqlchk)
Please replace this file to /etc/service in www1 and www2

#haproxy.j2
Please replace this file to /etc/haproxy/haproxy.cfg in www
