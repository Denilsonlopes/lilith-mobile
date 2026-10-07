# Lilith Mobile v0.2

Evolução da v0.1 com aprendizado por relações e comunicação por voz.

## Exemplo
Ensine: `Quando eu disser bom dia, responda Bom dia.`
Depois diga `bom dia`. A Lilith deve responder `Bom dia.`

## Voz
- 🎙️ você fala e o navegador tenta transformar sua fala em texto;
- 🔊 Lilith fala as respostas usando SpeechSynthesis;
- no iPhone, permita o microfone quando solicitado.

O reconhecimento de fala via Web Speech API tem compatibilidade mais limitada que a síntese; Safari iOS oferece reconhecimento na web, mas permissões/configurações do aparelho podem afetar o funcionamento.
