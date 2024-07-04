Claro! Aqui está um exemplo de README em português, com as instruções ajustadas para armazenar as queries em arquivos .txt:

---

# Consultas SQL para Prática

Este repositório contém um conjunto de consultas SQL projetadas para ajudar você a melhorar suas habilidades em SQL. As consultas estão categorizadas em níveis médios e difíceis, cobrindo várias operações SQL, como joins, group by e expressões de tabela comum (CTEs). Essas questões são do livro Introdução à linguagem SQL de Thomas Nield, peugei o banco de dados que ele disponibilizou no github dele.

## Índice

- [Introdução](#introdução)
- [Consultas Médias](#consultas-médias)
- [Consultas Difíceis](#consultas-difíceis)
- [Uso](#uso)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Introdução

Este repositório inclui uma série de consultas SQL para um banco de dados de exemplo que inclui tabelas como `Artist`, `Album`, `Customer`, `Employee`, `Genre`, `Invoice`, `InvoiceLine`, `MediaType`, `Playlist`, `PlaylistTrack` e `Track`.

As consultas estão divididas em dois níveis:
- Médio
- Difícil

## Consultas Médias

1. **Listar os nomes dos álbuns e os nomes dos artistas correspondentes.**
   - [consulta1.txt](queries/consulta1.txt)

2. **Mostrar o total de vendas (soma de Total) por país.**
   - [consulta2.txt](queries/consulta2.txt)

3. **Encontrar todos os funcionários que reportam ao gerente com EmployeeId = 1.**
   - [consulta3.txt](queries/consulta3.txt)

4. **Listar o nome e a quantidade de faixas de cada playlist.**
   - [consulta4.txt](queries/consulta4.txt)

5. **Mostrar o nome dos clientes e a cidade onde moram.**
   - [consulta5.txt](queries/consulta5.txt)

## Consultas Difíceis

1. **Listar o nome dos clientes e o total de suas compras, ordenado pelo valor total de compras em ordem decrescente.**
   - [consulta6.txt](queries/consulta6.txt)

2. **Encontrar o nome dos clientes que compraram mais de 5 produtos diferentes.**
   - [consulta7.txt](queries/consulta7.txt)

3. **Mostrar a quantidade de faixas (tracks) por gênero, apenas para gêneros que têm mais de 20 faixas.**
   - [consulta8.txt](queries/consulta8.txt)

4. **Encontrar os nomes das faixas (tracks) e os nomes dos compositores cujas faixas têm mais de 5 minutos (300000 milissegundos).**
   - [consulta9.txt](queries/consulta9.txt)

5. **Mostrar os nomes dos álbuns que possuem mais de 10 faixas (tracks).**
   - [consulta10.txt](queries/consulta10.txt)

## Uso

1. Clone o repositório:
    ```sh
    git clone https://github.com/seuusuario/consultas-sql-pratica.git
    ```
2. Navegue até o diretório do repositório:
    ```sh
    cd consultas-sql-pratica
    ```
3. Abra seu editor SQL preferido e execute as consultas nos arquivos .txt contra seu banco de dados.

## Contribuição

Contribuições são bem-vindas! Se você tiver sugestões ou melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.
