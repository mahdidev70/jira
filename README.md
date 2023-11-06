# Workspace

Setup internal tools and services for `ZeePlay Team`.

## Deployment

1. Check and Compare `ATL_PROXY_NAME`, `ATL_PROXY_PORT`  with `nginx/conf.d/*.conf`
2. Run stack
``` 
docker-compose up -d
```

## Crack License Key

Please run the command in the atlassian software(jira) container and copy/paste license key.
```commandline
java -jar atlassian-agent.jar -d -m [yourEmail] -n BAT -p conf -o http://[ServerIp-Or-Domain] -s [serverId]
```



