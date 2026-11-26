# TM Pizzaria Android

Projeto Android nativo (WebView) com cardápio, carrinho e finalização de pedido pelo WhatsApp.

## Gerar APK de teste
1. Abra a pasta do projeto no Android Studio (computador) com Android SDK instalado.
2. Aguarde a sincronização do Gradle.
3. Selecione **Build > Build APK(s)**.
4. O APK de teste será criado em `app/build/outputs/apk/debug/app-debug.apk`.

## Compilar na nuvem pelo GitHub Actions
1. Envie todo o conteúdo desta pasta para um repositório GitHub.
2. Abra a aba **Actions** e execute **Build TM Pizzaria APK**.
3. Baixe o artifact `TM-Pizzaria-APK` quando a execução terminar.

Observação: este pacote contém o código-fonte completo, mas não contém um APK já compilado. A compilação requer Android SDK/Gradle, indisponíveis neste ambiente.
