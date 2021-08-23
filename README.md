# TRABALHO DE PI: Mel - Adoção e Cuidados
Trabalho desenvolvido durante a disciplina de Banco de Dados do Integrado

# Sumário

### 1. COMPONENTES<br>
Integrantes do grupo<br>
Estefany Silva Gonçalves:estefanysilvagaoncalves@gmail.com<br>
Lucas Xavier:lucassxxavier@gmail.com<br>
Maria Eduarda:mellltomaz@gmail.com<br>

### 2.MINIMUNDO<br>

Nosso sistema web "Mel - Adoção e Cuidados" tem como objetivo facilitar o processo de adoção de animais. Aqui será representado a relação principal do nosso sistema web. Para que ocorra a adoção, o doador primeiramente precisa ser cadastrado no sistema web e deverá cadastrar um ou vários animais no sistema web e cada animal deverá ser cadastrado por somente um doador. Um animal pode ser somente um tipo (cachorro, gato, calopsita e hamster) e cada tipo de animal pode ou não ter vários animais do mesmo tipo. Um doador também precisa ser cadastrado e poderá doar um ou vários animais para um respectivo donatário, e o donatário poderá solicitar a doação de um ou vários animais para o doador. O donatário poderá escolher (se interessar) um ou vários animais e os animais poderão ser escolhidos por vários donatários. O modelo conceitual que será apresentado mais tarde, tem por objetivo apresentar as principais entidades, relações entre as entidades, e seus respectivos atributos necessários para facilitar o processo de adoção de animais. 
 

### 3.RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)<br>

![image](https://user-images.githubusercontent.com/87152467/127590159-9fce8f4a-aa9c-4ed0-8e43-8b56442d3b1e.png)
![Arquivo PDF do Protótipo Wireframe Simples](https://github.com/solebellsBEACH/projetoIntegrador/blob/main/modelo_wireframe_desenho_grupo_turmaA.pdf)<br>
![Arquivo PDF do Protótipo Wireframe Trabalhado](https://github.com/solebellsBEACH/projetoIntegrador/blob/main/modelo_wireframeturmaA.pdf)

#### 3.1 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?
    
> A MEL - Adoção e Cuidados precisa inicialmente dos seguintes relatórios:
* Relatório que informe quais são os doadores que estão cadastrados,  incluindo as seguintes informações: Codigo, nome, nome de usuário e senha.
* Relatório que informe quais são os donatários que estão cadastrados, incluindo as seguintes informações: Codigo, nome, nome de usuário e senha.
* Relatório que informe todos os animais cadastrados incluindo as seguintes informações: codigo, nome, categoria (cachorro, gato, calopsita e hamster) e sexo.
* Relatório de quantos animais foram cadastrados por cada pessoa, incluindo as seguintes informações: nome e codigo do doador.
* Relatório de quantas pessoas se interessaram por cada animal, incluindo as seguintes informações: Codigo, nome, categoria (cachorro, gato, calopsita e hamster) e sexo do animal.
 

### 4 TABELA DE DADOS DO SISTEMA:
    
![Tabela de dados da Mel - Adoção e Cuidados](https://github.com/solebellsBEACH/projetoIntegrador/blob/main/pi_tabela%20(1).xlsx)

 
 

 ### 5.PMC<br>
 ![image](https://user-images.githubusercontent.com/87152467/127596514-ffe7f265-2a68-40be-957f-02c208441f31.png)
 
 
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
   ![image](https://user-images.githubusercontent.com/87152467/130297653-d1f00834-ee9b-4ac6-b4a8-9cce23c3c602.png)


### 8	MODELO FÍSICO<br>
  ![image](https://user-images.githubusercontent.com/87152467/130514017-31fb5c62-b616-4aae-9a5e-88d80e6476d1.png)
  ![image](https://user-images.githubusercontent.com/87152467/130513932-da77e4e5-b2e7-4f45-b605-3351ccae642e.png)
  ![image](https://user-images.githubusercontent.com/87152467/130514139-eeb0f78c-59cb-4b3f-a721-e2b0d0ae2569.png)

       
### 9	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
        a) inclusão das instruções de inserção dos dados nas tabelas criadas pelo script de modelo físico
        (Drop para exclusão de tabelas + create definição de para tabelas e estruturas de dados + insert para dados a serem inseridos)
 ![image](https://user-images.githubusercontent.com/87152467/130470023-740e7629-e2be-4d23-9452-44cdbca92e61.png)
 ![image](https://user-images.githubusercontent.com/87152467/130470246-be99d367-3204-427d-b288-a638661a4d1d.png)
 ![image](https://user-images.githubusercontent.com/87152467/130470429-6e052140-cc00-46a8-a537-dbf1ee05ccbe.png)
 ![image](https://user-images.githubusercontent.com/87152467/130470481-9e73147c-9bb1-4537-a656-adf28c9606b9.png)
 ![image](https://user-images.githubusercontent.com/87152467/130469178-0e843eb6-6346-414b-97c0-208ec297cfa2.png)
 ![image](https://user-images.githubusercontent.com/87152467/130471060-121fb070-2de1-48cf-a767-360ce2692bcf.png)
 ![image](https://user-images.githubusercontent.com/87152467/130471209-a8538c30-2480-426b-9c69-90e5e1bb0ddc.png)
 ![image](https://user-images.githubusercontent.com/87152467/130471326-4d2f4133-0c5b-41cd-944f-d034ed68af99.png)
 ![image](https://user-images.githubusercontent.com/87152467/130471398-508f0147-0399-4320-8968-6eff22831ae6.png)
 ![image](https://user-images.githubusercontent.com/87152467/130471883-62377c70-ae76-4e93-acb7-f452e756a530.png)
 ![image](https://user-images.githubusercontent.com/87152467/130472011-898eb011-b46b-401c-9916-084199edd140.png)
 ![image](https://user-images.githubusercontent.com/87152467/130472608-569272f7-183e-412b-9d2f-16b2877f94e9.png)
 ![image](https://user-images.githubusercontent.com/87152467/130472732-f4f4dbe1-c018-461c-afda-931bbb9065d3.png)
 ![image](https://user-images.githubusercontent.com/87152467/130473049-bb75c2d1-aa5d-4ec6-8ad9-5ee258013dc9.png)
 ![image](https://user-images.githubusercontent.com/87152467/130473398-206143e4-ef3a-4b72-9bd2-ce179d89ee54.png)
 ![image](https://user-images.githubusercontent.com/87152467/130473601-8ac8a126-0e8b-4fd4-8d2e-19999dbc762c.png)
 ![image](https://user-images.githubusercontent.com/87152467/130473774-23fd2af8-9a62-4cf6-85eb-d0ec38b4bab5.png)
 ![image](https://user-images.githubusercontent.com/87152467/130474008-726e4493-3752-46c9-a85a-9b882eddcbc4.png)
 ![image](https://user-images.githubusercontent.com/87152467/130474251-bd0ddc5f-e878-4604-bd36-8dfd1895ae10.png)
 ![image](https://user-images.githubusercontent.com/87152467/130474640-72827016-703b-4d6a-af42-f07058e0abae.png)
 ![image](https://user-images.githubusercontent.com/87152467/130474864-854bb2af-6e30-4e4a-9e8b-96cda02efc2d.png)
 ![image](https://user-images.githubusercontent.com/87152467/130475049-67358b69-4cf9-4c33-9bea-8263ae576880.png)
 ![image](https://user-images.githubusercontent.com/87152467/130475286-8fcef1ac-95e3-459b-afec-d5d5bdd47e1f.png)
 ![image](https://user-images.githubusercontent.com/87152467/130475619-fd4582c8-9bad-4cd4-bc8f-c8ded8dfc4a1.png)
 ![image](https://user-images.githubusercontent.com/87152467/130475930-ea7ccc11-1bc6-4941-b4df-92f278f4b28b.png)
 ![image](https://user-images.githubusercontent.com/87152467/130476122-6b6a3b7e-8c3f-49cd-97e8-28045ee4098e.png)
 ![image](https://user-images.githubusercontent.com/87152467/130477372-9cadd03e-768f-460e-a782-c8571359a2a0.png)
 ![image](https://user-images.githubusercontent.com/87152467/130477546-4531779f-6bae-4667-be5f-aab2a83c13bb.png)
 ![image](https://user-images.githubusercontent.com/87152467/130477696-69f0c40c-2bdd-4c2b-8ae4-a6da04fa2b4f.png)
 ![image](https://user-images.githubusercontent.com/87152467/130478200-05cbebab-1ba7-4dc4-bb2c-e642499c677d.png)
 ![image](https://user-images.githubusercontent.com/87152467/130478406-04a64056-1ed5-4dbf-a39e-45691ac6197f.png)
 ![image](https://user-images.githubusercontent.com/87152467/130478676-9310d65b-33f1-47d6-84c7-c1ae09709184.png)
 
        b) Criar um novo banco de dados para testar a restauracao 
        (em caso de falha na restauração o grupo não pontuará neste quesito)
  AINDA FALTA ESSA PARTE
  
        c) formato .SQL
CREATE TABLE Animais (
    Cachorro varchar(50),
    Gato varchar(50),
    Calopsita varchar(50),
    Hamster varchar(50),
    codigo varchar(100) PRIMARY KEY,
    sexo varchar(50),
    fk_Doador_codigo varchar(50)
);

CREATE TABLE Doador (
    Nome varchar(100),
    nome_usuario varchar(50),
    senha varchar(50),
    codigo varchar(50) PRIMARY KEY
);

CREATE TABLE Donatario (
    nome varchar(100),
    nome_usuario varchar(50),
    senha varchar(50),
    codigo varchar(50) PRIMARY KEY
);

CREATE TABLE Solicita_Doa (
    fk_Donatario_codigo varchar(50),
    fk_Doador_codigo varchar(50)
);

CREATE TABLE Escolhe_Escolhidos (
    fk_Donatario_codigo varchar(50),
    fk_Animais_codigo varchar(100)
);
 
ALTER TABLE Animais ADD CONSTRAINT FK_Animais_2
    FOREIGN KEY (fk_Doador_codigo)
    REFERENCES Doador (codigo)
    ON DELETE RESTRICT;
 
ALTER TABLE Solicita_Doa ADD CONSTRAINT FK_Solicita_Doa_1
    FOREIGN KEY (fk_Donatario_codigo)
    REFERENCES Donatario (codigo)
    ON DELETE SET NULL;
 
ALTER TABLE Solicita_Doa ADD CONSTRAINT FK_Solicita_Doa_2
    FOREIGN KEY (fk_Doador_codigo)
    REFERENCES Doador (codigo)
    ON DELETE SET NULL;
 
ALTER TABLE Escolhe_Escolhidos ADD CONSTRAINT FK_Escolhe_Escolhidos_1
    FOREIGN KEY (fk_Donatario_codigo)
    REFERENCES Donatario (codigo)
    ON DELETE SET NULL;
 
ALTER TABLE Escolhe_Escolhidos ADD CONSTRAINT FK_Escolhe_Escolhidos_2
    FOREIGN KEY (fk_Animais_codigo)
    REFERENCES Animais (codigo)
    ON DELETE SET NULL;
    
  INSERT INTO tipo_animais (codigo,  tipo) VALUES('4', 'Calopsita')
  
  INSERT INTO doador (codigo, nome_usuario, nome, senha) VALUES('123', 'lxs', 'lucas', '123')
  
  INSERT INTO donatario (codigo,  nome_usuario, nome, senha,fk_animal_codigo) VALUES('1234', 'lxs4', 'maisa', '1223','342')
  
  INSERT INTO doador (codigo, nome_usuario, nome, senha) VALUES('78220', 'xande6876', 'Alexandre Lima', 'xandi8677')
  
  INSERT INTO doador (codigo, nome_usuario, nome, senha) VALUES('02072003', 'estef7884', 'Estefany', 'estf77450')
  
  INSERT INTO doador (codigo, nome_usuario, nome, senha) VALUES('6542879', 'duda77449', 'Maria Eduarda', 'duda5447')
  
  INSERT INTO doador (codigo, nome_usuario, nome, senha) VALUES('121358', 'tal784_s', 'Tales da Silva', 'tl45876')
  
  INSERT INTO doador (codigo, nome_usuario, nome, senha) VALUES('11224799', 'talita785', 'Talita Oliveira', 'tali47550');
  
  INSERT INTO donatario (codigo,  nome_usuario, nome, senha,fk_animal_codigo) VALUES('74159', 'ester485', 'Ester', '845est','8153654')
  
  INSERT INTO donatario (codigo,  nome_usuario, nome, senha,fk_animal_codigo) VALUES('74856511', 'karl841', 'Karol', '5412369','342');
  
  INSERT INTO donatario (codigo,  nome_usuario, nome, senha,fk_animal_codigo) VALUES('12030450', 'olive785a', 'Oliver', '2233oli','9710059');
  
  INSERT INTO donatario (codigo,  nome_usuario, nome, senha,fk_animal_codigo) VALUES('66954220', 'mateus441_s', 'Mateus Ferreira', 'mmf778','5894513774');
  
  INSERT INTO donatario (codigo,  nome_usuario, nome, senha,fk_animal_codigo) VALUES('12589879', 'caioss450', 'Caio Santos', 'cs5684','8658565');
  
  INSERT INTO donatario (codigo,  nome_usuario, nome, senha,fk_animal_codigo) VALUES('110235', 'camial84', 'Camila Fernandes', 'cami457','11023568');
  
  INSERT INTO donatario (codigo,  nome_usuario, nome, senha,fk_animal_codigo) VALUES('124569', 'nath451', 'Nathalia', 'nah9874mm','66399875');
  
  INSERT INTO donatario (codigo,  nome_usuario, nome, senha,fk_animal_codigo) VALUES('9750409', 'kemu1213', 'Kemuel Trindade', 'keml5441','4545625');
  
  INSERT INTO animal (codigo, sexo, nome, fk_doador_codigo, fk_tipo_animais_codigo) VALUES('8658565', 'M', 'Levi', '1232', '3');
  
  INSERT INTO animal (codigo, sexo, nome, fk_doador_codigo, fk_tipo_animais_codigo) VALUES('9710059', 'F', 'Kiara', '123a', '2');
  
  INSERT INTO animal (codigo, sexo, nome, fk_doador_codigo, fk_tipo_animais_codigo) VALUES('123456', 'F', 'Linda', '123', '4');
  
  INSERT INTO animal (codigo, sexo, nome, fk_doador_codigo, fk_tipo_animais_codigo) VALUES('4545625', 'M', 'Totó', '78220', '1');
  
  INSERT INTO animal (codigo, sexo, nome, fk_doador_codigo, fk_tipo_animais_codigo) VALUES('11023568', 'M', 'Tom', '02072003', '2');
  
  INSERT INTO animal (codigo, sexo, nome, fk_doador_codigo, fk_tipo_animais_codigo) VALUES('6657884', 'F', 'Nina', '6542879', '4');
  
  INSERT INTO animal (codigo, sexo, nome, fk_doador_codigo, fk_tipo_animais_codigo) VALUES('66399875', 'F', 'Mimi', '121358', '3');
  
  INSERT INTO animal (codigo, sexo, nome, fk_doador_codigo, fk_tipo_animais_codigo) VALUES('547610', 'F', 'Tina', '11224799', '3');
  
  INSERT INTO animal (codigo, sexo, nome, fk_doador_codigo, fk_tipo_animais_codigo) VALUES('5894513774', 'M', 'BOB', '5473012029', '1')

### 10	TABELAS E PRINCIPAIS CONSULTAS<br>
    
#### 10.1	CONSULTAS DAS TABELAS COM TODOS OS DADOS INSERIDOS (Todas) <br>
select* from tipo_animais;
![image](https://user-images.githubusercontent.com/87152467/130479416-2368e36c-fcb7-46a9-94fa-4c8e7bfd10ab.png)

select* from doador;
![image](https://user-images.githubusercontent.com/87152467/130479537-fc2b095b-bd98-4e95-b3b8-b37e3b29ed35.png)

select* from donatario;
![image](https://user-images.githubusercontent.com/87152467/130479603-7a0104a3-0d2e-48fa-aec5-61d24001858f.png)

select* from animal;
![image](https://user-images.githubusercontent.com/87152467/130479750-10279f3e-1958-4114-8ff5-55ba62b26a76.png)

#### 10.2 PRINCIPAIS CONSULTAS DO SISTEMA 
 Inserir as principais consultas (relativas aos 5 principais relatórios) definidas previamente no iten 3.1 deste template.
 <br>
 
 select codigo, nome, nome_usuario, senha from doador;
 ![image](https://user-images.githubusercontent.com/87152467/130482417-85c91579-6ed4-46a0-a5c0-5607e5745b26.png)
 
 select codigo, nome, nome_usuario, senha from donatario;
 ![image](https://user-images.githubusercontent.com/87152467/130482552-02ba3e91-9c53-48de-b2af-48187035b9a2.png)
 
 select codigo, nome, fk_tipo_animais_codigo, sexo from animal;
 ![image](https://user-images.githubusercontent.com/87152467/130482928-71ea9118-6aa4-4dd0-848e-5125e593004d.png)
 
 select count(*) "Quantidade", doa.nome, doa.codigo from doador doa inner join animal ani on (doa.codigo = ani.fk_doador_codigo) group by doa.nome, doa.codigo;
 ![image](https://user-images.githubusercontent.com/87152467/130485435-92b15fc7-d402-4938-b282-94af94f7ec47.png)
 
 select count(*) "Quantidade", ani.codigo, ani.nome, ani.fk_tipo_animais_codigo, ani.sexo from animal ani inner join donatario don on (ani.codigo = don.fk_animal_codigo) group by ani.codigo, ani.nome, ani.fk_tipo_animais_codigo, ani.sexo;
 ![image](https://user-images.githubusercontent.com/87152467/130485889-993a371d-90ee-4d71-add3-8e9954d268db.png)
 
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
