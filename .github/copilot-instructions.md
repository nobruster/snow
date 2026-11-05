# Instruções do Projeto Snowflake

## Perfil
Este projeto utiliza Snowflake para engenharia de dados, consultas analíticas e automação.

## Regras SQL

- Nunca utilizar SELECT *
- Nomear todas as colunas explicitamente
- Priorizar CTEs para legibilidade
- Utilizar QUALIFY para remoção de duplicidades
- Evitar subqueries desnecessárias

## Convenções

- STG_* = Staging
- DIM_* = Dimensões
- FCT_* = Fatos
- VW_* = Views

## Performance

- Aplicar filtros o mais cedo possível
- Evitar CROSS JOIN
- Avaliar impacto de ORDER BY em grandes volumes
- Explicar possíveis gargalos de performance

## Respostas do Copilot

Ao gerar SQL:
- Explicar a lógica da solução
- Informar possíveis otimizações
- Seguir sintaxe Snowflake
- Comentar trechos complexos quando necessário
