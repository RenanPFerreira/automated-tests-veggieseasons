<a id="readme-top"></a>
# Sobre o Projeto
Olá! 👋
Este é o repositório dos testes automatizados para a aplicação Veggie Seasons. </br>
🇺🇸 EN version? Please click here! 

## 🔧 Desenvolvimento
Esse projeto foi totalmente construído com: Maestro (https://www.maestro.dev/)

## Requisitos
Realize o download do repositório através do link: 
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



<p align="right">(<a href="#readme-top">back to top</a>)</p>















