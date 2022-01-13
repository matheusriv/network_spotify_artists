# Network Spotify Artists

Neste repositório é feito um estudo e uma rede de concorrência utilizando os nomes dos artistas das músicas de playlists encontradas num dataset. Para isso foi usado a linguagem de programação Python e pacotes para manusear os dados e gerar gráficos. Para a construção da rede foi utilizado o Spotify Million Playlist Dataset, que contém 1.000.000 playlists criadas por usuários na plataforma Spotify. A rede de coocorrência é construida com os nós representando os artistas e uma aresta é adicionada entre dois artistas quando eles se encontram na mesma lista de reprodução.

## Dataset
  
O Spotify Million Playlist Dataset pode ser usado por pesquisadores interessados em explorar como melhorar a experiência de escuta musical. Essas listas de reprodução foram criadas durante o período de janeiro de 2010 a outubro de 2017. Cada lista de reprodução no MPD contém um título de lista de reprodução, a lista de faixas (incluindo os metadados da faixa), informações de edição (hora da última edição, número de edições da lista de reprodução) e outras informações diversas sobre a lista de reprodução.
   
O dataset está disponível neste [link](https://www.aicrowd.com/challenges/spotify-million-playlist-dataset-challenge). 
  
## Network

<center><img width="600" src="https://github.com/matheusriv/network_spotify_artists/blob/main/images/spotify_network.png"></center>
<center>
  
Para explorar o grafo visite esse [link](https://matheusriv.github.io/network_spotify_artists/network/).
 
A página é uma visualização da rede criada usando o software Gephi, um pacote de software de código aberto para análise de redes e grafos. A rede foi exportada com o plug-in de exportação Sigma do Gephi.
