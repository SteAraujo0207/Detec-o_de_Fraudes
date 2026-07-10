# Deteccao de Fraudes em E-commerce

Sistema em SQL para detectar transações suspeitas em e-commerce, identificando compras acima de R$10.000, mudanças de país, dispositivos novos com valores altos e múltiplas tentativas recusadas. O script cria tabelas, insere dados, executa consultas e gera relatórios com views. Desenvolvido com SQLite. Teste no SQLite Online.

## Como executar

1. Acesse: https://www.mycompiler.io/view/BoPVZNj4lBe
2. Selecione SQLite no menu lateral
3. Copie o conteúdo do arquivo `deteccao_fraudes.sql`
4. Cole no editor e clique em Run

## Regras de negócio

- Transações acima de R$10.000 disparam alerta
- Compras em país diferente do cadastro disparam alerta
- Dispositivo novo com valor acima de R$1.000 disparam alerta
- Clientes com score abaixo de 400 são sinalizados
- Múltiplas tentativas recusadas sugerem ataque de força bruta

## Estrutura do projeto

O projeto está em um único arquivo SQL contendo:

- Criação das tabelas (clientes, dispositivos, transacoes, alertas_fraude)
- Inserção de dados de teste
- 7 consultas para análise de fraudes
- View para relatório diário

## Tecnologias utilizadas

- SQLite
- SQL (joins, subconsultas, views, indices)
- MyCompiler

## Autora

Stephanny Araujo - Estudante de Ciência da Computação


