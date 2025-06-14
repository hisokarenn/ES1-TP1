# Tabela de Tecnologias e Ferramentas (Tech Stack Map)

<p align="justify"> Em desenvolvimento de software, uma "tech stack" ou "pilha tecnológica" refere-se ao conjunto de ferramentas e tecnologias utilizadas para construir, executar e manter um projeto de software, como um site, aplicativo ou serviço. Isso inclui linguagens de programação, frameworks, bancos de dados, servidores, e outras ferramentas e componentes.

<p align="justify"> Foi elaborado um Mapa de Tecnologias (Tech Stack Map) e uma tabela que demonstram as tecnologias e ferramentas principais que seriam utilizadas para o desenvolvimento do aplicativo móvel.
<br>
<br>
  
## Tech Stack Map
<p align="justify"> Este mapa de tecnologia descreve a arquitetura e as tecnologias recomendadas para o desenvolvimento do sistema B Health, uma aplicação de gestão de vacinação que possui funcionalidades como autenticação, notificações, geolocalização e histórico de vacinas. A seguir é explicado detalhadamente cada parte do diagrama:
<br>
<br>

<p align="center"> <img src="https://github.com/hisokarenn/ES1-TP1/blob/00b0cc85bc88eadf9e018a9982a756f590116eb8/Arquitetura_do_Software/Imagens/Tech_Stack_Map/mapaDeTecnologias.drawio.png" alt="" width="1200"
<br>
<p align="center"> Mapa de Tecnologias gerado no Draw.io

---

<br>

## Estrutura Geral
O sistema BHEALTH está no centro e é dividido em sete módulos principais, que representam os blocos funcionais do sistema:

**1. Front-end**<br>
**2. Back-end** <br>
**3. Banco de Dados** <br>
**4. Autenticação** <br>
**5. Notificações** <br>
**6. Geolocalização** <br>
**7. Deploy** <br>

Cada módulo está ligado a uma tecnologia específica, com um balão descritivo explicando o que é a tecnologia e por que foi escolhida.

<br>

## Explicação sobre os itens disponíveis na imagem

<p align="justify"> A imagem a seguir é a legenda do mapa de tecnologia do aplicativo B Health que utiliza cores e formas para representar o papel de cada elemento no sistema. O mapa identifica o tipo de informação apresentada, como o nome do sistema, tecnologias recomendadas, alternativas disponíveis e descrições técnicas associadas às escolhas. Esses marcadores visuais facilitam a leitura e a compreensão rápida do diagrama: 
<br>
<br>

<p align="center"> <img src="https://github.com/hisokarenn/ES1-TP1/blob/00b0cc85bc88eadf9e018a9982a756f590116eb8/Arquitetura_do_Software/Imagens/Tech_Stack_Map/cores%20e%20identififca%C3%A7%C3%A3o.png" alt="" width="300"
<br>
  
---

<br>

<p align="justify"> Nesta imagem são apresentados o nome do aplicativo, sua descrição e as camadas que compõem sua arquitetura tecnológica. Cada camada representa uma parte fundamental do sistema, destacando as tecnologias utilizadas para o desenvolvimento do front-end, back-end, banco de dados, autenticação, notificações, geolocalização e deploy, oferecendo uma visão clara e estruturada da solução proposta:
<br>
<br>

<p align="center"> <img src="https://github.com/hisokarenn/ES1-TP1/blob/00b0cc85bc88eadf9e018a9982a756f590116eb8/Arquitetura_do_Software/Imagens/Tech_Stack_Map/camadas%20e%20tecnologias.png" alt="" width="500"
<br>

---

<br>
A seguir, estão todas as tecnologias que foram utilizadas no projeto, com uma explicação sobre o que é cada uma, para que serve e por que ela foi escolhida.
<br>
<br>

<p align="center"> <img src="https://github.com/hisokarenn/ES1-TP1/blob/00b0cc85bc88eadf9e018a9982a756f590116eb8/Arquitetura_do_Software/Imagens/Tech_Stack_Map/front-end.png" alt="" width="500"
<br>
  
<p align="center"> <img src="https://github.com/hisokarenn/ES1-TP1/blob/00b0cc85bc88eadf9e018a9982a756f590116eb8/Arquitetura_do_Software/Imagens/Tech_Stack_Map/back-end.png" alt="" width="500"
<br>

<p align="center"> <img src="https://github.com/hisokarenn/ES1-TP1/blob/00b0cc85bc88eadf9e018a9982a756f590116eb8/Arquitetura_do_Software/Imagens/Tech_Stack_Map/banco%20de%20dados.png" alt="" width="500"
<br>

<p align="center"> <img src="https://github.com/hisokarenn/ES1-TP1/blob/00b0cc85bc88eadf9e018a9982a756f590116eb8/Arquitetura_do_Software/Imagens/Tech_Stack_Map/Autentica%C3%A7%C3%A3o.png" alt="" width="500"
<br>

<p align="center"> <img src="https://github.com/hisokarenn/ES1-TP1/blob/00b0cc85bc88eadf9e018a9982a756f590116eb8/Arquitetura_do_Software/Imagens/Tech_Stack_Map/Notifica%C3%A7%C3%B5es.png" alt="" width="500"
<br>

<p align="center"> <img src="https://github.com/hisokarenn/ES1-TP1/blob/00b0cc85bc88eadf9e018a9982a756f590116eb8/Arquitetura_do_Software/Imagens/Tech_Stack_Map/geolocaliza%C3%A7%C3%A3o%20.png" alt="" width="500"
<br>

<p align="center"> <img src="https://github.com/hisokarenn/ES1-TP1/blob/00b0cc85bc88eadf9e018a9982a756f590116eb8/Arquitetura_do_Software/Imagens/Tech_Stack_Map/deploy.png" alt="" width="500"
<br>

---

## Tabela de Tecnologias
<p align="justify"> Na tabela a seguir, estão listadas as tecnologias usadas em cada parte do sistema, com uma breve explicação do motivo de cada escolha. A ideia foi escolher ferramentas que deixassem o B Health rápido, fácil de usar e que atendessem bem às funções que ele precisa.
<br>
  
|Camada|Tecnologias|Justificativa|
|-|-|-|
|<p align="center">Front-end|<p align="center">Flutter|<p align="justify">O Flutter é um framework (usa a linguagem de programação Dart) que é bem interessante de ser utilizado, pois este possui alto desempenho, fluido e é multiplataforma (IOS, Android, Web, MacOs, Windows e Linux). Além disso, é de fácil integração com Firebase.|
|<p align="center">Back-end|<p align="center">Node.js + Express|<p align="justify">Para lidar com várias conexões simultâneas, o Node.js é interessante de ser utilizado. Já o Express fica responsável por organizar as APIs, pelo motivo de possuir uma estrutura flexível e fluida.|
|<p align="center">Banco de Dados|<p align="center">PostgreSQL (PostGIS)|<p align="justify">O PostgreSQL é um banco de dados relacional que é bom para armazenar dados mais complexos. O PostGIS é relevante porque ele gerencia dados geoespaciais de forma eficiente. Assim, o controle das funcionalidades de localização dos pacientes e de campanhas de vacinas se tornam mais eficazes. Este banco de dados também facilita a integração com o Mapbox.|
|<p align="center">Autenticação|<p align="center">Firebase Authentication|<p align="justify">O Firebase Authentication fornece a autenticação segura com suporte a múltiplos provedores (email/senha, OAuth, etc). Ademais, a gestão e controle de acesso dos usuários se tornam simplificadas.|
|<p align="center">Notificações|<p align="center">Socket.IO + Firebase Cloud Messaging (FMC)|<p align="justify">O Socket.IO possibilita comunicação bidirecional persistente, o qual permite atualizações instantâneas que são relevantes para os agendamentos no B Health. Já o FCM ajuda no envio confiável de notificações push, isso ocorre até quando o aplicativo está em segundo plano.|
|<p align="center">Geolocalização|<p align="center">Google Maps SDK|<p align="justify">O Google Maps SDK possui uma grande cobertura mais completa e atualizações frequentes de localização.|
|<p align="center">Deploy|<p align="center">Railway|<p align="justify">Plataforma de deploy e infraestrutura moderna, usada para hospedar o back-end Node.js e o banco de dados PostgreSQL. Para mais, ele fornece suporte integrado para múltiplas linguagens e bancos, com escalabilidade automática e monitoramento.|
