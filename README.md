##launchjconsole 

This script uses brace expansion for servernames (first value) as well as ports (value2)

# ./launch-jconsole  "apache[a-z]gw tomcat[a-z]gw" "500[1-10]"


This would connect to all hosts of apachea-zgw as well as tomcata-zgw on ports 5001-5010 so long as hostname and ports are valid and open

# ./launch-jconsole "host" "port"
# ./launch-jconsole "host1 host2" "500[1-2]"
# ./launch-jconsole "host[1-2]" "500[1-2]"

