# TREINAMENTO XML/JSON
#### Autor: Lucas Ribeiro

:sparkles:

Este treinamento foi criado para o evento da FIEC, neste pequeno projeto temos duas apis criadas para trabalhar com estruturas de dados XML e JSON.

# XML

No treinamento de XML, simulamos um cenario aonde uma empresa no ramo de games, fez uma solicitação para desenvolvermos uma api aonde ela lê cards com fatos interessantes em temas variados, para facilitar o nosso trabalho, em nossa equipe um desenvolver senior, fez toda implementação da lógica e criou uma versão demonstração para apresentarmos para o cliente, a nossa responsabilidade neste cenario é a criação do xml com esses dados.


### CARD EXEMPLO
```XML
<?xml version="1.0" encoding="UTF-8"?>
<content>
        <tema>NOME DO TEMA</tema>
        <imagem>ARQUIVO DE IMAGEM.JPG</imagem>
        <nome>NOME DO ASSUNTO</nome>
        <descricao>FATO INTERESSANTE</descricao>
</content>
```

### TEMA EXEMPLO
```XML
<?xml version="1.0" encoding="UTF-8"?>
<temas>
    <tema
        nome="NOME DO TEMA"
        titulo="COR DO TITULO"
        fundo="COR DO FUNDO"
        conteudo="COR DO FUNDO CONTÉUDO"/>
</temas>
```
<br>

# JSON

No Treinamento de JSON, simulamos um cenario aonde uma empresa no ramo de vendas online, esta criando um novo software que busca em sua base de dados, todos os livros disponiveis para a venda, para facilitar o nosso trabalho um desenvolvedor mais experiente, fez toda a implementação da lógica que lê este dados, a nossa obrigação nesta demanda é a criação do arquivo json com a estrutura correta para testar essa api.

### LIVRO EXEMPLO
```JSON
[
    {
        "imagem" : "ARQUIVO IMAGEM JPG",
        "nome" : "NOME DO LIVRO",
        "autor" : "NOME DO AUTOR",
        "ano" : "ANO LANÇAMENTO",
        "valor" : "VALOR DO LIVRO"
    }
]
```
