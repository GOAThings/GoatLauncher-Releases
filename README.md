# GoatLauncher: versões

APKs do **GoatLauncher**, um ecrã inicial para Android TV (feito para a NVIDIA SHIELD).

## Instalar

Na app **Downloader**, escreve o código **3400411** (ou abre `aftv.news/3400411`).
Instala sempre a versão mais recente.

Link direto: https://github.com/iamSlokker/GoatLauncher-releases/releases/latest/download/goatlauncher.apk

Para o pôr como ecrã inicial, por adb:

```
adb shell cmd package set-home-activity cc.slokker.goatlauncher/.MainActivity
```

Depois de instalado, o launcher procura versões novas sozinho (Definições → Atualizações).
