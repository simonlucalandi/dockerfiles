MongoDB Monitoring Agent
========================

A simple MongoDB monitoring agent docker image  
Original source: <https://github.com/tianon/dockerfiles/tree/master/mongodb-mms>  

Usage
-----
The following docker command will start the monitoring service.  
`docker run -d -e MMS_API_KEY={YOUR_API_KEY} -e MMS_GROUP_ID={YOUR_GROUP_ID} rheosystems/mongodb-monitoring-agent`
