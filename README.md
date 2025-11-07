# Farmácia - Projeto Final Bloco 02

## 1. Descrição

A FarmaBelle faz parte do Projeto Final Bloco 02 - Backend Java Spring Boot.

Entre os principais recursos que uma Farmácia oferece, destacam-se:

- Usuário: representa os usuários que utilizam o sistema.
- Produtos: os produtos cadastrados no sistema.
- Categorias: as categorias dos produtos.5. Tecnologias utilizadas

| Item                          | Descrição       |
| ----------------------------- | ----------------|
| **Servidor**                  | Apache Tomcat   |
| **Linguagem de programação**  | Java            |
| **Framework**                 | SpringBoot      |
| **ORM**                       | JPA + Hibernate |
| **Banco de dados Relacional** | MySQL           |

------

## 6. Requisitos

<br />

Para executar os códigos localmente, você precisará:

- [Java JDK 17+](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
- Banco de dados [MySQL](https://dev.mysql.com/downloads/)
- [STS](https://spring.io/tools)
- [Insomnia](https://insomnia.rest/download) 

<br />

## 7. Como Executar o projeto no STS

<br />

### 7.1. Importando o Projeto

1. Clone o repositório do Projeto farmacia dentro da pasta do *Workspace* do STS

```bash
git clone https://github.com/misoliv/projeto_final_bloco_02
```

2. **Abra o STS** e selecione a pasta do *Workspace* onde você clonou o repositório do projeto
3. No menu superior do STS, clique na opção: **File 🡲 Import...**
4. Na janela **Import**, selecione a opção: **General 🡲 Existing Projects into Workspace** e clique no botão **Next**
5. Na janela **Import Projects**, no item **Select root directory**, clique no botão **Browse...** e selecione a pasta do Workspace onde você clonou o repositório do projeto
6. O STS reconhecerá o projeto automaticamente
7. Marque o Projeto Final Bloco 02 no item **Projects** e clique no botão **Finish** para concluir a importação

<br />

### 7.2. Executando o projeto

1. Na Guia **Boot Dashboard**, localize o  **Projeto Final Bloco 02**
2. Selecione o **Projeto Final Bloco 02**
3. Clique no botão **Start or Restart** <img src="https://i.imgur.com/wdoZqWP.png" title="source: imgur.com" width="4%"/> para iniciar a aplicação
4. Caso seja perguntado se você deseja autorizar o acesso ao projeto via rede, clique no botão **Permitir Acesso**
5. Acompanhe a inicialização do projeto no console do STS
6. Verifique se o banco de dados `db_farmacia` foi criado corretamente e se as tabelas foram geradas automaticamente.
7. Utilize o [Insomnia](https://insomnia.rest/) para testar os endpoints.

<br />

> [!TIP]
>
> Ao acessar a URL `http://localhost:8080` em seu navegador, a interface do Swagger será carregada automaticamente, permitindo a visualização e a interação com os endpoints da API, bem como a consulta dos modelos de dados utilizados.

<br />

## 8. Contribuição

<br />

Este repositório é parte de um projeto educacional, mas contribuições são sempre bem-vindas! Caso tenha sugestões, correções ou melhorias, fique à vontade para:

- Criar uma **issue**
- Enviar um **pull request**
- Compartilhar com colegas que estejam aprendendo Java!

<br />

##  9. Contato

<br />

Desenvolvido por [**Luana**](https://github.com/LuVicaria)
Para dúvidas, sugestões ou colaborações, entre em contato via GitHub ou abra uma issue!