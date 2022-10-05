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

que os hotéis parceiros da Hurb tenham acesso a sua página correspondente a sua conta de acesso, e então, após o login ter sido efetuado, conseguem ter acesso a plataforma para fazer a solicitação da antecipação de pagamento, escolhendo primeiramente para qual hotel quer solicitar, qual o valor que quer antecipar (consequentemente aparece quantas reservas são equivalentes a esse valor) e por último qual o tipo de demanda o usuário quer, podendo escolher entre (D+2, D+7, D+15). Caso ele escolha D+2, terá um desconto de 12% do total devido ao fornecedor, se for D+7, terá um desconto de 9% do total e se for D+15, terá um desconto de 6% do total devido ao fornecedor. Além de os hotéis parceiros conseguirem fazer o cadastro na plataforma para receber esse serviço, conseguem editar seus dados, adicionar os seus hotéis, podem solicitar como também acompanhar o status da solicitação das antecipações e podem visualizar seus histórico, o qual mostra o tipo da demanda escolhido, a data, o valor solicitado e o valor total.
## :pasta_de_arquivos: Estrutura de pastas
```
-Raiz
|
|-->documentos —> contém todos os documentos do projeto, principalmente o WAD.
 |-->outros
    |--> Hurb Web Power Style Guide.pdf
    |--> Pitch Módulo 2 - Web Power (Versão Final).pdf
    |--> Tabulação testes de funcionalidade - Registro dos testes.pdf
    |--> Web Power - Solicitação de Antecipação.mp4
 |--> T4_G3_V01_Web_application_document.pdf
 |--> T4_G3_V01_Web_application_document.docx —> Trata-se de uma documentação da nossa aplicação web, em que mencionamos a visão geral do projeto, a empresa que é nossa cliente, o problema, que é o fato das antecipações estarem ocorrendo de forma manual, portanto, com a nossa plataforma web, será possível realizar as antecipações de pagamento de forma digital. Nessa documentação também citamos os objetivos gerais, descrevemos a solução, mencionamos as partes interessadas, analisamos a indústria, o produto, o cenário, entre outros. É nessa documentação que contém a nossa Matriz SWOT, nossa Proposta de Valor, Matriz de Risco, Requisitos do Sistema, nossos Personas, Histórias dos usuários (user stories), Tecnologias Utilizadas, Análise de Dados, Manual do Usuário e do Administrador, Referências, entre outros.
|-->imagens —> Nesta pasta temos as imagens do projeto, portanto todas as capturas de tela da nossa aplicação web, desde quando se inicia o login, até o relatório final estão nessa pasta.
|-->src —> Contém todo o código fonte do sistema. Existem duas pastas, Backend (código do servidor) e Frontend (código da página web.mj).
 |-->Backend
         |--> controllers
             | index
         |--> database
            | cli
                  |--> mock.data
                  |--> show.data
                  |--> start
             | database
             | index
         |--> node_modules
         |--> routes
            | index
        |--> services
            | index
        |--> index
        |--> package
        |--> package-lock
        |--> yarn,lock
 |-->Frontend
        | Assets
             |--> hurb-icon
                 |--> hurb-logo
                 |--> image1
                 |--> image2
                 |--> image3
         | Authentication
                 |--> index
                 |--> script
                 |--> styles
         | Dashboard
                 |--> index
                 |--> script
                 |--> solicitationCard
                 |--> styles
         | HurbControl
                 |--> index
                 |--> script
                 |--> styles
         | Profile
                 |--> index
                 |--> script
                 |--> styles
         |--> global.styles
| README.md —> Arquivo que serve como guia e explicação geral sobre seu projeto.
```

## :computador: Configuração para desenvolvimento
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
* 0.1.3 - 12/05/2022
    * Painel do Hurb finalizado;
* 0.1.4 - 13/05/2022
    * Adicionado a versão 1.2 do WAD em pdf;
* 0.1.5 - 14/05/2022
    * Recurso javascript de currículo adicionado;
* 0.1.6 - 18/05/2022
    * Update README.md;
* 0.1.7 - 24/05/2022
    * Iniciado o servidor do projeto e uma nova tela;
* 0.1.8 - 24/05/2022
    * Adicionado a tela de autenticação da aplicação web;
* 0.1.9 - 24/05/2022
    * Ajustes do conteúdo do script de autenticação;
* 0.2.0 - 26/05/2022
    * Adicionado as rotas da aplicação web (routes app);
* 0.2.1 - 26/05/2022
    * Adicionado o banco de dados e aplicativo de serviços (database and services app);
* 0.2.2 - 26/05/2022
    * Adicionado a camada de controle (controllers);
* 0.2.3 - 27/05/2022
    * Ajuste nas rotas da aplicação web;
* 0.2.4 - 31/05/2022
    * Adicionado a versão 1.3 do WAD em pdf;
* 0.2.5 - 01/06/2022
    * Adicionado novas rotas da aplicação web;
* 0.2.6 - 07/06/2022
    * Tratamento de cors adicionado;
* 0.2.7 - 07/06/2022
    * Adicionado proprietário da atualização (added update owner);
* 0.2.8 - 08/06/2022
    * Adicionado o painel vinculado (dashboard);
* 0.2.9 - 08/06/2022
    * Adicionado Frontend de solicitação de atualização de perfil;
* 0.3.0 - 08/06/2022
    * Adicionado os últimos endpoint;
* 0.3.1 - 08/06/2022
    * Adicionado cartão de solicitação;
* 0.3.2 - 09/06/2022
    * Adicionado as rotas estáticas;
* 0.3.3 - 09/06/2022
    * Página de autenticação com Backend concluído;
* 0.3.4 - 10/06/2022
    * Done mcv arch, and done bind front-end routes;
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
