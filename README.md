### Running

```
docker-compose up -d
```

### Restart

```
docker-compose stop && docker-compose up -d
```

1. criação do docker-compose com os containers de banco e aplicação
2. criação de banco de dados e tabela baseado na estrutura de dados do arquivo .csv
3. criação de script em python que lê o arquivo .csv, conecta no mysql e persiste na tabela criada no passo 2
4. executa o docker-compose para subir os containers, preparando o banco e estrutura, e em sequência executando o script em python
