nginx: nginx
dockergen: docker-gen -watch -only-exposed -notify "nginx -s reload" /app/nginx.tmpl /etc/nginx/conf.d/default.conf
nginx-new-relic-agent: nginx-nr-agent -c /etc/nginx-nr-agent/nginx-nr-agent.ini 
