# GoatLauncher: versões

APKs do **GoatLauncher**, um ecrã inicial para Android TV (feito para a NVIDIA SHIELD).

Para instalar: descarrega o `.apk` do release mais recente (por exemplo com a app *Downloader*) e abre-o.
Para o pôr como ecrã inicial, por adb:

```
adb shell cmd package set-home-activity cc.slokker.goatlauncher/.MainActivity
```
