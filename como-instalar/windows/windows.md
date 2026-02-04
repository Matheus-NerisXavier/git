1. Pra começar, acesse o link de download para Windows:

 https://git-scm.com/install/windows

2. Não se esqueça de selecionar o download conforme a arquitetura da sua máquina: *32bits* ou *64bits;*

3. Clique no arquivo que foi baixado para ser executado. 
Uma tela como essa deverá aparecer:

4. Selecione a pasta em que você irá instalar o arquivo:

5. Siga para o próximo passo:

6. Selecione a opção para que o Visual Studio Code seja o seu editor padrão para o uso do git:

7. Você pode já setar o nome da sua branch pra main para facilitar quando for subir seus arquivos pro GitHub:

8. Selecione a opção recomendada para que você possa utilizar o git por linha de comando e também por software de terceiros.

9. O git já vem com o seu próprio SSH Client, como não há necessidade de usar um específico, pode manter essa opção padrão:

10. Essa opção está relacionada aos certificados do servidor. 
Você pode selecionar a opção padrão:

11. Esse passo está relacionado à forma como os dados são formatados e qualquer alteração pode causar problemas.😖
É recomendado que você selecione a opção padrão: 

12. Escolha o emulador de terminal que você deseja usar.

13. Agora você vai selecionar o que o comando git pull deve fazer. 
Basta deixar a opção padrão selecionada:

14. Em seguida você deve escolher qual o auxiliar de credenciais que você vai querer usar. Recomendamos utilizar a opção padrão já que é mais estável:

15. As próximas etapas são customizações que você pode ou não fazer na sua instalação. 
Basta deixar selecionada a opção padrão:

16. Ou simplesmente não selecionar nada e partir pra instalação!
Ufa, hein? Chegamos na etapa final! Basta clicar em Install!


### Configurando credenciais
Basta rodar esses comandos no seu terminal: 

⚠️ Lembre-se de substituir o que está entre aspas pelas suas informações pessoais!

```jsx
git config --global user.name “**username**”
```

```jsx
git config --global user.email “**email**”
```