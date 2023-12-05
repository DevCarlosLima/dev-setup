<h1 align="center">💻🖥️ Meu Setup ⌨️🖱️</h1>
<div align="center">

![Build Status](https://img.shields.io/static/v1.svg?label=setup-dev&message=v1.0.0&color=blue&style=flat&logo=circleci&logoColor=white)

<i>Aqui são as linguagens de programação que mais utilizo no github</i>   

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=DevCarlosLima&langs_count=3)](https://github.com/anuraghazra/github-readme-stats)
</div>

> Este é um modelo de setup para desenvolvimento. As principais ferramentas que utilizo na caminhada de desenvolvedor fullstack.

<div align="center">
  
|<img src="https://cdn-icons-png.flaticon.com/512/5968/5968322.png" width="70" heigth="70"/>|<img src="https://docs.microsoft.com/pt-br/dotnet/images/hub/netcore.svg" width="70" heigth="70" />|<img src="https://cdn.freebiesupply.com/logos/large/2x/angular-icon-1-logo-png-transparent.png" width="70" heigth="70" />|<img src="https://mhartington.io/img/v4-upgrade/ionic-icon.png" width="70" heigth="70" />|<img src="https://brandslogos.com/wp-content/uploads/thumbs/java-logo-vector-1.svg" width="70" heigth="70" />|<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/2048px-Visual_Studio_Code_1.35_icon.svg.png" width="70" heigth="70"/>|<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c1/Android_Studio_icon_%282023%29.svg/2048px-Android_Studio_icon_%282023%29.svg.png" width="70" heigth="70"/>|<img src="https://user-images.githubusercontent.com/17512287/46575879-3847d100-c9be-11e8-97dc-1d95d880c187.png" width="70" heigth="70" />|
|-|-|-|-|-|-|-|-|
|*v20.10.0*|*v2.2.100*|*v15.2.9*|*v6.20.9*|*v17.0.9 (JDK)*|*LTS*|*LTS*|*LTS*|
|[Download](https://nodejs.org/dist/v20.10.0/)|[Download](https://dotnet.microsoft.com/pt-br/download/dotnet/thank-you/sdk-2.2.100-windows-x64-installer)|[Install](#angular)|[Install](#ionic)|[Download](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)|[Download](https://code.visualstudio.com/)|*[Download](https://developer.android.com/studio)*|[Download](https://learn.microsoft.com/pt-br/azure-data-studio/download-azure-data-studio?tabs=win-install%2Cwin-user-install%2Credhat-install%2Cwindows-uninstall%2Credhat-uninstall#download-azure-data-studio)|

</div>

# Angular
    npm i -g @angular/cli@15.2.9

# Ionic
    npm install -g @ionic/cli@6.20.9

`capacitor.config.ts`
``` typescript
import { CapacitorConfig } from '@capacitor/cli';

const config: CapacitorConfig = {
  plugins: {
    SplashScreen: {
      launchShowDuration: 2000,
      launchAutoHide: false,
      launchFadeOutDuration: 400,
      backgroundColor: "#ffffffff",
      androidSplashResourceName: "splash",
      androidScaleType: "CENTER_CROP",
      showSpinner: true,
      androidSpinnerStyle: "large",
      iosSpinnerStyle: "small",
      spinnerColor: "#999999",
      splashFullScreen: true,
      splashImmersive: true,
      layoutName: "launch_screen",
      useDialog: true,
    },
  },
};
```
