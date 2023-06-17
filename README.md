# Python-RanqueamentoDePaginas
Esta é uma das minhas tarefas finais da especialização Python for Everybody da Universidade de Michigan. O projeto utiliza tecnologias como Python, SQLite e Web Scraping para criar uma versão simples do ranqueamento de páginas do Google, produzindo, ao final, visualização em gráfico utilizando d3.js. Certificado de Conclusão: https://www.coursera.org/account/accomplishments/certificate/ELZCSB9P93R8

![PageRankMap](https://github.com/jvictorlopez/Python-RankingDePaginas/assets/124679867/335aac1f-5913-4be1-9742-b531b2b6f2fb)

Caso queira, baixe e utilize o código para produzir visualização com seu url de escolha, seguindo o passo a passo abaixo.

Na minha execução, optei por utilizar o site da minha universidade, Unifor.

# Passo a Passo
1. Seguindo as instruções do mapa demonstrado acima, executo primeiramente o código spider.py, utilizando como prompt meu url de escolha, no caso, https://www.unifor.br/
Em seguida, peço que o programa processe 150 páginas. O processo leva alguns minutos.
2. Executo o código sprank.py, responsável por rankear as páginas por critérios, rodando 150 iterações.
3. Executo o código spdump.py, recebendo 98 linhas da tabela gerada no arquivo .sqlite (o if statement reduz a visualização das linhas para 50).
![PageRankDump](https://github.com/jvictorlopez/Python-RankingDePaginas/assets/124679867/1527ba59-7531-461d-b834-182637185a68)

4. Executo o código spjson.py, criando o output JSON em spider.js, escolhendo 25 nós (nodes) para visualização.
Logo após, executo force.html para me redirecionar ao site, produzindo a visualização desejada.
![uuuuu](https://github.com/jvictorlopez/Python-RankingDePaginas/assets/124679867/366f8641-4927-405b-a13b-bbcfa7435f1e)

