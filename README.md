<h1> BANCO DE DADOS - TRABALHO EM GRUPO - MÓDULO 4 </h1> 

 <p> O objetivo desse projeto é montar um dashboard com base
no conjunto de dados que nos foi disponibilizado
pela Resilia. Após escolher qual tema, iremos analisar
e manipular esses dados utilizando a ferramenta MySQL Workbench.</p>


![image](https://s2.glbimg.com/gt1wO8FBpPkdDUMSF9pMoiK08ww=/0x0:2000x1333/924x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_bc8228b6673f488aa253bbcb03c80ec5/internal_photos/bs/2022/k/a/qfdzbVQIKDB7XfJGV4nQ/habilidades-basquete-ge.jpg)


<h2> 📢  REQUISITOS e PASSO A PASSO: </h2>

 <p> 🏀 Ideação/Brainstorm sobre perguntas que podem ser
respondidas pelos dados: Análise o conjunto de dados
selecionado para que as perguntas sejam pertinentes. </p>
 <p> 🏀 Estruturar o esquema do banco de dados:
A partir da avaliação do conjunto de dados fornecidos,
modelar as tabelas do banco. Não é necessário mapear
todas as colunas de todas  as tabelas. 
Mantenha sua implementação simples construindo um modelo que
atende às perguntas elaboradas pelo grupo.</p> 
 <p> 🏀 Realizar carga no banco: Com base no esquema
desenhado e criado, subir os dados presentes nos arquivos
para o banco de dados a fim de verificar o funcionamento da
solução encontrada.</p>
 <p> 🏀 Criar visualizações dos dados com base nas perguntas
elaboradas utilizando planilhas. </p> 

 <p> 🏀 Montar uma apresentação a partir das perguntas e análise
exploratória feita em cima do conjunto de dados selecionados. </p>

<h2> UM POUCO SOBRE O TEMA: NBA </h2>
 <p> ❯ NBA (National Basketball Association) é considerada a principal
liga de basquete do mundo. Foi fundada em junho de 1946, em Nova York
com o nome BAA. </p> 
 <p> É uma liga profissional de basquetebol dos Estados Unidos
e Canadá, com 30 franquias no total, sendo 29 equipes nos Estados Unidos e 1
representando o Canadá, a Toronto Raptors.  </p>


![image](https://s2.glbimg.com/htXio_Xo64203-jst1l3aSnPwDA=/0x0:1080x608/984x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_bc8228b6673f488aa253bbcb03c80ec5/internal_photos/bs/2022/B/H/gdyewvQ36SLycZRwl2AA/carrossel-apresentacao-da-temporada-nba.jpg)


Como funciona a NBA?

Os 30 times da NBA são divididos entre duas conferências: Leste e Oeste. Ou seja, as equipes são distribuídas de acordo com sua localização geográfica. Cada conferência tem 15 equipes, que compõem três divisões com cinco representantes.

Conferência Leste :

A Conferência Leste da NBA conta com a Divisão do Atlântico, a Divisão Central e a Divisão Sudeste. As 15 equipes dessa conferência são divididas da seguinte forma:

Divisão do Atlântico :

Boston Celtics,
Brooklyn Nets,
New York Knicks,
Philadelphia 76ers,
Toronto Raptors
<hr>
Divisão Central :

Chicago Bulls,
Cleveland Cavaliers,
Detroit Pistons,
Indiana Pacers,
Milwaukee Bucks

<hr>
Divisão Sudeste :

Atlanta Hawks,
Charlotte Hornets,
Miami Heat,
Orlando Magic,
Washington Wizards
<br>
<hr>
Conferência Oeste :

Na Conferência Oeste da NBA, estão as equipes da Divisão Noroeste, Divisão do Pacífico e Divisão Sudoeste.

Divisão Noroeste :

Denver Nuggets,
Minnesota Timberwolves,
Portland Trail Blazers,
Oklahoma City Thunder,
Utah Jazz,
Divisão do Pacífico,
Golden State Warriors,
Los Angeles Clippers,
Los Angeles Lakers,
Phoenix Suns,
Sacramento Kings

<hr>
Divisão Sudoeste :

Dallas Mavericks,
Houston Rockets,
Memphis Grizzlies,
New Orleans Pelicans,
San Antonio Spurs

<hr>
<h2>O QUE USAMOS:</h2>

 <p><img src="https://img.shields.io/badge/-Mysql-orange?style=for-the-badge&logo=mysql&logoColor=white"></p>
 <p><img src="https://img.shields.io/badge/-Github-black?style=for-the-badge&logo=Github&logoColor=white"></p>
 <p><img src="https://img.shields.io/badge/-Excel-36802d?style=for-the-badge&logo=excel&logoColor=white"></p>

<hr>
<h1> Modelo Relacional </h1>

<h4>O Modelo Relacional sobre seus antecessores é a
representação simples dos dados e a facilidade com que consultas complexas podem ser
expressas. Antes da estrutarar o banco de dados por boas práticas de programação deve-se fazer um modelo db.<h4>


<img src="https://raw.githubusercontent.com/themonsteer/db-nba/main/diagrama-model/diagrama.PNG">


<hr>

  <h1> 📝Consultas</h1>

<h4>Na documentação foi realizado a extração das informação, que seria necessárias para construção do nosso db, com isto o squad construiu as consultas para que o banco de dados realizasse o retorno.</h4>

🏀 Ano de Fundação(times mais antigos)

🏀 Derrotas (Top 10 dos times com derrotas na data de classificação 24/02/2020)

🏀 Vitórias(Times com mais vitórias)

🏀 Vitórias fora de casa(Top 6 Times com mais vitórias fora de casa)

<h1>Retorno das Consultas</h1>
  
  <h1> TIMES COM MAIS VITÓRIAS </h1>
<img src = "https://github.com/themonsteer/db-nba/blob/main/img/times-mais-vitorias.PNG?raw=true">
  <h1> TIMES COM MAIS VITÓRIAS FORA DE CASA </h1>
<img src = "https://github.com/themonsteer/db-nba/blob/main/img/times-vitorias-fora.PNG?raw=true">
  <h1> TIMES COM MAIS DERROTAS ATÉ 01/03/2020 </h1>
<img src = "https://github.com/themonsteer/db-nba/blob/main/img/times-mais-derrotas.PNG?raw=true">
  <h1> TIMES MAIS ANTIGOS </h1>
<img src = "https://github.com/themonsteer/db-nba/blob/main/img/times-mais-antigos.PNG?raw=true">
  <h1> MAIORES ARENAS</h1>
<img src = "https://github.com/themonsteer/db-nba/blob/main/img/maiores-arenas.PNG?raw=true">
  
<hr>
  
  <h1>📊 Gráficos</h1>
 
 <h4>Após a realização da extração da documetação e realizada as consultas, importamos as consultas para o Power Bi para modelagem dos gráficos. Os gráficos são extremamente importante para uma vizualização mais ampla dos dados, atrativo para o endentimento de qualquer pessoa e uma estrutura básica para apresentações. </h4>
   
  <h1> TIMES COM MAIS VITÓRIAS </h1>
<img src = "https://github.com/themonsteer/db-nba/blob/main/graficos/time-mais-vitorias.PNG?raw=true">
  <h1> TIMES COM MAIS VITÓRIAS FORA DE CASA </h1>
<img src = "https://github.com/themonsteer/db-nba/blob/main/graficos/times-vitorias-fora.PNG?raw=true">
  <h1> TIMES COM MAIS DERROTAS ATÉ 01/03/2020 </h1>
<img src = "https://github.com/themonsteer/db-nba/blob/main/graficos/times-mais-derrotas.PNG?raw=true">
  <h1> TIMES MAIS ANTIGOS </h1>
<img src = "https://github.com/themonsteer/db-nba/blob/main/graficos/times-mais-antigos.PNG?raw=true">
  <h1> MAIORES ARENAS</h1>
<img src = "https://github.com/themonsteer/db-nba/blob/main/graficos/maiores-arenas.PNG?raw=true">
  
 <hr>
  
  <h1>🏀TIME<h1>
    
<p> Links:</p>

<h2>Pedro Souza: </h2>
<p> <a href="https://github.com/themonsteer" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" style="border-radius: 30px"></a> </p>
   
<p>  <a href="https://www.linkedin.com/in/pedro-souza-a382b3182" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" style="border-radius: 30px"></a> </p>

<h2>Caio Pereira:</h2>
<p>  <a href="https://github.com/caaiopereira" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" style="border-radius: 30px"></a> </p>
<p>  <a  href="https://www.linkedin.com/in/caio-pereira-oliveira" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" style="border-radius: 30px></a> </p>

<h2>Luis Henrique:</h2>
<p>  <a href="https://github.com/Luis-Henrique-Lima" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" style="border-radius: 30px"></a> </p>
<p>  <a  href="https://www.linkedin.com/in/lu%C3%ADs-henrique-santos" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" style="border-radius: 30px></a> </p>

<h2>Pablo Miceli:</h2>
<p>  <a href="https://github.com/psmiceli" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" style="border-radius: 30px"></a> </p>
<p>  <a  href="https://www.linkedin.com/in/pablo-miceli-8bb15516" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" style="border-radius: 30px></a> </p>
