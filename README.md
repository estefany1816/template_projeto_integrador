# TRABALHO DE PI: Mel - Adoção e Cuidados
Trabalho desenvolvido durante a disciplina de Banco de Dados do Integrado

# Sumário

### 1. COMPONENTES<br>
Integrantes do grupo<br>
Estefany Silva Gonçalves:estefanysilvagaoncalves@gmail.com<br>
Lucas Xavier:lucassxxavier@gmail.com<br>
Maria Eduarda:mellltomaz@gmail.com<br>
...

### 2.MINIMUNDO<br>

Nosso sistema web "Mel - Adoção e Cuidados" tem como objetivo facilitar o processo de adoção de animais. Aqui será representado a relação principal do nosso sistema web. Para que ocorra a adoção, o doador primeiramente precisa ser cadastrado no sistema web e deverá cadastrar um ou vários animais no sistema web e cada animal deverá ser cadastrado por somente um doador. Um animal pode ser somente um tipo (cachorro, gato, calopsita e hamster) e cada tipo de animal pode ou não ter vários animais do mesmo tipo. Um doador também precisa ser cadastrado e poderá doar um ou vários animais para um respectivo donatário, e o donatário poderá solicitar a doação de um ou vários animais para o doador. O donatário poderá escolher (se interessar) um ou vários animais e os animais poderão ser escolhidos por vários donatários. O modelo conceitual que será apresentado mais tarde, tem por objetivo apresentar as principais entidades, relações entre as entidades, e seus respectivos atributos necessários para facilitar o processo de adoção de animais. 
 

### 3.RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)<br>

![image](https://user-images.githubusercontent.com/87152467/127590159-9fce8f4a-aa9c-4ed0-8e43-8b56442d3b1e.png)
![Arquivo PDF do Protótipo Wireframe Simples](https://github.com/solebellsBEACH/projetoIntegrador/blob/main/modelo_wireframe_desenho_grupo_turmaA.pdf)<br>
![Arquivo PDF do Protótipo Wireframe Trabalhado](https://github.com/solebellsBEACH/projetoIntegrador/blob/main/modelo_wireframeturmaA.pdf)

#### 3.1 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?
    
> A MEL - Adoção e Cuidados precisa inicialmente dos seguintes relatórios:
* Relatório que informe quantos doadores estão cadastrados,  incluindo as seguintes informações: Nome, nome de usuário e senha.
* Relatório que informe quantos donatários estão cadastrados, incluindo as seguintes informações: Nome, nome de usuário e senha.
* Relatório de animais cadastrados incluindo as seguintes informações: categoria (cachorro, gato, calopsita e hamster) e sexo.
* Relatório de quantos animais foram cadastrados por cada pessoa.
* Relatório de quantas pessoas solicitaram a tutela do pet para os doadores.
 

### 4 TABELA DE DADOS DO SISTEMA:
    
![Tabela de dados da Mel - Adoção e Cuidados](https://github.com/solebellsBEACH/projetoIntegrador/blob/main/pi_tabela%20(1).xlsx)

 
 

 ### 5.PMC<br>
 (![image](https://user-images.githubusercontent.com/87152467/127596514-ffe7f265-2a68-40be-957f-02c208441f31.png))
 
 
 ### 6.MODELO CONCEITUAL<br>  
        
![image](https://user-images.githubusercontent.com/87152467/130252472-66f5542d-d9f3-4e56-a705-a3890877c724.png)
    
      
    
#### 6.1 Descrição dos dados 
    nome_doador: Armazena o nome da pessoa cadastrada, no caso, o doador.
    nome_usuario_doador: Armazena o nome de usuário da pessoa cadastrada, no caso, o doador.
    senha_doador: Armazena a senha da pessoa cadastrada, no caso, o doador.
    codigo_doador: Armazena o código da pessoa cadastrada, no caso, o doador.
    nome_donatario: Armazena o nome da pessoa cadastrada, no caso, o donatário.
    nome_usuario_donatario: Armazena o nome de usuário da pessoa cadastrada, no caso, o donatário.
    senha_donatario: Armazena a senha da pessoa cadastrada, no caso, o donatário.
    codigo_donatario: Armazena o código da pessoa cadastrada, no caso, o donatário.
    Tipo_Animal: Armazena a categoria de animais disponíveis (cachorro, gato, calopsita e hamster).
    codigo_Tipo_Animal: Armazena os códigos que indentificam cada categoria de animal,
    codigo_animal: Armazena o código do animal.
    sexo_animal: Armazena o sexo do animal.


### 7	MODELO LÓGICO<br>
   ![image](https://user-images.githubusercontent.com/87152467/130260642-1393b3c5-29f5-4764-9c1f-fcc4f80fa0e5.png)


### 8	MODELO FÍSICO<br>
   ![image](https://user-images.githubusercontent.com/87152467/130254033-1c89ba09-4130-48f1-8aeb-9c7a12450b85.png)
   ![image](https://user-images.githubusercontent.com/87152467/130254256-037eca8a-e65c-4b39-b82f-d5b7b2211876.png)
   ![image](https://user-images.githubusercontent.com/87152467/130254348-40b66941-919b-4438-bc83-1a3cd5a04db0.png)

   
       
### 9	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
        a) inclusão das instruções de inserção dos dados nas tabelas criadas pelo script de modelo físico
        (Drop para exclusão de tabelas + create definição de para tabelas e estruturas de dados 
 <br> + insert para dados a serem inseridos)
        b) Criar um novo banco de dados para testar a restauracao 
        (em caso de falha na restauração o grupo não pontuará neste quesito)
        c) formato .SQL


### 10	TABELAS E PRINCIPAIS CONSULTAS<br>
    OBS: Incluir para cada tópico as instruções SQL + imagens (print da tela) mostrando os resultados.<br>
#### 10.1	CONSULTAS DAS TABELAS COM TODOS OS DADOS INSERIDOS (Todas) <br>
#### 10.2 PRINCIPAIS CONSULTAS DO SISTEMA 
 Inserir as principais consultas (relativas aos 5 principais relatórios) definidas previamente no iten 3.1 deste template.
 <br>
  a) Você deve apresentar as consultas em formato SQL para cad um dos relatórios.
 <br>
  b) Além da consulta deve ser apresentada uma imagem com o resultado obtido para cada consulta.
 <br>
 <br>
 
 ### 11 Gráficos, relatórios, integração com Linguagem de programação e outras solicitações.<br>
     OBS: Observe as instruções relacionadas a cada uma das atividades abaixo.<br>
 #### 11.1	Integração com Linguagem de programação; <br>
 #### 11.2	Desenvolvimento de gráficos/relatórios pertinentes, juntamente com demais <br>
 #### solicitações feitas pelo professor. <br>
 <br>
 <br>
 
 ### 12 Slides e Apresentação em vídeo. <br>
     OBS: Observe as instruções relacionadas a cada uma das atividades abaixo.<br>
 #### 12.1 Slides; <br>
 #### 12.2 Apresentação em vídeo <br>
 <br>
 <br>   


    
##### About Formatting
    https://help.github.com/articles/about-writing-and-formatting-on-github/
    
##### Basic Formatting in Git
    
    https://help.github.com/articles/basic-writing-and-formatting-syntax/#referencing-issues-and-pull-requests
   
    
##### Working with advanced formatting
    https://help.github.com/articles/working-with-advanced-formatting/

#### Mastering Markdown
    https://guides.github.com/features/mastering-markdown/

### OBSERVAÇÕES IMPORTANTES

#### Todos os arquivos que fazem parte do projeto (Imagens, pdfs, arquivos fonte, etc..), devem estar presentes no GIT. Os arquivos do projeto vigente não devem ser armazenados em quaisquer outras plataformas.
1. Caso existam arquivos com conteúdos sigilosos, comunicar o professor que definirá em conjunto com o grupo a melhor forma de armazenamento do arquivo.

#### Todos os grupos deverão fazer Fork deste repositório e dar permissões administrativas ao usuário deste GIT, para acompanhamento do trabalho.

#### Os usuários criados no GIT devem possuir o nome de identificação do aluno (não serão aceitos nomes como Eu123, meuprojeto, pro456, etc). Em caso de dúvida comunicar o professor.


Link para BrModelo:<br>
http://sis4.com/brModelo/brModelo/download.html
<br>


Link para curso de GIT<br>
![https://www.youtube.com/curso_git](https://www.youtube.com/playlist?list=PLo7sFyCeiGUdIyEmHdfbuD2eR4XPDqnN2?raw=true "Title")
