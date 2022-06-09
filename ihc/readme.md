# Heurísticas de Nielsen e WCAG

**1. Visibility of System Status**

Ao respeitar essa heurística, a aplicação deve indicar ao usuário o estado de um componente em tela ou operação em andamento. Um exemplo seria, promoções de jogos no site da steam (https://store.steampowered.com/?l=portuguese), indicando preços antigos, novos e validade da promoção.

<div align="center">

![image](https://user-images.githubusercontent.com/55204419/164981557-f61cf3eb-d512-41d0-bf8e-869e6316f3f8.png)

</div>

**3. User Control and Freedom**

A aplicação deve disponibilizar meios para o usuário desfazer um erro cometido por engano, ou por falta de clareza. Um exemplo seria ao deletar um arquivo no google drive, a plataforma oferece um recurso de desfazer ação, para caso o usuario tenha se enganado ou se arrependido de ter feito uma ação custosa, como remover um arquivo importante.


| Removendo um arquivo do Google Drive     |   Opção para desfazer a remoção se feita por engano  |
| :--------------------------------: | :-------------------------------------------: |
| ![image](https://user-images.githubusercontent.com/55204419/164980765-a2915269-0b5b-4f0b-ba18-bf2edd8d158a.png) | ![image](https://user-images.githubusercontent.com/55204419/164980718-5fb5bc32-5f42-4c3a-861a-3a348c7b4210.png) |

**9. Help users recognize, diagnose and recover from errors**

Mesmo que a aplicação tenha uma funcionalidade de desfazer ações, pode ocorrer desta funcionalidade nao ser adequada a alguma situação como enviar um arquivo de extensão inadequada a situação ou da regra de negocio do sistema. Logo, o sistema tem que ajudar o usuario a encontrar o gargalo e auxiliá-lo a encontrar o caminho da solução e prosseguir com o funcionamento da aplicação.

| Instrução para enviar um arquivo PDF | Instrução para escolher um arquivo adequado para o sistema |
| :--------------------------------: | :-------------------------------------------: |
| ![image](https://user-images.githubusercontent.com/55204419/164982028-5baa71b9-90d4-4f6a-89e3-afcd23cefa75.png) | ![image](https://user-images.githubusercontent.com/55204419/164982012-cadd48f7-07cf-4492-b3fe-0b994721c4b8.png) |

---
# WCAG


### 1.3.4 Orientation (Level AA)

Não restringir a exibição e a operação do conteúdo a uma única orientação de exibição (retrato ou paisagem), a menos que uma orientação de exibição específica seja essencial.

Um exemplo é o nosso projeto feito através do projeto integrador da FATEC [HelpDuck](https://help-duck.netlify.app/).

| Site em modo retrato     |   Site em modo paisagem  |
| :--------------------------------: | :-------------------------------------------: |
| ![image](https://user-images.githubusercontent.com/55204419/172738913-5ad8b710-8038-4190-a1bf-fa95314e31a3.png) | ![image](https://user-images.githubusercontent.com/55204419/172738926-474116f3-473e-4a3d-bf6c-aa2c37a61aa6.png)|


### 2.4.11 Focus Appearance (Minimum) (Level AA)
    
A intenção do padrão WCAG 2.4.11 é ajudar usuários com baixa visão que usam um teclado para navegar em um site, garantindo que o ponto de foco atual seja claramente visível. Para passar neste critério basta projetar uma borda grossa ao redor do elemento como no exemplo abaixo do site da steam:
![image](https://user-images.githubusercontent.com/55204419/172734064-026bc80e-2c6c-44c5-af59-b25db7435dc5.png)


### 3.3.8 Redundant Entry (Level A)

A intenção do padrão WCAG 3.3.8 é ajudar os usuários com dificuldades de memória de curto prazo e outros problemas cognitivos a limitar a necessidade de recuperar informações fornecidas em uma etapa anterior de um processo, como o envio de um formulário.

Exemplos para passar esse critério incluem permitir que o usuário confirme que o endereço de cobrança e o endereço de entrega são o mesmo endereço ou até mesmo cartões de créditos.

Exemplos para executar uma compra no site da Amazon:

![image](https://user-images.githubusercontent.com/55204419/172736130-35a5f852-74da-436a-a0d3-ea141b83bc7c.png)


> ![image](https://user-images.githubusercontent.com/55204419/172736472-7fb409d7-f758-475f-84f3-92d43f6541e9.png) <br>
> informações apagadas para privacidade do autor deste repositório.

<br>

