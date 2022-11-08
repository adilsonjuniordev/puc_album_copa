# Album de Figurinhas da Copa 2022 - Qatar

Projeto desenvolvido para a disciplina de Laboratório de Projetos de Sistemas, a fim de propor a solução de um problema, colocando em prática a arquitetura MVP com Flutter e vários outros conceitos do mundo Mobile.

<br>

Link para acessar o [**Slide de apresentação da primeira entrega**](https://www.canva.com/design/DAFRSj2La4E/FOUZs2iDxC1_5Nr2KAmxbQ/view?utm_content=DAFRSj2La4E&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

<br>

**Integrantes:**

- Adilson Antonio Pereira Junior
- Pedro Augusto Costa Senciano
- Raony Lino de Oliveira

<br>

**Descrição do Sistema:**

O objetivo do projeto é um aplicativo mobile para gerenciamento de figurinhas do album da copa de 2022 no Qatar, com o propósito de centralizar de maneira organizada as figurinhas do usuário, para que ele possa saber:

1. Quais/quantas figurinhas do album já possui.
2. Quais/quantas figurinhas do album estão faltando.
3. Quais/quantas figurinhas do album são repetidas.

<br>

**Estórias de Usuários:**

1. Como Alice, quero ter agilidade na identificação das figurinhas que possuo em minha coleção.
2. Como Márcio, quero facilidade ao gerenciar minhas figurinhas.
3. Como Ramon, quero saber quais figurinhas estão faltando na minha coleção.
4. Como Yumi, quero saber quais e quantas figurinhas repetidas possuo.
5. Como Marcelo, quero saber quais são os jogadores de uma seleção.

<br>

# Testando o App (depuração pela IDE)

Instale o SDK do [**Flutter**](https://docs.flutter.dev/get-started/install) na versão mais recente do canal **Stable**.
Em seguida [**configure a IDE**](https://docs.flutter.dev/get-started/editor) de preferência.

1 - Abra o terminal na raiz do projeto.<br>
2 - Execute o comando abaixo para baixar os pacotes e dependências do projeto:

```sh
> flutter pub get
```

3 - Abra o emulador **OU** conecte um dispositivo Android via USB e certifique-se de que a IDE o identificou.<br>
4 - Execute o comando abaixo para instalar e executar o projeto:

```sh
> flutter run
```
___

# Testando o App (Instalação APK)

> Copie o arquivo **installer.apk** para o dispositivo Android e execute-o.
> Ao concluir a instalação basta abri-lo
___
> Caso esteja instalando pelo ADB, execute o seguinte comando via terminal:
```sh
> adb install installer.apk
```
___
# Credenciais de Acesso

> Ao abrir o APP será solicitado **e-mail** e **senha** para se autenticar:

| Email | Senha |
| ----------------- | ------ |
| teste@pucminas.br | 123456 |


<br>

## Screenshots

<p float="left">
  <img src="assets/screenshots/splash.jpg" href="#" alt="Splash Page" width="240">
    <img src="assets/screenshots/home.jpg" href="#" alt="Home Page" width="240">
    <img src="assets/screenshots/my_stickers.jpg" href="#" alt="My Stickers Page" width="240">
    <img src="assets/screenshots/login.jpg" href="#" alt="Login Page" width="240">
    <img src="assets/screenshots/register.jpg" href="#" alt="Register Page" width="240">
</p>

## Packages utilizados

Foram utilizados os packages abaixo para auxiliar na construção do projeto:

- top_snackbar_flutter: ^2.1.1
- loading_animation_widget: ^1.2.0+3
- flutter_getit: ^1.2.1
- flutter_dotenv: ^5.0.2
- dio: ^4.0.6
- validatorless: ^1.2.1
- shared_preferences: ^2.0.15
- flutter_awesome_select: ^6.5.0
