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
## :anotações: Descrição
Descrição curta sobre o que seu projeto faz:
Nesse módulo, foi solicitado que fosse desenvolvido um projeto em grupo, em que temos como nosso cliente o Hospital das Clínicas (Faculdade de Medicina-USP). Este projeto, trata-se da criação de um modelo preditivo, o qual tem como objetivo predizer o tempo de sobrevida das mulheres com câncer de mama. Sendo assim, nos foram fornecidas diversas bases de dados dessas pacientes, com as quais foram realizadas as seguintes tarefas: pré-processamento dos dados, seleção das features mais importantes, criação de métodos para preenchimento de nulos e de algoritmos para predição.
De um a dois parágrafos sobre o que é seu projeto e o que ele faz:
O projeto desse módulo trata-se de um modelo preditivo, no qual temos o Hospital das Clínicas como o nosso cliente. Foi solicitado que criássemos uma modelo preditivo, com o objetivo de fornecer tanto para os médicos, como para as pacientes com câncer de mama, o tempo de sobrevida.
Sendo assim, com o nosso modelo de predição, será possível relatórios e prognóticos mais precisos e informativos para um melhor acompanhamento de cada paciente. Portanto, com o auxílio do Google Colab, diversos modelos foram criados, os quais possuem taxas de acertos e de erros. Logo, o modelo que obteve como resultado a maior acurácia, será o modelo utilizado para suprir essa necessidade. Sendo assim, o modelo selecionado foi a Árvore de Decisão, a qual obteve uma acurácia de 88%. 
Portanto, a ferramenta que será disponibilizada para suprir esse problema de demora no tempo dos prognósticos, essa ferramenta veio para dar como retorno às pacientes, um prognóstico. O software do modelo preditivo, funciona através de um formulário, que possui algumas features, as mais importantes que foram seleiconados, e a partir dessas features, as pacientes preenche de acordo com os dados delas, os dados são armazenados no formulário que tem como objetivo predizer o resultado do tempo de sobrevida da paciente com base nos seus dados. 

## :pasta_de_arquivos: Estrutura de pastas
```
-Raiz
|
|--> pasta 1 —> contém todos os algoritmos de tratamento de dados
    |--> FillEmptyAlgorithms.ipynb
    |--> FillEmptyAlgorithmsWithDecisionModel.ipynb
    |--> ClassifierAlgorithm.ipynb
    |--> seleção_features.ipynb
|-->imagens —> Nesta pasta temos as imagens do projeto, portanto todas as capturas de tela da nossa aplicação web, desde quando se inicia o login, até o relatório final estão nessa pasta.
|-->src —> Contém todo o código fonte do sistema. Existem duas pastas, Backend (código do servidor) e Frontend (código da página web.mj).
|--> pasta 2 -> contém todos os modelos preditivos: Árvore de Decisão, Random Forest, Regressão Logítica, KNN e Naive Bayes.
    |--> DecisionTree.ipynb
    |--> randomForest.ipynb
    |--> regressao_logistica.ipynb
    |--> KNN.ipynb
    |--> naive_bayes.ipynb
| README.md —> Arquivo que serve como guia e explicação geral sobre seu projeto.
```

## :computador: Configuração para desenvolvimento
Aqui encontram-se todas as instruções necessárias para a instalação de todos os programas, bibliotecas e ferramentas imprescindíveis para a configuração do ambiente de desenvolvimento.
1. Acessar o Google Colaboratory (colab) no browser: 
2. Abrir o colab 'formulário'.
3. Após isso, deve-se preencher o formulário do colab com os dados da paciente para obter-se o resultado de seu tempo de sobrevida.
4. O resultado do tempo de sobrevida será apresentado ao final da execução.

Aqui encontram-se todas as instruções necessárias para a instalação de todos os programas, bibliotecas e ferramentas imprescindíveis para a configuração do ambiente de desenvolvimento.
1. Baixar e instalar o node.js: https://nodejs.org/pt-br/ (versão 16.15.1 LTS)
2. Clone o repositório em questão.
3. No modo administrador, abra o "prompt de comando" ou o "terminal" e, após, abra a pasta "src/backend" no diretório raiz do repositório clonado e digite o segundo comando:
npm install
Isso instalará todas as dependências definidas no arquivo package.json que são necessárias para rodar o projeto. Agora o projeto já está pronto para ser modificado. Caso ainda deseje iniciar a aplicação, digite o comando abaixo no terminal:
npm start
5. Agora você pode acessar a aplicação através do link http://localhost:1234/
6. O servidor está online.

## :arquivo: Histórico de lançamentos
* 0.0.1 - 22/04/2022
    * Primeiro Commit do grupo;
    * Organização da pasta Github, contendo as pastas necessárias, cuja cópia foi feita, com isso, foi direto para a máquina de cada membro do grupo.
* 0.1.0 - 01/05/2022
    * Adicionado a versão 1.1 do WAD;
* 0.1.1 - 07/05/2022
    * Adicionado o modal de introdução;
* 0.1.2 - 09/05/2022
    * Adicionado o padrão de design do projeto e o código Frontend;

## :prancheta: Licença/License
<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/Spidus/Teste_Final_1">WEB POWER</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://www.yggbrasil.com.br/vr">Inteli, André Luís, Camila Anacleto, João Gonzalaes, Larissa Carvalho, Luiz Granville, Ueliton Rocha</a> is licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>
## :chapéu_de_formando: Referências
Aqui estão as referências usadas no projeto:
1. https:
2. https:
3. https:
4. https:
5. https:
6. https:
7. https:
8. https:
9. https:
10. https:
11. https:
12. https:
13. https:
14. https:
