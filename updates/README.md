# Kolibri Print — Manifestos de atualização

Esta pasta é o canal público consumido pelo mecanismo de atualização segura do Kolibri Print.

Arquivos previstos:

- `stable.json` — versão estável atualmente oferecida aos clientes;
- `beta.json` — versão beta disponível somente para instalações que escolheram o canal beta.

Os manifestos não são fonte de confiança por si só. O aplicativo só aceita um manifesto quando:

1. a assinatura ECDSA P-256 é válida para a chave pública embutida no build;
2. o canal corresponde ao canal selecionado;
3. a URL do instalador usa HTTPS;
4. tamanho e SHA-256 do instalador correspondem aos valores assinados.

Um manifesto novo só deve ser publicado depois que o respectivo instalador existir em **Releases** e tiver passado pelo gate de homologação correspondente.

A chave privada usada para assinar manifestos não é armazenada neste repositório.
