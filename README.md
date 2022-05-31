# yacht_templates
Yacht templates of containers I use for IT Automation development, and testing.

## What port each service run on?
* Jenkins = 8080/tcp, 50000/tcp
* Guacamole = 8080/tcp
* Damn Vulnerable Web Application (DVWA) = 80/tcp
* Gitlab = 80/tcp, 443/tcp, 22/tcp
* pgAdmin4 = 80/tcp
* NGINX = 80/tcp, 443/tcp
* NGNIX Proxy Manager = 80/tcp, 443/tcp, 81/tcp
* HEIMDALL = 80/tcp, 443/tcp
* Pi-hole = 53/tcp, 53/udp, 67/udp, 80/tcp
* CoreDNS = 53/tcp, 53/udp
* Portainer = 8000/tcp, 9443/tcp
* Yacht = 8000/tcp
* Docker Registry = 5000/tcp
* PostgreSQL = 5432/tcp
* Vault = 8200/tcp

## Templates:
* name: Vault - Development mode
    * Docker Hub: https://hub.docker.com/_/vault
* name: Vault
    * Docker Hub: https://hub.docker.com/_/vault
* name: Portainer
    * Official Website: https://docs.portainer.io/v/ce-2.11/start/install/server/docker/linux
* name: Jenkins
    * Docker Hub: https://hub.docker.com/r/jenkins/jenkins/
    * Note: To get the initial password login in the container and run the command "cat /var/jenkins_home/secrets/initialAdminPassword"
* name: Gitlab
    * Docker Hub: https://hub.docker.com/r/gitlab/gitlab-ce/
    * Note: To get the initial password login in the container and run the command "gitlab | grep 'Password:' /etc/gitlab/initial_root_password"
* Docker Registry
    * Official Website: https://docs.docker.com/registry/
    * Docker Hub: https://hub.docker.com/_/registry
* Pi-hole:
    * Docker Hug: https://hub.docker.com/r/pihole/pihole/
    * Official Website: https://pi-hole.net/
* HEIMDALL
    * GitHub: https://github.com/linuxserver/Heimdall
    * Official Website: https://heimdall.site/
    * Docker Hub: https://hub.docker.com/r/linuxserver/heimdall/
* PostgreSQL
    * Docker Hub: https://hub.docker.com/_/postgres
* pgAdmin4
    * Docker Hub: https://hub.docker.com/r/dpage/pgadmin4/#!
* Damn Vulnerable Web Application (DVWA)
    * Docker Hub: https://hub.docker.com/r/vulnerables/web-dvwa
* CoreDNS
    * Official Website: https://coredns.io/
    * Docker Hub: https://hub.docker.com/r/coredns/coredns/
* NGINX
    * Docker Hub: https://hub.docker.com/_/nginx/
* NGNIX Proxy Manager
    * Official Website: https://nginxproxymanager.com/
    * Docker Hub: https://hub.docker.com/r/jc21/nginx-proxy-manager/
    * Default Username and Password: admin@example.com, changeme
* Nextcloud
    * Docker Hub: https://hub.docker.com/_/nextcloud/
    * Official Website: https://nextcloud.com/
* Code-Server
    * Docker Hub: https://hub.docker.com/r/linuxserver/code-server
* File Browser
    * Docker Hub: https://hub.docker.com/r/filebrowser/filebrowser
    * Official Website: https://filebrowser.org/
    * GitHub: https://github.com/filebrowser/filebrowser
