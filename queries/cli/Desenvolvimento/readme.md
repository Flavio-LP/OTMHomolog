
# Padronização das documentações


## Banco de dados ( Owner: OTIMIZA)

Padrões a serem seguidos no desenvolvimento
    - Tabelas
       - Criar a tabela no seguinte formato: TTABELA_DE_DADOS
       - Inserir comentários nas colunas.

        ```
            BEGIN
              EXECUTE IMMEDIATE 'COMMENT ON COLUMN TTABELA_DE_DADOS.COLUNA IS ''DADOS X - REFERENCIA DA TABELA TTABELA_DE_DADOS'''; 
            END;
        ```


