# Mini Banco de Dados em C  

Este projeto é uma implementação simplificada do **SQLite**, desenvolvida para aprendizado sobre **banco de dados, C, estruturas de dados** e conceitos de **baixo nível de sistemas operacionais**, como manipulação de arquivos e gerenciamento de memória.

---

## Como Rodar  

###  **Compilar o código**  
```
gcc dbema.c -o dbema
```
2️ Executar o banco de dados
```
./dbema banco.db
```

## Comandos Disponíveis

Inserir um registro
```
insert <id> <username> <email>
```

Consultar todos os registros
```
select
```
Sair do programa
```
.exit
```


## Testes Automatizados
Implementei testes usando RSpec, então é necessário ter Ruby instalado. Os testes estão localizados no arquivo spec/database_spec.rb.

Para rodar os testes
```
bundle exec rspec
```
Caso precise limpar o banco de testes antes de rodar
```
rm -f test.db
```
