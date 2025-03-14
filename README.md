# Sobre o Projeto
Olá! 👋
Este é o repositório dos testes automatizados para a aplicação Veggie Seasons. 

## 🔧 Desenvolvimento
Esse projeto foi totalmente construído com: Maestro (https://www.maestro.dev/)

## Requisitos

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
