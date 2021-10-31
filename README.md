# alura-docker
App para exemplicar os seguintes conceitos cobertos no curso:

    1. App nodejs rodando em 3 containers.
    2. Servidor web nginx funcionando como servidor de arquivos estáticos (imagens, css, htmls) e também loadbalancer para balancear a carga entre os 3  containers que estão sendo executados.
    3. Conceito docker-compose com instruções para fazer build da imagem do nginx com as configurações do servidor do nginx necessárias e também o build dos das imagens da aplicação. Organizar a ordem de execução aplicando o conceito de depends on para que os serviços que possuem dependencia respeitem a ordem de inicialização.
    4. Conceito de rede utilizando docker, sendo possível acessar recursos de rede utilizando nome(dns) ao invés de IP. Obs.: Quando se trabalha com rede diferente da rede default do docker é possível utilizar esse recurso de dns para acessar os containers que estão na mesma rede docker.
    5. Criação de arquivo dockerfile para compilar a aplicação nodejs e também para o servidor nginx com as configurações necesárias para o funcionamento do loadbalancer e também arquivos estáticos.

