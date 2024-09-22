Previsão de Preço de Veículos Usados com Random Forest
Este repositório contém um projeto em Python desenvolvido para prever o preço de veículos usados com base em diversas características, como quilometragem, tipo de combustível e potência, utilizando o modelo de aprendizado de máquina Random Forest. O foco principal deste projeto é a aplicação de técnicas de Machine Learning para prever o valor de veículos e otimizar o desempenho do modelo por meio da busca de hiperparâmetros com GridSearchCV.

Objetivo
O objetivo deste projeto é prever o preço de veículos usados a partir de um conjunto de dados contendo suas principais características, como potência, quilometragem e tipo de combustível. Para isso, foi utilizado o algoritmo Random Forest para realizar a tarefa de regressão e o Erro Absoluto Médio (MAE) como métrica de avaliação da precisão das previsões.

Tecnologias e Ferramentas Utilizadas
Python 3.x
Pandas: Para manipulação e análise de dados.
Scikit-learn: Para aplicar o modelo Random Forest, GridSearchCV, e calcular o MAE.
Random Forest: Modelo de aprendizado de máquina utilizado para prever os preços.
GridSearchCV: Técnica para otimizar os hiperparâmetros do modelo.

Dataset
Este projeto utiliza um conjunto de dados chamado autos.csv, que contém informações detalhadas de veículos usados, como:

Preço
Potência do motor
Quilometragem
Tipo de combustível
Tipo de câmbio
Certifique-se de que o arquivo autos.csv está no diretório correto ou ajuste o caminho no código, se necessário.

Considerações Finais
Embora Random Forest e GridSearchCV tenham sido usados com sucesso neste projeto, é importante notar que existem outras técnicas mais apropriadas e avançadas para esse tipo de problema de regressão. Modelos como XGBoost, LightGBM e redes neurais profundas podem oferecer resultados ainda mais precisos e rápidos. No entanto, neste projeto, Random Forest foi utilizado para fins de teste e aprendizado, explorando sua aplicabilidade em previsão de preços de veículos.

Contribuição
Contribuições são bem-vindas! Se você quiser melhorar este projeto ou adicionar novas funcionalidades, fique à vontade para abrir um pull request.

Licença
Este projeto está sob a licença MIT.
