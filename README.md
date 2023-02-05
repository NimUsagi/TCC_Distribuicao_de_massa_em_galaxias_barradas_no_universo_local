# TCC_Distribuicao_de_massa_em_galaxias_barradas_no_universo_local
O Objetivo deste repositório é deixar acessível todos os passos da análise do meu TCC.

Sobre os arquivos:

Salo15(4629)+IRSA_S4G(2352)+Bouquin18(1931)+Buta15.csv -- União de 4 catálogos: Tabela 7, Salo et al. 2015; IRSA S4G Sheth et al. 2010; Tabela 1, 
Bouquin et al. 2018; Buta et al. 2015.

amostra_430.csv -- Tabela com 430 galáxias com componente de decomposição barra, inclinação menor que 65, qualidade de decomposição 5, com valor de 
distância catalogado e sem componete "disco+disco" em seu modelo de decomposição. Dados retirados da tabela "Salo15(4629)+IRSA_S4G(2352)+
Bouquin18(1931)+Buta15.csv", passos ilustrados em "Selecao_amostra_ideal.ipynb".

Selecao_amostra_ideal.ipynb -- Mostra os passos da seleção da amostra ideal que visa estudar a distribuição de massa em galáxias no universo local.
gera a tabela "amostra_370.csv".

Numero_galaxias_diferentes_cortes_de_massa.ipynb -- Ilustra como os critérios de cortes de massa influenciaram os tamanhos das amostras e chegaram ao 
valor que temos em nossas subamostras.

Analise_Tipo_Morfologico.ipynb -- Mostra os passos da analise de tipo morfológico em detalhes. Verifica a frequência de galáxias barradas. Verifica os falsos positivos e falsos negativos.

Analise_Decomposicao.ipynb -- Mostra os passos da analise da decomposição na banda 3.6um. Verifica o quão frequêntes são as componentes nos modelos de decomposição em diferentes cortes de massa. 

Analise_Distribuicao_Massa.ipynb -- Mostra os passos da anlise da distribuição de massa nas 430 galáxias da nossa amostra ideal, olhando para a massa relativa das componentes em quatro modelos de decomposição diferentes. Neste jupyter notebook também é feito o teste de hipótese em duas amostras de galáxias massivas. 
