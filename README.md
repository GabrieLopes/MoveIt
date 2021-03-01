# MoveIt

As tecnologias utilizadas foram React, Typescript e NextJS

**Primeiros passos:** Primeiramente precisamos escolher alguma IDE de sua preferência, neste exemplo estarei utilizando o Visual Studio Code, antes de começarmos qualquer coisa precisamos instalar o Node (v14.15.5), NPM (v6.14.11) e o Yarn (v1.22.0), agora sim nós já podemos fazer o clone do projeto, logo após isso se certifique de entrar no diretório correto pelo terminal, no mesmo utilize o comando "yarn" para instalarmos todas as dependências automaticamente. Se nenhum erro aparecer você pode iniciar a aplicação com o comando "yarn dev" e você verá a seguinte tela (Lembrando que o meu navegador é o Opera): ![image](https://user-images.githubusercontent.com/53949034/109439542-7ae62a00-7a0d-11eb-801e-4c200724e91f.png)
 

**Funcionalidades:** A funcionalidade mais aparente é o botão de "Iniciar um ciclo" 
![image](https://user-images.githubusercontent.com/53949034/109439611-d7494980-7a0d-11eb-9494-be8ee732269a.png)
, quando clicamos nele o timer começa e caso ele chegue a 0 sem ser interrompido você será notificado com um som da notificação e receberá um novo desafio 
![image](https://user-images.githubusercontent.com/53949034/109439659-0fe92300-7a0e-11eb-998b-57cbed748b12.png) 
Caso você complete o desafio você receberá uma quantia de XP e o seu indicador de desafios concluídos irá acumular, porém caso você não complete o botão de "Iniciar um ciclo" aparecerá novamente. 

Caso você clique no botão "Iniciar um ciclo e logo após clicar em "Abandonar ciclo" o timer irá reiniciar, pois não podemos trapaçear nos nossos momentos de concentração 
![image](https://user-images.githubusercontent.com/53949034/109439746-622a4400-7a0e-11eb-8202-5361edcd643e.png)

