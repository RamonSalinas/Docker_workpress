# Docker_workpress
Sistema para instalar um ambente wordpress  usado a tecnologia  docker.  O seguinte material será descrito para o sistema operacional Linux.

# Pre - Requisitos
- SO  Linux Ubunto 18.04 - 20.04
- ter instalado docker se não tiver o programa pode seguir o seguinte tutorial desde o passo 2. https://www.hostinger.com.br/tutoriais/install-docker-ubuntu
- verificar sim tem instalado docker-compose  pode segur o seguente tutorial sem deseja installar o componente se nao foi instalado com o procedimento anterior https://www.hostinger.com.br/tutoriais/instalar-docker-compose-no-ubuntu/

# Instalação

1. Clone o repositorio git Clone
2. Na pasta onde foi clonado o repositorio execute o seguinte comando  para iniciar

$ docker-compose up -d

-para detener o contenedor 
$ docker-compose down --volumes



Para ingressar só precisa ingressar em  http://localhosta   e iniciar a instalação do wordpress


Pronto já tem instalado o wordpress em um container pode instalar multiplos wordpress no seu sistema so precisa mudar os portos do phpadmin, mysql e php. 
