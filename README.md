# Ocorrências Aeronáuticas de Aviação Civil Brasileira

Cada notebook está nomeado de acordo com os arquivos utilziados e tipos de análises realizadas. Nessas análises foi possível observar:

- O ano de 2013 foi o que registrou mais ocorrências (654);
- O mês com mais registros de ocorrências é o mês de janeiro (mês de férias da maioria das pessoas);
- O estado de SP é o que tem mais ocorrências (1373), destas 848 são incidentes, 388 acidentes e 137 incidentes graves;
- Dentro do estado de SP, as cidades de SP, Guarulhos e Campinas são as 3 com maior número de ocorrências;
- O aeródromo com mais registros de ocorrências é o de Guarulho, seguido pelo Campo de Marte e Belo Horizonte;
- Os acidentes geralmente destroem as aeronaves ou as deixam com danos substanciais;
- 2012 foi o ano com aeronaves mais danificadas (401);
- Cessna Aircraft é o fabricante com mais registro de ocorrências;
- As aeronaves com mais registros de ocorrências foram fabricadas recentemente (2007-2012);
- O modelo PA34 é o que tem mais ocorrências e o modelo IPAN o que registrou mais acidentes;
- O motor pistão e aeronaves mono e bimotores são as que registraram mais ocorrências;
- Os anos 2011 e 2012 foram os que apresentaram mais fatalidades (110) seguido por 2016 (104);
- A principal causa das ocorrências e de acidentes são falhar do motor em voos;
- Fatores operacionais são responsáveis por 65.4% das ocorrências, enquanto fatores humanos 31.8%;
- O fator contribuinte com mais acidentes e ocorrências é o julgamento de pilotagem, seguido por aplicação de comandos;
- Algumas das recomendações encontradas são manutenção e segurança operacional das aeronaves e aeródromos;
- Análise com aprendizagem de máquina mostrou que é possível saber previamente a ocorrência de uma aeronave.

O notebook nomeado de Prevendo_Ocorrencia_Classificacao.ipynba está relacionado ao estudo preditivo envolvendo todos os anos a fim de saber a classificação de uam ocorrência (Acidente, Incidente ou Incidente Grave).Aqui também foi visto a correlação dos atributos e foi observado que as classes era desbalanceadas. Sendo assim, então foram criadas amostras artificiais utilizando técnicas de sobreamostragem (RandomOverSampler, SMOTE, ADASYN) e foi feito um benchmarking de 4 algoritmos clássicos de classificação (SVM, KNN, Rede Neural e XGBoost).


