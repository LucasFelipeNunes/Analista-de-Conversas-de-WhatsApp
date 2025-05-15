# 📄 Analista de Conversas do WhatsApp

Olá! Este programa tem como objetivo analisar estatísticas detalhadas de uma conversa exportada (sem mídias) do WhatsApp, tendo sido desenvolvido em Python na plataforma do Google Colab. A análise inclui aspectos como volume de mensagens, distribuição temporal, uso de palavras, emojis, mídias e outros indicadores de comportamento dos participantes.

Para utilizar este programa, você pode abrir este código com o botão no canto superior esquerdo e salvá-lo no seu Drive, e, na mesma pasta em que você salvar o programa, salvar o arquivo em txt da conversa exportada do WhatsApp, com o nome `conversa.txt`.

## 📥 Entrada

O programa espera um arquivo de texto no formato padrão de exportação do WhatsApp (sem mídia), em que cada linha segue o formato:

```
dd/mm/aaaa hh:mm - Nome: Mensagem
```

Exemplo:

```
20/04/2024 14:53 - João: Olá, tudo bem?
```

## 📤 Saída

Os resultados são exibidos diretamente no console, organizados em seções com listagens ordenadas de acordo com a frequência ou volume.
