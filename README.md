# Inteli - Instituto de Tecnologia e Liderança

<p align="center">
<a href= "https://www.inteli.edu.br/"><img src="https://www.inteli.edu.br/wp-content/uploads/2021/08/20172028/marca_1-2.png" alt="Inteli - Instituto de Tecnologia e Liderança" border="0"></a>
</p>

# Tempo de sobrevida das pacientes

## Smart Health

## Integrantes:
- <a href="https://www.linkedin.com/in/andrelessajr/">André Luís Lessa Junior</a>
- <a href="https://www.linkedin.com/in/camilaanacleto/">Camila Fernanda de Lima Anacleto</a>
- <a href="https://www.linkedin.com/in/jo%C3%A3o-lucas-delistoianov-gonzalez-b0501922a/">João Gonzales</a>
- <a href="https://www.linkedin.com/in/carvalholari/">Larissa Gouveia de Carvalho</a>
- <a href="https://www.linkedin.com/in/luiz-granville-898780209/">Luiz Francisco Granville</a>
- <a href="https://www.linkedin.com/in/uelitonrocha">Ueliton Moreira Rocha</a>

## 📝 Descrição

Descrição curta sobre o que seu projeto faz:

Nesse módulo, foi solicitado que fosse desenvolvido um projeto em grupo, em que temos como nosso cliente o Hospital das Clínicas (Faculdade de Medicina-USP). Este projeto, trata-se da criação de um modelo preditivo, o qual tem como objetivo predizer o tempo de sobrevida das mulheres com câncer de mama. Sendo assim, nos foram fornecidas diversas bases de dados dessas pacientes, com as quais foram realizadas as seguintes tarefas: pré-processamento dos dados, seleção das features mais importantes, criação de métodos para preenchimento de nulos e de algoritmos para predição.

De um a dois parágrafos sobre o que é seu projeto e o que ele faz:

O projeto desse módulo trata-se de um modelo preditivo, no qual temos o Hospital das Clínicas como o nosso cliente. Foi solicitado que criássemos uma modelo preditivo, com o objetivo de fornecer tanto para os médicos, como para as pacientes com câncer de mama, o tempo de sobrevida.
Sendo assim, com o nosso modelo de predição, será possível relatórios e prognóticos mais precisos e informativos para um melhor acompanhamento de cada paciente. Portanto, com o auxílio do Google Colab, diversos modelos foram criados, os quais possuem taxas de acertos e de erros. Logo, o modelo que obteve como resultado a maior acurácia, será o modelo utilizado para suprir essa necessidade. Sendo assim, o modelo selecionado foi o Random Forest, o qual obteve uma acurácia de 71%. 
Portanto, a ferramenta que será disponibilizada para suprir esse problema de demora no tempo dos prognósticos, essa ferramenta veio para dar como retorno às pacientes, um prognóstico. O software do modelo preditivo, funciona através de um formulário, que possui algumas features, as mais importantes que foram seleiconados, e a partir dessas features, as pacientes preenchem de acordo com os dados delas, os quais são armazenados no formulário que tem como objetivo predizer o resultado do tempo de sobrevida da paciente. 

## 📁 Estrutura de pastas
```
-Raiz
|
| --> Documentação -> Contém toda a documentação do projeto
    |--> Versões antigas -> Contém versões anteriores
        | --> Documentação_Projeto_Módulo 3_Grupo 2_v1.docx.pdf
        | --> Documentação_Projeto_Módulo 3_Grupo 2_v2.docx.docx
    | --> Documentação_Projeto_Módulo 3_Grupo 2.docx
    | --> Documentação_Projeto_Módulo 3_Grupo 2.docx.pdf
| --> Notebook -> Contém todos os algoritmos
    |--> Modelo final —> contém todos os algoritmos de tratamento de dados e o modelo baixado
        |--> data_process.ipynb
        |--> rf_model.pkl
        |--> user_forms.ipynb
    |--> Predições -> contém todos os modelos preditivos: Árvore de Decisão, Random Forest, Regressão Logítica, KNN e Naive Bayes.
        |--> DecisionTree.ipynb
        |--> KNN.ipynb
        |--> naive_bayes.ipynb
        |--> randomForest.ipynb
        |--> regressao_logistica.ipynb
| README.md —> Arquivo que serve como guia e explicação geral sobre seu projeto.
```

## 💻 Configuração para desenvolvimento

Aqui encontram-se todas as instruções necessárias para a instalação de todos os programas, bibliotecas e ferramentas imprescindíveis para a configuração do ambiente de desenvolvimento.
1. Acessar o Google Colaboratory (colab) no browser: https://colab.research.google.com/drive/12c2rKzggvMjSS6rWPEYVdb3VY07AwSqj#scrollTo=EI9Y3xQjGQEr.
2. Dirija-se a seção "Formulário para o usuário realizar a predição".
3. Após isso, deve-se preencher o formulário com os dados da paciente.
4. Os dados do formulário serão armazenados, então basta executar todo o colab para obter-se o resultado de seu tempo de sobrevida.
5. Para executar todo o colab, basta clicar em ambiente de execução > executar tudo ou Ctrl+F9.
6. Após esse procedimento, o resultado do tempo de sobrevida será apresentado ao final da execução, podendo ser classificado como baixo, médio ou alto.

## 🗃 Histórico de lançamentos

* 0.0.1 - 14/08/2022
    * Documentação Projeto Grupo 2;
    * Adição no documento de: Análise SWOT, Value Proposition Canvas, 5 forças de Porter, Personas, Contexto da Indústria, Jornada do Usuário, Planejamento Geral da Solução, Matriz de Riscos, Proposta de Solução e Compreensão dos Dados.
* 0.1.0 - 29/08/2022
    * Atualização da documentação e inclusão do colab notebook;
    * Adição no documento de: Compreensão dos Dados, Resultados, Análise dos Resultados, Algoritmos escolhidos e Estratégia de Avaliação.
* 0.1.1 - 11/09/2022
    * Modelo de predicao v1; Classificacao do Follow Up Date;
    * Adição no documento dos modelos: Naive Bayes, Regressão Logística, Random Forest, K-Nearest Neighbors (KNN), Árvore de Decisão e Análise de Resultados.
* 0.1.2 - 12/09/2022
    * Organização das pastas
* 0.1.3 - 25/09/2022
    * Atualização da documentação, itens 4.4 e 4.5
    * Atualização da seleção de features, Testes de diversos modelos e Atualização dos métodos escolhidos

## 📋 Licença/License

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/Spidus/Teste_Final_1">WEB POWER</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://www.yggbrasil.com.br/vr">Inteli, André Luís, Camila Anacleto, João Gonzalaes, Larissa Carvalho, Luiz Granville, Ueliton Rocha</a> is licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>

## 🎓 Referências

Aqui estão as referências usadas no projeto:
1. https://scikit-learn.org/stable/
2. https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html?highlight=gridsearch#sklearn.model_selection.GridSearchCV
3. https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html?highlight=logistic+regression
4. https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html?highlight=random+forest
5. https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html?highlight=decision+tree
6. https://scikit-learn.org/stable/modules/classes.html?highlight=naive+bayes#module-sklearn.naive_bayes
7. https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html
8. https://scikit-learn.org/stable/modules/grid_search.html#randomized-parameter-search
9. https://sigmoidal.ai/como-salvar-seu-modelo-de-machine-learning/
10. https://www.youtube.com/watch?v=W7MfsE5av0c
11. https://www.digitalhouse.com/br/blog/arvore-de-decisao/#:~:text=O%20conceito%20de%20entropia%20dentro%20de%20uma%20%C3%A1rvore%20de%20decis%C3%A3o&text=A%20entropia%20%C3%A9%20uma%20forma,%C3%A9%20dito%20de%20menor%20entropia.
12. https://stackoverflow.com/
13. https://numpy.org/install/
14. https://matplotlib.org/stable/
15. https://seaborn.pydata.org/
16. https://python.readthedocs.io/en/stable/library/pickle.html
