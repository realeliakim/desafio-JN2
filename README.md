<p align="center">
  <img src="https://res.cloudinary.com/dte7upwcr/image/upload/blog/blog2/sites-para-criar-loja-virtual/image_11-jn2.jpg" alt="JN2_logo" height="120"/>
</p>
<h1 align="center">
  Desafio JN2
</h1>


<p align="center">
  <a href="https://www.linkedin.com/in/realeliakim/">
    <img alt="Linkedin" src="https://img.shields.io/badge/-Eliakim%20Aquino-0e76a8?label=Linkedin&logo=linkedin&style=flat-square"/>
  </a>
</p>

## :page_facing_up: Descrição

O desafio consiste na criação de um sistema de controle de clientes e suas respectivas placas de carro.


## :computer: Instalação

```bash
# Clone este repositório.
$ git clone https://github.com/realeliakim/desafio-JN2.git

# Vai para a pasta do projeto
$ cd pipedrive_bling

# Executa o sistema no docker no endereço: http://127.0.0.1:8080/
$ docker-composer up

```

## Endpoints

```bash
# Lista todos os clientes cadastrados.
> [GET]  /api/cliente

# Cadastra um novo cliente.
> [POST] /api/cliente

# Consulta informações de um cliente específico.
> [GET] /api/cliente/{id}

# Edição de um cliente existente.
> [PUT] /api/cliente/{id}

# Remoção de um cliente existente.
> [DELETE] /api/cliente/{id}

# Lista todos os clientes cadastrados, onde o número da placa do carro é igual ao informado.
> [GET] /api/consulta/final-placa/{numero}

```


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
