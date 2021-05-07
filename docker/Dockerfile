FROM minishift

RUN node server.js

ENTRYPOINT ["oc new-app https://github.com/ionutcaramaliu/DO288-apps --context-dir docker --name docker"]
