## Unidade 2 - Trabalho 1

# Discentes:
- Natan Bastos de Morais
- Thiago Vinicius Cardoso Lopes

# Resumo

Neste notebook, aplicaremos os conhecimentos vistos no curso para analisar a rede
de co-autoria dos professores permanentes do Programa de Pós-Graduação em
Engenharia Elétrica e de Computação (PPgEEC) da UFRN (Universidade Federal do Rio Grande do Norte).
Utilizamos o aplicativo Gephi para gerar imagens de gráficos necessários para atender aos 3 requisitos propostos.

Requisito 1:
- Gerar uma figura para demonstrar a rede disponibilizada pelo professor. O tamanho do vértice deverá ser
proporcional a quantidade de vizinhos, enquanto as cores devem ser relacionadas com o Closeness ou Betweenness ou Eigenvector Centrality.


![closeness_centrality](https://github.com/user-attachments/assets/36ec6cac-63fb-46cf-8171-8c939653fd3c)


Descrição: Utilizamos o degree centrality para demonstrar o tamanho dos vértices e escolhemos o closeness centrality para as cores.
 

Requisito 2:
- A partir da rede, gerar uma figura destacando o k-core e o k-shell. O tamanho do vértice deverá ser
proporcional ao degree centrality.


![k_metrics](https://github.com/user-attachments/assets/e7a0cd5d-3849-4861-84bb-16970ea70476)


Descrição: Utilizamos o degree centrality para demonstrar o tamanho dos vértices e as cores são representadas pelas métricas k-shell e k-core da rede.


Requisito 3:
- Gerar uma figura onde o tamanho do vértice deve ser relacionado a uma métrica de livre escolha, enquanto as cores deverão ser relacionadas ao critério de comunidade. 
Por fim, a rede deverá estar em produção de forma análoga ao explicado na Semana 6. Ou seja, é necessário dar deploy dos arquivos.

https://thiagoclopes.github.io/netdeploy/

Descrição: Escolhemos o degree centrality para demonstrar o tamanho dos vértices e as cores são relaxionadas ao critério de comunidade pela métrica Modularity.


# Vídeo explicativo
LINK


# Conclusão
Através do Gephi, atendemos aos requisitos propostos no trabalho e aprimoramos nossos conhecimentos a respeito das métricas apresentadas em sala de aula:
- Closeness centrality
- Degree centrality
- Eigenvector centrality
- Betweness centrality
- K-shell
- K-core

E também fizemos na prática o deploy da rede na web. 
Para gravar o vídeo, utilizamos o Loom. 



