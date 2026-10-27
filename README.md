# 🎹 PixelBoard Theme Studio (Android Nativo)

Este pacote contém o código-fonte completo do aplicativo e teclado **PixelBoard Theme Studio** para Android (`InputMethodService` nativo + Gerenciador de Temas).

## 🚀 Como gerar o arquivo `.apk` instalável (2 Opções)

### Opção 1: Sem instalar nada no PC (Pelo Celular ou Navegador via GitHub)
O projeto já inclui um robô de compilação automática (`.github/workflows/build-apk.yml`):
1. Crie um repositório gratuito no [GitHub](https://github.com/new).
2. Envie os arquivos desta pasta para o repositório.
3. Clique na aba **Actions** no seu repositório do GitHub.
4. O workflow **Compilar PixelBoard APK** será executado automaticamente e, em cerca de 2 minutos, liberará o download do arquivo **`PixelBoard-Theme-Studio-APK` (`app-debug.apk`)** pronto para instalar no celular!

### Opção 2: Usando o Android Studio (No Computador) ou AndroidIDE (No Celular)
1. Abra a pasta do projeto no **Android Studio** (ou no app **AndroidIDE** diretamente no Android).
2. Aguarde a sincronização automática do Gradle.
3. No menu superior, clique em **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
4. O arquivo `.apk` será gerado em `app/build/outputs/apk/debug/app-debug.apk`.
