# LH_CD_Diogo
Olá Meu nome é Diogo e apresento o código que desenvolvi para o desáfio da Lighthouse
Neste código utilizo técnicas e bibliotecas em linguagem de programção python, para fazer previsões e modelos para tomadas de decisões.
No inicio foi feito um tratamento dos dados dispostos, como transformação de string para int em algumas colunas, no caso a coluna Runtime. Foram removidas linhas com valores nulos.
Após, foi feito uma Análise Exploratória de Dados (EDA) vendo comparações par a par dos parametros, isso é 12 colunas de paramentros que caracterizam 713 filmes
Então, foi modelado e implementado um modelo de programação linear de pesquisa operacional, para escolher entre os 713 filmes, 10 filmes para serem recomendados a uma pessoa desconhecida, sem histórico de navegação
Depois o código busca usar aprendizado de máquina para primeiro responder se o parametro "overview" é util para prever o parametro "gênero" do filme, depois disso dado um conjunto de parametros de um novo filme fora da base de dados utilizada, é previsto a nota IMDB (um dos parametros), através do aprendizado de máquina.
O código está no arquivo LightHouse.pynb é a primeira vez que uso o github e não sei como exportar modelos .plk ainda, mas toda a analise e a respostas das perguntas estão no código feito no colab
