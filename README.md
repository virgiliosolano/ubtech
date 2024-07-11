# Bootcamp Kotlin Multiplatform com Gemini API & OpenAI API

Olá! Eu sou  o Virgílio Magalhães e este guia irá te ajudar a construir um App que consome as API's do **Google Gemini** e **OpenAI**. 

Este guia foi construído para o bootcamp no **1º UBTECH EXPERIENCE, Simpósio Paraibano de Tecnologia e Inovação**, realizado em João Pessoa, Paraíba - Brasil.

**Este guia está organizado de modo que você possa:**

 1. Configurar o ambiente necessário para construir Apps com Kotlin Multiplatform
 2. Construir um App Android utilizando o Android Studio que consome a API do Google Gemini e possa ser convertido para um projeto Kotlin Multiplatform
 3. Configurar as dependências necessárias para rodar um projeto em Android e iOS em Kotlin Multiplatform
 4. Criar um projeto em Kotlin Multiplatform do zero considerando a utilização do Compose Multiplatform
 5. Consumir a API da OpenAI
 6. Desafio: Trocar mensagens entre as API's do Google Gemini e OpenAI através do recurso de Chat

# Configuração Inicial

A configuração a seguir depende do sistema operacional que você utiliza, para Windows e Linux Dist os passos serão os mesmos. Para usuários de MacOS haverá alguns passos a mais devido o suporte para executar o projeto para iOS.

## Windows e Linux Dist

 1. Faça o download do Android Studio em: [https://developer.android.com/studio](https://developer.android.com/studio)
 2. Instale o Android Studio e em seguida abra o console e digite: **java -v** 
 3. Caso o Java não esteja instalado, baixe e instale através do link: [https://www.oracle.com/java/technologies/downloads](https://www.oracle.com/java/technologies/downloads)
 4. Com o Android Studio aberto, vá até  **Configurações -> Plugins** e na opção  **Marketplace** pesquise pelo  **Plugin** do  **Kotlin Multiplatform**, instale e reinicie o Android Studio
 5. https://developer.android.com/studio/preview/gemini

## MacOS

 1. Para quem possui MacOS, atualize o XCode para a última versão, possivelmente você tenha que atualizar o MacOS antes.
 2. Para validar o seu ambiente, será necessário instalar o KDoctor

     `brew install kdoctor`

 3. Em seguida digite o comando no console: `kdoctor` 
 4. Caso seja encontrado alguma inconsistência, faça o devido ajuste, caso contrário o seu ambiente está pronto.

# Criando o seu App Kotlin Multiplatform

Para criar o nosso App Kotlin Multiplatform podemos utilizar 3 abordagens

 1. Android Studio -> Novo Projeto -> Kotlin Multiplatform App
 2. Pelo Wizard da JetBrains
	 2.1. https://www.jetbrains.com/help/kotlin-multiplatform-dev/multiplatform-create-first-app.html
	 2.2. https://www.jetbrains.com/help/kotlin-multiplatform-dev/compose-multiplatform-create-first-app.html

## Criando a sua API Key do Gemini no AI Studio

https://aistudio.google.com/app/apikey


## Criando a sua API Key no OpenAI

https://platform.openai.com/api-keys

## Criando um App Android com Suporte ao Google Gemini API

 1. Android Studio -> Novo Projeto -> Gemini API Starter
 

### Converter o Projeto Android para Multiplatform

 1. https://www.jetbrains.com/help/kotlin-multiplatform-dev/multiplatform-integrate-in-existing-app.html

## Configurando um projeto KMP para utilizar a API do Gemini

 1. ......

## Configurando um projeto KMP para utilizar a API do OpenAI

 1. ......


# Projetos de Referência

 1. https://github.com/joreilly/GeminiKMP/tree/main
 2. https://github.com/google-gemini/generative-ai-android
 3. Wizard do Android Studio com Gemini

# Desafio 1

Utilizando os projetos de referência, customizar o projeto base para contemplar um dos ou mais seguintes casos de uso:

 1. Enviar texto para API
 2. Enviar Imagem para API
 3. Manter um fluxo conversacional com a API, Chat

> Before starting to publish, you must link an account in the **Publish** sub-menu.

# Desafio 2

 1. Configurar o cliente do OpenAI e colocar uma IA para conversar com a outra, aguardando o tempo de resposta entre elas

# Bibliotecas para uso

 1. https://github.com/terrakok/kmp-awesome
 2. https://github.com/icerockdev/moko-mvvm/
 3. https://voyager.adriel.cafe/android-viewmodel/viewmodel-kmp/
 4. https://github.com/Kamel-Media/Kamel
 5. https://ktor.io/
 6. https://github.com/Kotlin/kotlinx.serialization

# Referências

 1. https://www.jetbrains.com/help/kotlin-multiplatform-dev/get-started.html
 2. https://developer.android.com/kotlin/multiplatform
 3. https://ai.google.dev/gemini-api/docs/get-started/
 4. https://android-developers.googleblog.com/2023/12/leverage-generative-ai-in-your-android-apps.html
 5. https://platform.openai.com/docs/quickstart?context=curl
 6. https://aistudio.google.com/
 7. [Build an iOS & Android app in 100% Kotlin with Compose Multiplatform by Jetbrains](https://www.youtube.com/watch?v=5_W5YKPShZ4)

# Contato

 - Virgilio Magalhaes
 - virgilio@bossanovalabs.com - www.bossanovalabs.com
 - virgilio@agrobee.net - www.agrobee.net
