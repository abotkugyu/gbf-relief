FROM nginx:1.9.12
ADD conf/default.conf /etc/nginx/conf.d
ENV NODE_PATH /usr/local/lib/node_modules
ENV TZ=Japan
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
