# DESENVOLVIMENTO-DE-SISTEMAS-ORIENTADO-A-OBJETOS-GRUPO-54

SERVIÇO NACIONAL DE APRENDIZAGEM COMERCIAL **SENAC** 

**CURO DE TECNOLOGIA EM ANÁLISE E DESENVOLVIMENTO DE SISTEMAS** 

**PROJETO INTEGRADOR II: DESENVOLVIMENTO DE SISTEMAS ORIENTADO A OBJETOS** 

Alunos:

Rafael Theodoro Campos Carvalho 

Priscila De Almeida Silvestre      

Gabriel Gomes Rios 

Ricardo Lins Da Silva

Suellen Lorreine Miranda     

Vitor Oliveira Da Silva Pereira 

Thiago Scordamaglia M.   

Rodrigo Teixeira Das Chagas 

18 de novembro, 2023 

Projeto Integrador 

Projeto Integrador 2 

Tarefa como exigência parcial para a obtenção de aprovação na disciplina Projeto Integrado 2 do curso de Análise de Sistemas.

Professor Orientador: Enoque Felipe dos Santos Leal 

 

# **Sumário** 

Resumo ......................................................................................................................2 
1. Introdução .......................................................................................................3 
2. Desenvolvimento ..........................................................................................3

	2\.1.  Relação de classes e desenvolvimento .........................................5
3. Lista de Funcionalidades .............................................................................7 
4. Diagramas de uso ..........................................................................................7 
5. Casos de uso......................................................................................................8 
6. Protótipos .........................................................................................................11 

 Referências .................................................................................................................13

 

# **Resumo**

Neste trabalho,  abordamos  o  cadastro  de  professores, alunos, e fornecedores em um contexto educacional, visando a organização  eficiente  de  uma  instituição  de  ensino. Exploramos os conceitos  de programação orientada a objetos e  apresentamos  a  relação  entre  classes,  essencial  para  o desenvolvimento  de  um  sistema  de  banco  de  dados organizado.


# **1  Introdução**
A  criação  de  um  diagrama  UML  (Unified  Modeling  Language) desempenha  um  papel  fundamental  nos  projetos  de  análise  e desenvolvimento de sistemas. Ele  serve  como  uma  linguagem  visual que  ajuda  a  representar  de  forma  clara  e  concisa  a  estrutura, funcionalidades e interações de um sistema de software. 

A principal razão de elaborar um diagrama desse tipo é garantir que a equipe de  TI esteja alinhada com os objetivos do projeto, ao tornar  visual  os processos facilita a comunicação eficaz  entre as partes interessadas o que garante um feedback mais preciso.


# **2  Desenvolvimento**
Em um caso hipotético um novo professor precisa ser cadastrado para o  começo do ano letivo. 

Para que tal processo seja possível é necessário o cadastro de suas  informações essenciais.  Como um funcionário  de  uma  empresa  e  pessoa  física,  dados  como  CPF, endereço, e-mail e formação acadêmica devem ser fornecidos para preencher  os  atributos  de  cadastro  e  como  consequência  deve receber um valor de matrícula como professor da instituição. As futuras avaliações feitas pelos alunos devem ser corrigidas e postadas nos sistemas  pelos  professores  no  qual  as  pessoas  físicas  cadastradas podem ter acesso. 
Um  centro  universitário  tem  grande  impacto  na  geração  de empregos, como serviços  limpeza, material, reformas e segurança são exemplos  desses. Porém, com objetivo manter a vigilância de todos esses prestadores de serviços é  preciso  uma  organização  eficiente.  Simulando  uma  situação  de cadastro de um fornecedor a  instituição por ser uma pessoa jurídica dados como CNPJ,  e-mail, endereço e serviço prestado devem estar bem claros, de mesmo modo, uma empresa deve relatar os serviços fornecidos (Materiais, funcionários etc.) 

Os  alunos  que  desejem  entrar  na  instituição  devem  também  ser cadastrados com suas informações básicas:e-mail, CPF e endereço, o aluno se relaciona com os professores através da classe pessoa física, onde é capaz de consultar suas notas.

Figura 1: Diagrama

![](001.png)

 
**2.1 Relação de classes e desenvolvimento**

Ao elaborar um sistema de organização para uma grande instituição de ensino como por exemplo um banco de dados é preciso uma grande organização  prévia.  O  sistema  de  diagrama  de  classes  é  uma ótima ferramenta para se estruturas as ideias, métodos e funções desse tipo de sistema.

No diagrama criado no capítulo 1 fica claro a relação de herança em as classes hipotéticas criadas. No qual, as classes “filhas” recebem as funções de classes ”Mães” estabelecendo suas relações através de atributos e métodos compartilhados, em uma aplicação mais elaborada seria  necessário  novas  classes  e  a  utilização  dos  conceitos  de programação orientada a objetos. 

Em  um  caso  de  cadastro  de  um aluno que recebe bolsa integral ao invés de elaborar uma nova classe para esse tipo de aluno é possível utilizar a relação de polimorfismo já que  apesar  de  bolsista  ainda é  um  aluno.  Talvez  seja  conveniente também,  definir  o  comportamento  de  uma  classe  através de uma interface para garantir que os vai implementar os métodos declarados obrigatoriamente e seguir seu contrato de comportamento. 

Os conceitos de orientação a objetos são essenciais para a elaboração de um sistema  que  seja  expansível  e  sem  atritos  com  futuras  novas funcionalidades  e  aliado  as  tecnologias  da  engenharia  de  software permitem que o projeto caminhe de maneira eficiente. 

Uma  universidade  oferece  vários serviços  e  atividades,  como expansão do diagrama do capítulo 2, as classes biblioteca, atlética, projeto de extensão, financeiro e disciplinas foram acrescentadas, cada uma  delas  se  relaciona  de  diferentes  formas  com  as  outras  classes presentes,  de  forma  que  consiga  obter  as  informações  e  métodos necessários para seu funcionamento. 

Figura 2: Diagrama 2

![](002.jpeg)

 
# **3  Lista de Funcionalidades**
1. Login 
1. Tela inicial (home) 
1. Cadastro de Professores 
1. Cadastro de Alunos 
1. Cadastro de Fonecedores 


# **4  Diagrama de uso**

Figura 3: Diagrama 3
![](003.png)

 
# **5  Casos de uso**

**CASO DE USO : Cadastro de pessoas em um sistema de universidade.**

VISÃO GERAL : O sistema da universidade deve criar um sistema de dados que inclui o cadastro de alunos , professores e fornecedores.  

PRÉ CONDIÇÃO : Todo fornecedor e a universidade são pessoas jurídicas / os professores e alunos são pessoas físicas. 

PÓS CONDIÇÕES : Os dados cadastrados ficam armazenados no sistema.  

**CASO DE USO : Cadastro de alunos.**

ATOR : Aluno  

1 - O aluno inicia o caso de uso acessando o sistema da universidade. 

2 - O sistema oferece ao aluno as opções: Visualizar cursos/Se inscrever em cursos.  

3  -  Selecionando  a  opção  visualizar  cursos,  o  aluno  escolhe  um  curso  de  seu interesse.  

4 - Com o curso escolhido o aluno acessa a opção se inscrever em cursos. 

5 - Na opção se inscrever em cursos o aluno envia para a o sistema seus dados para ser feito seu cadastro com sucesso. 

6 - Os dados dos alunos são mantidos no sistema. 


**CASO DE USO : Cadastro de professor.**

ATOR : Professor.

1 - O professor inicia o caso de uso acessando o sistema da universidade.  

2 - O sistema informa quantas turmas e alunos ficaram em sua responsabilidade.  

3 - O sistema oferece ao professor as opções: incluir ou excluir aluno nas turmas /enviar ou atualizar notas no sistema / enviar ou atualizar frequências no sistema.  


**CASO DE USO : Cadastro de fornecedor.**

ATOR : Fornecedor  

1 - O fornecedor inicia o caso de uso acessando o sistema da universidade.  

2 - O sistema informa ao fornecedor as solicitações de materiais  

3 - O fornecedor envia cotações ao sistema 

4 - O fornecedor consegue ter acesso a dados genéricos sobre alunos e professores.  


**CASO DE USO : Universidade gerenciando o sistema.**

ATOR : Universidade

1 - A universidade inicia o caso de uso acessando ao sistema  

2 - A universidade ao gerir o sistema fica responsável por: cadastrar, excluir ou alterar alunos do sistema / cadastrar, excluir ou alterar professores do sistema / cadastrar, excluir ou alterar fornecedores do sistema.  


**CASO DE USO: CENÁRIO ALTERNATIVO: O aluno deseja mudar de turma durante o curso.**

ATOR: Aluno  

1 - O aluno inicia o caso de uso acessando o sistema da universidade  

2 - O aluno envia uma solicitação ao professor pedindo a mudança de turma  3 - O professor envia ao sistema a alteração de turma do aluno  

4 - Assim que o sistema faz a alteração automaticamente o professor consegue fazer a alteração  

5 - Solicitação de mudança concluída com sucesso.  


**CASO  DE  USO:  CENÁRIO  ALTERNATIVO:  O  aluno desistir  do  curso  e  sair  da universidade.**

ATOR : Aluno  

1 - O aluno inicia o caso de uso acessando o sistema da universidade  

2  -  O  aluno  envia  uma  solicitação  ao  professor  pedindo  o  desligamento  da universidade  

3 - O professor envia ao sistema a solicitação de desligamento do aluno  

4 - Assim que o sistema faz a alteração automaticamente o professor consegue fazer a alteração  

5- Solicitação de desligamento concluída com sucesso 


# **6  Protótipos**

**Tela de login**

Figura 4: Tela de Login
![](.004.png)


**Home**

Figura 5: Home
![](005.png)

**Cadastro de professores (pessoa física)**

Figura 6: Cadastro Professores

![](006.png)


**Cadastro de alunos (pessoa física)**

Figura 7: Cadastro Aluno

![](007.png)

**Cadastro de fornecedores (pessoa jurídica)**

Figura 8: Cadastro Fornecedores
![](008.png)


# **7  Referências bibliográficas**
• BARNES,  D.  J.;  KOLLING,  M.  Programação orientada  a objetos com Java: uma  introdução prática usando o BlueJ.

São Paulo: Pearson, 2010. • FOWLER, M. UML essencial: um breve guia para a linguagem padrão  de  modelagem  de  objetos.  Porto  Alegre:  Bookman, 2005. • SCHILDT,  H.;  SKRIEN,  D.  Programação com  Java:  uma introdução abrangente.  Porto Alegre:  Bookman McGraw Hill, 2013.

Link Git Hub [https://github.com/RodrigoTeixeiraC/DESENVOLVIMENTO-DE-SISTEMAS- ORIENTADO-A-OBJETOS-GRUPO-54 ](https://github.com/RodrigoTeixeiraC/DESENVOLVIMENTO-DE-SISTEMAS-ORIENTADO-A-OBJETOS-GRUPO-54)
