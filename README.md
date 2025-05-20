Esse aplicativo em Python realiza uma análise exploratória de dados sobre jogadores de futebol do Brasileirão, com base em um arquivo CSV (BRA_players.csv). Ele fornece um menu interativo com várias funcionalidades para exibir, filtrar e comparar dados dos jogadores e clubes. Abaixo está a descrição de cada funcionalidade:

⚙️ Funcionalidades do App:
✅ 1. Clubes + Valiosos
Lista os 10 clubes com maior valor de mercado somado entre seus jogadores.

Os valores são ordenados de forma decrescente e exibidos com formatação monetária (pt_BR).

✅ 2. Jogadores: +Jovens e +Experientes
Mostra os 10 jogadores mais jovens e os 10 mais experientes.

Cada lista apresenta o nome, clube e idade.

✅ 3. Compara Clubes: Média de Idades
Solicita o nome de dois clubes.

Calcula e exibe a média de idade dos jogadores de cada um.

Caso o clube não exista, exibe uma mensagem apropriada.

✅ 4. Pesquisa por Nome do Jogador
Permite buscar jogadores com base em uma substring do nome.

Retorna todos os jogadores cujo nome contenha o texto informado, mostrando o nome e o clube.

✅ 5. Análise por Idade
Solicita uma idade e:

Lista os clubes que possuem jogadores com essa idade.

Lista os clubes que não possuem jogadores com essa idade.

Usa set() para garantir que os clubes listados não se repitam.

✅ 6. Finalizar
Encerra o aplicativo.
