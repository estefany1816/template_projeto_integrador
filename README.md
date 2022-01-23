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
* Relatório que informe quantos animais tem por sexo (macho e fêmea).
* Relatório que informe quantos animais estão cadastrados em cada tipo (categoria: cachorro, gato, calopsita e hamster).
* Relatório que informe a quantidade de animais cadastrados por idade. Ordenada crescentemente por idade.
* Relatório que informe quantos animais foram cadastrados por cada pessoa, incluindo as seguintes informações: nome e codigo do doador.
* Relatório que informe quantas pessoas se interessaram por cada animal, incluindo as seguintes informações: Codigo, nome, categoria (cachorro, gato, calopsita e hamster) e sexo do animal.
 

### 4 TABELA DE DADOS DO SISTEMA:
    
![Tabela de dados da Mel - Adoção e Cuidados](https://github.com/solebellsBEACH/projetoIntegrador/blob/main/pi_tabela%20(2).xlsx)

 
 

 ### 5.PMC<br>
![image](https://user-images.githubusercontent.com/87152467/150694282-da0d1f06-9d2a-4654-8c13-75fa33fde497.png)
 
 
 ### 6.MODELO CONCEITUAL<br>  
        
![image](https://user-images.githubusercontent.com/87152467/150684562-d6e5cfeb-2a0d-424c-b6eb-f9cde4f750b8.png)
    
      
    
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
    idade_animal: Armazena a idade do animal.


### 7	MODELO LÓGICO<br>
   ![image](https://user-images.githubusercontent.com/87152467/150684642-e9004f3c-1c4c-4fe9-b2f9-6a1dd971bbd6.png)


### 8	MODELO FÍSICO<br>
  ![image](https://user-images.githubusercontent.com/87152467/150684667-a09e90da-d8e7-4bba-b8f5-ed71dc971cc2.png)
  ![image](https://user-images.githubusercontent.com/87152467/150684682-657148f3-8f28-49a3-a269-eaae611452d0.png)
  ![image](https://user-images.githubusercontent.com/87152467/150684693-23d57e0a-55af-4868-8f7d-c3ce90a146b5.png)

       
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
-create table animal (codigo varchar(255), sexo varchar(255), nome varchar(255), fk_doador_codigo varchar(255), fk_tipo_animais_codigo varchar(255)) 

-create table doador (codigo varchar(255), nome_usuario varchar(255), nome varchar(255), senha varchar(255)) 

-create table donatario (codigo varchar(255),  nome_usuario varchar(255), nome varchar(255), senha varchar(255),fk_animal_codigo varchar(255))

-create table tipo_animais (codigo varchar(255),  tipo varchar(255))

![WhatsApp Image 2021-08-23 at 20 26 57](https://user-images.githubusercontent.com/62174352/130532393-1c988032-b196-4dd7-8936-c07a7d7cbf81.jpeg)
![image](https://user-images.githubusercontent.com/87152467/130852069-5d6545b5-1a87-4d67-8fdc-2c8c016afa76.png)

  
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
![image](https://user-images.githubusercontent.com/87152467/131016817-5a6cdb8b-3af6-404a-b71b-5c5d279fe0f2.png)

select* from donatario;
![image](https://user-images.githubusercontent.com/87152467/131016916-4efc3900-ac2b-4966-9e68-2d4de261272f.png)

select* from animal;
![image](https://user-images.githubusercontent.com/87152467/131017026-78bef8e1-538c-4df0-a9a0-7337937fb5aa.png)


#### 10.2 PRINCIPAIS CONSULTAS DO SISTEMA 
 Inserir as principais consultas (relativas aos 5 principais relatórios) definidas previamente no iten 3.1 deste template.
 <br>
 
 select count(*) "Quantidade", sexo from animal group by sexo;
 ![image](https://user-images.githubusercontent.com/87152467/131025375-c4cf3b55-2759-429c-b975-8d2b57ed18af.png)
 
 select count(*) "Quantidade", ta.tipos from animal ani inner join tipo_animais ta on (ani.fk_tipo_animais_codigo = ta.codigo) group by ta.tipos;
 ![image](https://user-images.githubusercontent.com/87152467/131025430-937c75ab-9c4d-4ae9-82c6-78ef83d8b921.png)
 
 select count(*) "Quantidade de Animais", idade from animal group by idade order by idade;
 ![image](https://user-images.githubusercontent.com/87152467/131025522-95661a0d-1713-4d1b-9d06-8069a8c6ecdd.png)
 
 select count(*) "Quantidade", doa.nome, doa.codigo from doador doa inner join animal ani on (doa.codigo = ani.fk_doador_codigo) group by doa.nome, doa.codigo;
 ![image](https://user-images.githubusercontent.com/87152467/131025610-33580c37-eed3-488d-83b4-dcdce87e9fd5.png)
 ![image](https://user-images.githubusercontent.com/87152467/131025655-85f15543-f515-453e-97fd-e7756e94707c.png)
 
 select count(*) "Quantidade", ani.codigo, ani.nome, ani.fk_tipo_animais_codigo, ani.sexo from animal ani inner join donatario don on (ani.codigo = don.fk_animal_codigo) group by ani.codigo, ani.nome, ani.fk_tipo_animais_codigo, ani.sexo;
 ![image](https://user-images.githubusercontent.com/87152467/131025723-4d390454-af0c-4469-beca-cfc936d28719.png)
 ![image](https://user-images.githubusercontent.com/87152467/131025749-f45ff9bf-0b69-45e9-8a4e-8887c8220311.png)

 
 ### 11 Gráficos, relatórios, integração com Linguagem de programação e outras solicitações.<br>
     OBS: Observe as instruções relacionadas a cada uma das atividades abaixo.<br>
 #### 11.1	Integração com Linguagem de programação; <br>
 Link para o colab: https://colab.research.google.com/drive/1hzXWwdca_IWv8wE0XC1cEG4UGNYS8xzg#scrollTo=TPXwPE9SHkhT
 
 ### Relatório 1:
  res = pd.read_sql_query("""
                            select count(*) "Quantidade", sexo from animal group by sexo;
                            """,conn)

  sns.barplot(x='sexo',y='Quantidade', data=res)
  
  ### Relatório 2:
  res = pd.read_sql_query("""select count(*) "Quantidade", ta.tipos from animal ani inner join tipo_animais ta on (ani.fk_tipo_animais_codigo = ta.codigo) group by ta.tipos
                            """,conn)
  res
  
  plt.xticks(rotation=70)
  sns.barplot(x='tipos',y='Quantidade',data=res,)
  
  ### Relatório 3:
  res = pd.read_sql_query("""
                  select count(*) "Quantidade de Animais", idade from animal group by idade order by idade;
                  """,conn)
  res
  
  sns.barplot(x='idade',y='Quantidade de Animais',data=res)
  
  ### Relatório 4:
   res = pd.read_sql_query("""
                           select count(*) "Quantidade", doa.nome, doa.codigo from doador doa inner join animal ani on (doa.codigo = ani.fk_doador_codigo) group by doa.nome,        doa.codigo
 """,conn)
   res
   
   plt.figure(figsize= (20, 10))
   plt.xticks(rotation=70)
   sns.barplot(x='nome',y='Quantidade',data=res,)

   ### Relatório 5:
   res = pd.read_sql_query("""
                           select count(*) "Quantidade", ani.codigo, ani.nome, ani.fk_tipo_animais_codigo, ani.sexo from animal ani inner join donatario don on (ani.codigo =  don.fk_animal_codigo) group by ani.codigo, ani.nome, ani.fk_tipo_animais_codigo, ani.sexo
                            """,conn)
   res
   
   sns.barplot(x='nome',y='Quantidade',data=res)

 #### 11.2	Desenvolvimento de gráficos/relatórios pertinentes, juntamente com demais <br>
 #### solicitações feitas pelo professor. <br>
 
 ### Relatório 1:
 ![image](https://user-images.githubusercontent.com/87152467/131025846-c5348ccf-e597-4062-b67e-2b8f79f18a76.png)
 
 ### Relatório 2:
 ![image](https://user-images.githubusercontent.com/87152467/131025925-179d0519-3663-44d7-a740-a5d1c04eb1d7.png)
 
 ### Relatório 3:
 ![image](https://user-images.githubusercontent.com/87152467/131026114-aaa5a32b-8796-4f7d-9026-a31a67c6af5e.png)
 ![image](https://user-images.githubusercontent.com/87152467/131026156-88bf9e23-df52-4816-a1a3-5f1744f392ae.png)
 
 ### Relatório 4:
 ![image](https://user-images.githubusercontent.com/87152467/131026418-37a968a9-4cef-45d0-89fd-41a8aaf31b5c.png)
 ![image](https://user-images.githubusercontent.com/87152467/131026500-85fc8328-5fce-4cf6-afe7-d10e7927b2ae.png)
 ![image](https://user-images.githubusercontent.com/87152467/131026557-03abfbfe-8d70-4b16-8113-3472ddb53da4.png)
 
 ### Relatório 5:
 ![image](https://user-images.githubusercontent.com/87152467/131026859-98f32c3c-6580-4651-89c8-cd5b54827fbf.png)
 ![image](https://user-images.githubusercontent.com/87152467/131026909-00a3f941-1960-4ca6-be04-ca3555189f7a.png)

 <br>
 <br>
 
 ### 12 Slides e Apresentação em vídeo. <br>
     OBS: Observe as instruções relacionadas a cada uma das atividades abaixo.<br>
 #### 12.1 Slides; <br>
 
 [Slides em pdf](https://github.com/estefany1816/template_projeto_integrador/files/7068988/PI_slides_PK.pdf) <br>
 [Slides em pptx](https://github.com/estefany1816/template_projeto_integrador/files/7068990/PI_slides_PK.pptx) <br>
 
 #### 12.2 Apresentação em vídeo <br>
 
 https://youtu.be/wijKXRqSpEQ

 ### 13 Telas - Versão Mobile <br>
 #### 13.1 Protótipos de Telas - Mobile <br>
 [Prints dos protótipos em pdf](https://github.com/estefany1816/template_projeto_integrador/files/7920715/Prints_prototipos.pdf)
 <br>
 #### 13.2 Telas Desenvolvidas no Android Studio - Mobile <br>
 [Telas - Mobile em pdf](https://github.com/estefany1816/template_projeto_integrador/files/7920823/telas_mobile_AS.pdf)

 #### 14 Link para instalar apk do projeto <br>
https://drive.google.com/file/d/19Lrzgqi1I8CwBgg9Y0A6w1v7WHbLBkpP/view?usp=sharing

#### 15 Link para acessar sistema versão web <br>
https://progweb-front.herokuapp.com/dashboard

#### 16 Link do repositório - Projeto MEL - Adoções e Cuidados (Android Studio) <br>
Nesse link está o repositório integrado no Android Studio. Nele contém todas as pastas do projeto.
https://github.com/estefany1816/melapp

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
