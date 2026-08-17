# Ultra Portaria — downloads

Este repositório **não tem código**. Ele guarda apenas os arquivos que o
aplicativo Android **Ultra Portaria** publica a cada versão:

| Arquivo | Para que serve |
|---|---|
| `ultra-portaria.apk` | o aplicativo |
| `ultra-portaria.apk.sha256` | a soma de verificação do APK |
| `manifest.json` | o que o app lê para saber se há versão nova |

## Baixar o app

**[Última versão publicada](../../releases/latest)** → baixe `ultra-portaria.apk`.

No celular, toque no arquivo baixado. Quando o Android avisar, permita
**instalar apps desconhecidos** para o navegador — a permissão é por aplicativo,
não para o aparelho inteiro.

Instalar por cima da versão anterior **mantém os dados do app**, inclusive a fila
offline. Não desinstale.

## Por que existe separado

O código do aplicativo é privado, e um Release de repositório privado exige login
para baixar — o celular na porta de um evento não tem como fazer isso. Este
repositório é público só para que o download funcione; nenhuma linha de código
fonte é publicada aqui.

Os arquivos são enviados automaticamente pelo build a cada versão. Não edite nada
à mão: o `manifest.json` precisa concordar com o APK que está ao lado dele.
