<h1 align="center">ExpenseFlow 🏦 </h1>
   <!-- 
   <p align="center">
   <image alt="header-main" src=""/>
   </p>   
   -->
<hr>

  <p align="center">
     <a href ="#objetivo">Objetivo</a>  |
     <a href ="#visão-do-produto">Visão do produto</a>  |
     <a href ="#cronograma">Cronograma</a>  |
     <a href ="#backlog--entregas">Backlog/Entregas</a>  |
     <a href ="#requisitos">Requisitos</a>  |
     <a href ="#tecnologias">Tecnologias</a>  |
     <a href ="#como-usar">Como usar</a>   |
     <a href ="#equipe">Equipe</a>
   </p>


<span id="objetivo">
   
## :dart: Objetivo 
<blockquote>
O objetivo do ExpenseFlow é desenvolver uma aplicação móvel intuitiva e de fácil utilização, permitindo que os usuários realizem requisições de maneira simples e prática. A aplicação visa proporcionar uma experiência fluida e eficiente, facilitando o gerenciamento de despesas. O projeto foi produzido utilizando a metodologia ágil Scrum, garantindo entregas rápidas, iterativas e alinhadas às necessidades do cliente, promovendo um ciclo contínuo de melhorias e adaptações.
</blockquote>

<span id="visão-do-produto">
   
## :eye_speech_bubble: Visão do Produto   
<blockquote>   
A visão do ExpenseFlow é ser uma solução móvel para a gestão e requisição de reembolsos corporativos, oferecendo uma plataforma responsiva, intuitiva e de fácil uso. O objetivo é simplificar o processo de solicitação e aprovação de reembolsos, proporcionando uma experiência ágil e eficiente tanto para os usuários quanto para as empresas, aumentando a produtividade e garantindo maior controle e transparência nas finanças corporativas.
</blockquote>

<span id="cronograma">  
   
## :spiral_calendar: Cronograma  
| FASE | INÍCIO | FIM |
| --- | --- | --- |
| Kick-off | 24/02/2025 | 28/02/2025 |
| Sprint 1 | 10/03/2025 | 30/03/2025 |
| Planning | 31/03/2025 | 04/04/2025 |
| Sprint 2 | 07/04/2025 | 27/04/2025 |
| Planning | 28/04/2025 | 02/05/2025 |
| Sprint 3 | 05/05/2025 | 25/05/2025 |
| Review   | 26/05/2025 | 28/05/2025 |

<span id="backlog--entregas">
   
## :pushpin: Product Backlog

<details>
 <summary>Product Backlog</summary>
   
| Rank | Prioridade | User Story | Estimativa | Sprint | Critério de aceitação |
| --- | --- | --- | --- | --- | --- |
| 1 | ALTA | "Como usuário, quero fazer login na aplicação, para que possa acessar minhas informações e funcionalidades." | 2 | 1 | "Tela com Campos para acesso a aplicação com  E-mail e senha para acesso; Validar as credenciais e permitir acesso à aplicação se forem corretas; Redirecionamento para Tela Principal ao logar com sucesso" |
| 2 | ALTA | "Como usuário, quero selecionar o tipo de reembolso que estou solicitando, para que possa categorizar corretamente minha despesa." | 2 | 1 | "Usuário deve ser capaz de selecionar o tipo de reembolso de uma lista de tipos disponíveis; O tipo de reembolso solictiado deve aparecer na tela" |
| 3 | ALTA | "Como usuário, quero informar o valor do reembolso, para que possa registrar minha solicitação de forma precisa." | 1 | 1 | "O campo do valor do reembolso só pode aceita números ; O valor deve ser validado para certificar que é positivo e dentro do limite especificado" |
| 4 | ALTA | "Como usuário, quero enviar uma foto do comprovante armazenada na minha galeria, para que possa anexá-la ao meu pedido de reembolso." | 3 | 1 | "Usuário deve ser capaz de acessar sua galeria de fotos/arquivos do dispositivo; Usuário deve poder selecionar uma foto/pdf para anexo; A foto/pdf deve ser exibido na tela antes do envio" |
| 5 | ALTA | "Como usuário, quero ver uma lista dos meus pedidos de reembolso, para que possa acompanhar minhas solicitações." | 1 | 1 | "Tela com uma lista de pedidos de reembolso do usuário; A lista deve conter informações basicas do pedido" |
| 6 | ALTA | "Como usuário, quero receber um alerta ao tentar solicitar um reembolso acima do limite permitido, para que eu possa justificar o valor." | 1 | 1 | "Um alerta deve aparecer na tela do usuário caso ele ultrapasse o limite; O alerta deve fornecer informações de como justificar a ultrapassagem do limite" |
| 7 | ALTA | "Como sistema, quero salvar a data, o valor e o tipo do reembolso, para que possa processar corretamente as solicitações dos usuários." | 2 | 1 | "Armazenar a data da solicitação, o valor e o tipo de reembolso corretamente no banco de dados; Essas informações devem ser acessiveis através de um endpoint na API" |
| 8 | ALTA | "Como usuário, quero adicionar uma descrição detalhada à minha despesa, para que possa justificar a solicitação de reembolso." | 1 | 1 | "O campo de descrição permite ao usuário inserir texto; O campo de descrição é validado para garantir que o texto não seja vazio caso o usuário ultrapasse o limite de valor do pedido" |
| 9 | ALTA | "Como usuário, quero poder excluir um comprovante anexado antes do envio, para que possa substituir por outro caso tenha anexado o errado." | 1 | 1 | "O usuário pode excluir um comprovante anexado antes de finalizar a solicitação de reembolso; O sistema confirma a exclusão do arquivo com uma mensagem e retirando a imagem/pdf da tela" |
| 10 | ALTA | "Como usuário, quero pertencer a múltiplos grupos e projetos, para que possa gerenciar reembolsos de diferentes áreas." | 3 | 2 |
| 11 | ALTA | "Como usuário, quero escolher o projeto, grupo ou área do reembolso, para que possa organizar minhas solicitações corretamente." | 3 | 2 |
| 12 | ALTA | "Como usuário, quero tirar uma foto do comprovante de despesa, para que possa anexá-lo à minha solicitação de reembolso." | 2 | 2 |
| 13 | ALTA | "Como usuário, quero visualizar o status do meu pedido de reembolso, para que possa saber se foi aprovado ou rejeitado." | 1 | 2 |
| 14 | MÉDIA | "Como usuário, quero que meus reembolsos sejam organizados por projeto, grupo ou área, para que possa gerenciá-los com mais eficiência." | 3 | 2 |
| 15 | MÉDIA | "Como usuário, quero cancelar uma solicitação de reembolso antes da aprovação, para que possa evitar processamento de pedidos incorretos." | 1 | 2 |
| 16 | MÉDIA | "Como usuário, quero filtrar meus reembolsos por status (pendente, aprovado, rejeitado) ou por período (mensal, trimestral, anual), para que possa encontrar informações rapidamente" | 4 | 2 |
| 17 | MÉDIA | "Como desenvolvidor, quero acesso a uma documentação ampla da funcionalidade dos endpoints do sistema." | 5 | 3 |
| 18 | MÉDIA | "Como usuário, quero acesso a um manual de uso e instalação da aplicação." | 3 | 3 |
| 19 | MÉDIA | "Como usuário, quero receber uma notificação quando meu reembolso for aprovado ou rejeitado, para que possa acompanhar meu pedido sem precisar abrir o app o tempo todo." | 1 | 3 |
| 20 | MÉDIA | "Como usuário, quero ver o motivo pelo qual meu reembolso foi rejeitado, para que possa corrigir e reenviar, se necessário." | 1 | 3 |

</details>
<!--
<details>
 <summary>Sprint-1 Backlog</summary>
| Rank | Prioridade | Requisito | Tarefa |
| --- | --- | --- | --- |
</details>
<details>
 <summary>Sprint-2 Backlog</summary>
| Rank | Prioridade | Requisito | Tarefa |
| --- | --- | --- | --- |
</details>
<details>
 <summary>Sprint-3 Backlog</summary>
| Rank | Prioridade | Requisito | Tarefa |
| --- | --- | --- | --- |
</details>
<details>
 <summary>Sprint-4 Backlog</summary>
| Rank | Prioridade | Requisito | Tarefa |
| --- | --- | --- | --- |
</details>
-->

## 🎥 Video Apresentação

<details>
 <summary>Sprints</summary>
<!--  
## Sprint 1   
https://github.com/user-attachments/assets/
## Sprint 2
https://github.com/user-attachments/assets/
## Sprint 3
https://github.com/user-attachments/assets/
## Sprint 4
https://github.com/user-attachments/assets/
-->
</details>

   
<span id="requisitos">
   
## 🔎 Requisitos
   <ul>
      <li>Implementar Aplicação com ORM em BD Relacional.</li>
      <li>Implementar Aplicação com Persistência de JSON (MongoDB por ex).</li>
      <li>Linguagem TypeScript e JavaScript.</li>
      <li>Tecnologias React e ReactNative.</li>
      <li>SO Android e Android SDK.</li>
      <li>Banco de dados NOSQL (ex: Mongo ou equivalente).</li>
      <li>Banco de dados Relacional (ex: MySQL ou equivalente).</li>
   </ul>
   
<span id="tecnologias">
   
## 🖥️Tecnologias:
   <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html,css,js,ts,nodejs,react,tailwind,mysql,mongodb,express,sequelize&perline=3">
   </a>

   
<span id="ferramentas">

## 🛠️ Ferramentas:
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=vscode,github,postman,androidstudio,&perline=5">
  </a>

  
<span id="como-usar">
   
## Como utilizar
#### Requisitos :
 - Node.js v20.6.0 ou superior
 - MySQL 8.0
 - Git
 - MongoDb

### Preparando o projeto
1. Abra o cmd na pasta aonde deseja instalar o projeto
2. Execute o comando 
```bash
git clone https://github.com/Byte-Boost/ExpenseFlow
```
3. Entre no diretório ExpenseFlow\Backend_ExpenseFlow
4. Crie um arquivo chamado ".env"
5. Abra este arquivo com seu editor de texto de preferência, e preencha o mesmo seguindo o modelo ".env.example", presente no mesmo diretório.
6. Repita os passos 4 e 5 no diretório ExpenseFlow\Frontend_ExpenseFlow


### Executando o projeto


#### Backend
1. Certifique-se que seus serviços MySQL e MongoDb estejam rodando
2. Abra o cmd na pasta ExpenseFlow\Backend_ExpenseFlow
3. Rode os comandos: 
```
npm install
npm run start
```

#### Frontend
1. Abra o cmd na pasta ExpenseFlow\Frontend_ExpenseFlow
2. Rode os comandos: 
```
npm install
npx expo start
```


<span id="equipe">
   
## 👥 Equipe:

   ### ![Static Badge](https://img.shields.io/badge/Dev_Team-brightgreen) - Arthur Silva: 
   [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](https://br.linkedin.com/in/arthur-sousa-3287391b1)
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/Meowo2)

   ### ![Static Badge](https://img.shields.io/badge/Dev_Team-brightgreen) - Jaqueline Silva : 
   [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](
   https://www.linkedin.com/in/jaqueline-maria-fran%C3%A7a-veloso-silva/)
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/jaquemfvs)


   ### ![Static Badge](https://img.shields.io/badge/Dev_Team-brightgreen) - João Eduardo Messias : 
   [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](https://www.linkedin.com/in/jo%C3%A3o-eduardo-messias-a3019125b/)
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/joao-eduardo17)


   ###  ![Static Badge](https://img.shields.io/badge/Dev_Team-brightgreen) - Marcos Antonio : 
   [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](
   https://www.linkedin.com/in/marcos-antonio-329449268)
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/oOutroMarcos)


   ###  ![Static Badge](https://img.shields.io/badge/Product_Owner-219ebc) - Markos Nunes : 
   [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](https://linkedin.com/in/markos-vinícius-nunes-230448268)
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/MarkVN2)
   [<img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/markos_vn2)


   ### ![Static Badge](https://img.shields.io/badge/Dev_Team-brightgreen) - Sandro Pimentel : 
   [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](https://www.linkedin.com/in/sandro-roberto-pimentel-junior-1287a3254/)
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/Sandro-Pimentel)
   

   ### ![Static Badge](https://img.shields.io/badge/Scrum_Master-red) - Vinícius Forcato : 
   [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](https://www.linkedin.com/in/vinícius-felipe-forcato-789462268)
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/nininhosam)
   [<img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/nao_sou_felps)

  
   ### ![Static Badge](https://img.shields.io/badge/Dev_Team-brightgreen) - Vitor Saborito : 
   [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](https://br.linkedin.com/in/vitor-henrique-saborito-216219268)
   [<img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">](https://github.com/VituuSaborito )
   

  
