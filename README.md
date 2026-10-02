# Kolibri Print

Canal oficial de distribuição do **Kolibri Print** para Windows.

Este repositório público contém apenas instaladores, notas de versão e hashes de integridade. O código-fonte do produto é mantido separadamente em repositório privado.

## Download

Use sempre a seção **Releases** deste repositório para baixar a versão publicada mais recente.

> A versão em desenvolvimento não é disponibilizada aqui. Uma versão só é publicada após passar pelo gate de homologação correspondente.

## Instalação

1. Abra a versão desejada em **Releases**.
2. Baixe `KolibriPrint_Setup_vX.Y.Z.exe`.
3. Confira o SHA-256 publicado junto da versão.
4. Execute o instalador no Windows e escolha a função necessária: Agent, Bridge ou ambos.

## Componentes

- **Kolibri Print Agent** — disponibiliza impressoras do computador host.
- **Kolibri Print Bridge** — conecta o computador cliente ao Agent e cria filas de impressão no Windows.
- **Kolibri Print Forwarder** — encaminhador local usado pela impressão universal autenticada.

## Compatibilidade

O alvo prático do produto é Windows 10/11 x64. A compatibilidade de cada release é descrita nas notas da própria versão.

## Segurança

Baixe instaladores somente deste repositório oficial. Compare o SHA-256 do arquivo baixado com o hash publicado na mesma Release.

## Licença e código-fonte

O Kolibri Print é software proprietário. Este repositório é destinado exclusivamente à distribuição de builds oficiais e documentação pública de release.
