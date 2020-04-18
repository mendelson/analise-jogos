# analise-jogos
Análise de uma amostra da base de dados de jogadores de uma plataforma de jogos online.

Temos aqui uma base de dados que representa alguns de nossos usuários e seus dados de jogo. A tabela players é formada pela identificação do jogador e sua data de cadastro. A tabela matchmaking_stats_summary compõe todos os dados do jogador no nosso modo ranqueado. Por último, temos a tabela player_monthly_stats que contém um sumário mensal de toda a atividade dos jogadores no modo competitivo, que inclui tanto dados ranqueados quanto em outros modos competitivos.

players:
- player_id: identificação do jogador
- cadastrado_em: sua data de cadastro

matchmaking_stats_summary:
- player_id: identificação do jogador
- matches_played: quantidade de partidas jogadas
- total_wins: quantidade de vitórias
- total_loss: quantidade de derrotas
- mm_points: saldo de pontos
- kills: total de abates
- death: total de mortes
- assist: total de assistências
- hs: quantidade de tiros na cabeça
- created_at: data de criação do registro
- updated_at: data de última atualização do registro

player_monthly_stats:
- player_id: identificação do jogador
- game_mode: modo de jogo
- ref_date: data de referência
- total_played: quantidade de partidas
- kills: total de abates
- deaths: total de mortes
- assists: total de assistências
- wins: total de vitórias
- loss: total de derrotas
- headshots: quantidade de tiros na cabeça

A pasta *scripts* possui os scripts utilizados para gerar o banco de dados.

A pasta *figs* possui as imagens geradas neste projeto e a logo da plataforma de jogos.

Os arquivos *task.ipynb* and *Report.html* são o jupyter notebook e sua respectiva exportação em HTML.

O arquivo *Apresentação.pdf* é o arquivo utilizado para a apresentação oral do projeto.
