# Lunch Tray App

O **Lunch Tray App** é um aplicativo de pedidos de almoço interativo construído com Jetpack Compose. Este projeto faz parte do exercício para aprender navegação do curso "Android Basics in Compose". Minha função foi adicionar a navegação ao aplicativo usando compose. Como foi proposto no [Codelab](https://developer.android.com/codelabs/basic-android-kotlin-compose-practice-navigation?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-compose-unit-4-pathway-2%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fbasic-android-kotlin-compose-practice-navigation#0).

## Capturas de tela
![Fluxo](https://developer.android.com/static/codelabs/basic-android-kotlin-compose-practice-navigation/img/6e7d1c4638c64988_960.png)

## Funcionalidades

- Seleção de itens do menu (entrada, acompanhamento e complemento).
- Navegação entre múltiplas telas usando Jetpack Compose.
- Barra superior com título e botão de navegação.

## Pré-requisitos

- Android Studio Arctic Fox ou superior.
- Kotlin 1.5.10 ou superior.
- Dispositivo ou emulador rodando Android 5.0 (Lollipop) ou superior.

## Como executar o projeto

1. Clone o repositório para a sua máquina local:
    ```bash
    git clone https://github.com/seu-usuario/lunch-tray-app.git
    ```
2. Abra o projeto no Android Studio.
3. Conecte um dispositivo Android ou inicie um emulador.
4. Clique em "Run" para compilar e executar o aplicativo.

## Estrutura do Projeto

- `MainActivity`: Atividade principal que define o conteúdo da UI usando Jetpack Compose.
- `AppBar`: Composable que exibe a barra superior com título e botão de navegação.
- `LunchTrayApp`: Composable que configura a navegação entre as telas do aplicativo.
- `StartOrderScreen`, `EntreeMenuScreen`, `SideDishMenuScreen`, `AccompanimentMenuScreen`, `CheckoutScreen`: Composables que representam as diferentes telas do aplicativo.
- `OrderViewModel`: ViewModel que gerencia o estado da ordem de almoço.

