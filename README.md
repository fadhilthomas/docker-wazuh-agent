## docker-wazuh-agent

#### Description

Wazuh Agent as Docker Image.


#### Run

    docker build -t fadhilthomas/wazuh-agent:3.13.1 .


#### Run

    docker run -d -e AGENT_MANAGER=${MANAGER_IP} -e AGENT_NAME=${AGENT_NAME} -v /${NGINX_LOG_PATH}:/var/log/nginx/ fadhilthomas/wazuh-agent:3.13.1


#### Source

https://github.com/noenv/docker-wazuh-agent
