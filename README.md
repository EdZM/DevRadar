# Aplicativo de teste para encontrar/cadastrar/remover desenvolvedores (Semana Omnistack)

## Implementado usando ReactJS, React Native e NodeJS

### Para testar usando o Gitpod: 
  - Instale o gitpod;
  - Recarregue essa página e clique no botão [Gitpod]() ao lado de [Clone or Download]() ou [nesse link](https://gitpod.io/#https://github.com/EdZM/DevRadar)
  - Na aba que abrir, vá no terminal na parte inferior da tela 
  - Para testar o front end: 
    
    ```
    cd web/
    yarn start 
    ```
    
    - Caso apareça janelas exigindo a exposição de algumas portas, clique em [Expose]() em cada janela que aparecer.
    - Irá aparecer duas opções : [Open Browser]() ou [Open Preview]().
    - Selecione uma delas.
  
  - Para testar o mobile:  
    
    ```
    cd mobile/
    yarn start  
    ```
    
    - Instalar expo no celular via Play Store
    - Com o expo aberto no celular, escaneie o QR code que aparecer no terminal após o comando `yarn start`
    
  - Para testar o back end: 
    
    ``` 
    cd backend/
    yarn dev
    ```
    
    - OBS.: Ao rodar com o gitpod, o back end não estará integrado com as demais partes. Para rodar a versão totalmente integrada dessa aplicação é necessário clonar o repositório localmente
    
### Para testar localmente:
  - Abra o terminal.
  - Clone esse repositorio com o comando `git clone <link desse repo>`
  - Execute a parte do back end acima, e mantenha esse terminal aberto 
  - Abra outro terminal e execute a parte do front end ou mobile ambos citados acima
  - Pronto
