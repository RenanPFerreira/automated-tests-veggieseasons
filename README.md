# Sobre o Projeto
Olá! 👋
Este é o repositório dos testes automatizados para a aplicação Veggie Seasons. </br>
🇺🇸 EN version? (<a href="#english-version">Please click here!</a>)</p>

## 🔧 Desenvolvimento
Esse projeto foi totalmente construído com: Maestro (https://www.maestro.dev/)

## Requisitos
Realize o download do repositório através do link: </br>
Para executar os cenários, primeiramente é necessário realizar a instalação do Maestro em seu equipamento, o caminho com todos os passos necessários se encontra na documentação oficial da página: 
https://docs.maestro.dev/getting-started/installing-maestro

Foi utilizado para desenvolver um aparelho físico Android 14. 
Mas fica a seu critério utilizar qualquer Android que seja compatível com o app.


## Maestro
Esse framework utiliza a extensão .yaml para executar os cenários e o comando abaixo
```diff
+ maestro test nomedoarquivo.yaml
```
No caminho /test você encontrará todos os cenários que foram desenvolvidos. 
Como boa prática recomendo seguir a ordem descrita abaixo:  
</br>
![image](https://github.com/user-attachments/assets/e5ae926b-2d41-4939-87e9-7b3c70d32717)

## Rodar o código
Após instalar o Maestro em seu equipamento e estar com seu emulador ou dispositivo físico configurado, basta executar os passos abaixo
```diff
1 - Abrir seu terminal aonde está a pasta test com os códigos
2 - Executar chamando o comando maestro test 1-checkingList.yaml
3 - Após concluir seguir para os demais arquivos
```
## Descrição dos cenários
##### 1-checkingList: Busca pelo vegetal Endívia dentro da listagem que aparece no botão Home e clica no mesmo para certificar que está ok.
##### 2-checkingDetails: Busca pelo elemento acima na listagem Home e clica sobre o mesmo, ao final do processo é capturado uma evidência para comparativo.
##### 3-favoriteTest: Busca pelo limão na listagem da Home, clica sobre o mesmo e o favorita, após verifica se o mesmo foi registrado no menu My Garden e realiza uma captura da tela com o registro.
##### 4-changingCalories: Entra no menu de configuração, tira uma evidencia do mesmo no padrão de 2000kcal e faz a mudança para 2400kcal, após captura as evidências para comparar.
##### 5-searchTest: Entra no menu de pesquisa e realiza consultas com alguns vegetais e palavras que não são encontradas.
##### 6-checkingCategories: Cenário extra, que realiza mudanças nas categorias favoritas e testa o botão de reset de configuraçöes.
##### 7-checkingMyGarden: Cenário extra, que garante que o menu MyGarden é resetado ao iniciar o app.

## Demos
#### Exemplo da execução do cenário 3-favoriteTest
![maestro-favoriteTest](https://github.com/user-attachments/assets/01e0d94e-dcd7-477e-8027-150c7690d52b)

## Uso de AI
Durante a criação dos códigos utilizei prompts buscando melhores formas de escrita para o proprio Maestro.
Pensando a longo prazo para um projeto, gostaria de utilizar e entender mais a fundo o uso da IA para comparar as imagens do aplicativo como uma forma de teste de regressão visual.
Acredito que seria uma excelente forma de comparar valores em casos onde o Maestro não consegue identificar 100%.


## EULA
Este repositório foi criado para estudos e será utilizado apenas para essa finalidade, com toda responsabilidade do desenvolvedor Renan Ferreira

</br>
</br>
</br>
</br>
</br>

</br>
</br>
</br>
</br>
</br>

</br>
</br>
</br>
</br>
</br>

<a id="english-version"></a>


# About the Project

Hello! 👋 
This is the repository for the automated tests of the Veggie Seasons application.


# 🔧 Development

This project was entirely built using: Maestro (https://www.maestro.dev/)


# Requirements

Download the repository using the following link: </br>
To execute the test scenarios, you first need to install Maestro on your device. You can find all the necessary steps in the official documentation:
https://docs.maestro.dev/getting-started/installing-maestro

For development, an Android 14 physical device was used.
However, you can use any Android device that is compatible with the app.

# Maestro

This framework uses the .yaml extension to execute test scenarios with the following command:

```diff
+ maestro test filename.yaml
```

Inside the /test folder, you will find all the developed scenarios.
As a best practice, I recommend following the order described below:


![image](https://github.com/user-attachments/assets/e5ae926b-2d41-4939-87e9-7b3c70d32717)


# Running the Code

After installing Maestro on your device and configuring your emulator or physical device, simply follow the steps below:
```diff
1 - Open your terminal in the folder where the test scripts are located  
2 - Run the command maestro test 1-checkingList.yaml  
3 - After completing the first test, proceed to the remaining test files  
```
# Scenario Descriptions
##### 1-checkingList: Searches for the vegetable Endive in the list displayed on the Home button and clicks on it to verify that it is working correctly.
##### 2-checkingDetails: Searches for the previously mentioned item in the Home list, clicks on it, and captures evidence for comparison at the end of the process.
##### 3-favoriteTest: Searches for a lemon in the Home list, clicks on it, and adds it to favorites. Then, it verifies if it was successfully added to the My Garden menu and captures a screenshot for recordkeeping.
##### 4-changingCalories: Opens the settings menu, captures evidence of the default 2000 kcal setting, changes it to 2400 kcal, and captures new evidence for comparison.
##### 5-searchTest: Opens the search menu and tests searches for various vegetables as well as terms that are not found.
##### 6-checkingCategories: An additional scenario that changes favorite categories and tests the reset settings button.
##### 7-checkingMyGarden: An additional scenario that ensures the My Garden menu resets when the app is restarted.


# Demos
Example of the execution of scenario 3-favoriteTest
![maestro-favoriteTest](https://github.com/user-attachments/assets/01e0d94e-dcd7-477e-8027-150c7690d52b)

# AI Usage
During the creation of the test scripts, I used AI-generated prompts to find better ways to write for Maestro itself.
Thinking long-term for this project, I would like to explore and better understand the use of AI to compare app images as a form of visual regression testing.
I believe this would be an excellent way to compare values in cases where Maestro cannot achieve 100% accuracy in identification.


# EULA

This repository was created for study purposes and will be used solely for that purpose, with full responsibility assumed by the developer Renan Ferreira.
