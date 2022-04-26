# DesafioNodeJsNginx

## Desafio Nginx com Node.Js + Mysql

- Para executar, basta acessar a pasta `nginx-with-nodejs` e executar com `docker-compose up`
- Veja na imagem abaixo que caso a tabela `people` ainda não exista, ela é criada no início da aplicação NodeJs, além de inserir o registro que é listado no endpoint `/`
- Criei endpoints adicionar como `[GET] /query` e `[POST] /command/:name`

##

### Characteristics:

- :heavy_check_mark: **Docker + docker-compose** (volumes, networks e mais)
- :heavy_check_mark: **NodeJs** (http server with **Express**)
- :heavy_check_mark: **Nodemon** (usado para que ocorra o "live-reload" em modificações feitas na aplicação NodeJs, sem precisar reiniciar o container manualmente)
- :heavy_check_mark: **Dockerize** (usado para que o container do NodeJs aguarde o container do Mysql estar disponível)
- :heavy_check_mark: **MySql**
- :heavy_check_mark: **Nginx** (como proxy-reverso para a aplicação http em NodeJs)
- :heavy_check_mark: **Nodemon**
