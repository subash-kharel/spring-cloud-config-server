# spring-cloud-config-server

URLS: localhost:8888/limits-service/default,  localhost:8888/limits-service/qa,  localhost:8888/limits-service/dev

Things to remember:
1) @EnableConfigServer
2) add and link git repo where all the configurations are added which is git-local-repo in our case.
      a) Steps are: first right click on the config server repo, then build path, then link folder.
