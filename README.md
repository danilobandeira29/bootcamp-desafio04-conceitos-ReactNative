# conceitos-ReactNative
## Desafios Resolvidos
- Likes should add a like to the like counter of the repository

## Instalando as dependências
Com o terminal aberto no diretório da aplicação, basta executar o comando:
```
yarn
```
## Iniciando a aplicação
Com o terminal aberto no diretório da aplicação, executar o comando:

Caso deseje utilizar um aparelho android (ou emulador android)
```
yarn android
```
**OU**

Caso deseje utilizar um aparelho ios (ou emulador ios)
```
yarn ios
```

*Para ambos os casos, o back-end dessa aplicação deve ser inicializado, disponível em: [conceitos-NodeJS](https://github.com/danilobandeira29/conceitos-NodeJS)*

## Testes da aplicação
Com o terminal aberto no diretório da aplicação, basta executar o comando:
```
yarn test
```
## Possíveis erros

Para usuários android:

Erro:
```
"Android project not found. Are you sure this is a React Native project? If your Android files are located in a non-standard location (e.g. not inside ‘android’ folder) consider setting ‘project.android.sourceDir’ option to point to a new location. Run CLI with –verbose flag for more details. ”
```
Solução:
- Ir no diretório da aplicação e acessar ```./android/app/build/intermediates/signing_config/debug/out```
- Deletar o arquivo *signing-config.json* e executar o comando ```yarn android```
