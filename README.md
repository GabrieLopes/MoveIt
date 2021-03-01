# MoveIt
Esta é uma aplicação que promove a saúde para quem tende a ficar muitas horas seguidas utilizando o computador, por isso seguindo a lógica de concentração "Pomodoro" foi desenvolvido essa aplicação que consiste em realizar diferentes exercícios durante intervalos cronometrados, alguns exemplos são exercícios para a visão e para diferentes regiões do nosso corpo. As tecnologias utilizadas para o desenvolvimento do mesmo foram React, Typescript e NextJS.

https://move-it-bhi9nedzf-gabrielopes.vercel.app

**Primeiros passos:** Primeiramente precisamos escolher alguma IDE de sua preferência, neste exemplo estarei utilizando o Visual Studio Code, antes de começarmos qualquer coisa precisamos instalar o Node (v14.15.5), NPM (v6.14.11) e o Yarn (v1.22.0), agora sim nós já podemos fazer o clone do projeto, logo após isso se certifique de entrar no diretório correto pelo terminal, no mesmo utilize o comando "yarn" para instalarmos todas as dependências automaticamente. Se nenhum erro aparecer você pode iniciar a aplicação com o comando "yarn dev" e você verá a seguinte tela (Lembrando que o meu navegador é o Opera e que precisamos permitir as notificações): 

![image](https://user-images.githubusercontent.com/53949034/109439542-7ae62a00-7a0d-11eb-801e-4c200724e91f.png)
 
 
 

**Como funciona?** 

A funcionalidade mais aparente é o botão para "Iniciar um ciclo" 


![image](https://user-images.githubusercontent.com/53949034/109439611-d7494980-7a0d-11eb-9494-be8ee732269a.png)

Quando clicamos nele o timer começa e caso ele chegue a "00:00" sem ser interrompido você será notificado com o som da notificação e receberá um novo desafio 


![image](https://user-images.githubusercontent.com/53949034/109439659-0fe92300-7a0e-11eb-998b-57cbed748b12.png) 


Caso você complete o desafio você receberá uma quantia de XP e o seu indicador de desafios concluídos irá acumular, porém caso você não complete o botão de "Iniciar um ciclo" aparecerá novamente. 

![image](https://user-images.githubusercontent.com/53949034/109439921-0dd39400-7a0f-11eb-9bc9-7e080aeab15b.png)

Este é um bom exemplo de como o seu contador ficará.



E por fim, caso você clique no botão "Iniciar um ciclo" e logo após clicar em "Abandonar ciclo" o timer irá reiniciar, pois não podemos trapaçear nos nossos momentos de concentração 

![image](https://user-images.githubusercontent.com/53949034/109439746-622a4400-7a0e-11eb-8202-5361edcd643e.png)

