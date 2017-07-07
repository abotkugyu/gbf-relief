# gbf-relief

This application get twitter granbluefantasy raid.

DEMO:http://gbf-relief.abot.link/

### Need to module
~~~
docker-compose
~~~

### Need to change
Server Name
~~~
containers/nginx/conf/default.conf
~~~

### Need create file
Twitter APi Config
data/nodejs/twitter_api_config.js
~~~
exports.c_key = '***';
exports.c_secret = '***';
exports.a_key = '***';
exports.a_secret = ''***';
~~~

### After 
~~~
docker-compose start
~~~
