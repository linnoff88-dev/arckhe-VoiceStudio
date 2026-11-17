# VoiceStudio

[![VoiceStudio â€” sua voz local](guia/assets/banner.jpg)](https://inematds.github.io/VoiceStudio/guia/)

**ðŸ‡§ðŸ‡· [PortuguÃªs](README.md) Â· ðŸ‡ºðŸ‡¸ [English](README.en.md) Â· ðŸ‡ªðŸ‡¸ [EspaÃ±ol](README.es.md)**

## O que Ã©

O VoiceStudio Ã© um programa gratuito e de cÃ³digo aberto que faz no seu computador o que serviÃ§os pagos como o ElevenLabs fazem na nuvem. Ele copia uma voz a partir de alguns segundos de gravaÃ§Ã£o, cria vozes novas a partir de uma descriÃ§Ã£o em texto, dubla vÃ­deos e transcreve Ã¡udio em 646 idiomas. Serve para quem produz vÃ­deo, curso, podcast ou audiolivro e quer narraÃ§Ã£o sem pagar por minuto nem enviar o Ã¡udio para fora. Precisa de um computador com uns 10 GB livres; com placa de vÃ­deo NVIDIA fica bem mais rÃ¡pido.

## ðŸ“– Guia de uso

Guia completo (landing + passo a passo): **https://inematds.github.io/VoiceStudio/guia/**

ðŸŽ¬ VÃ­deo: https://www.youtube.com/shorts/RlPeasc5dUw

## Origem e licenÃ§a

Este repositÃ³rio Ã© um **espelho** de [debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio), mantido pelo [INEMA.CLUB](https://inema.club) com o guia em portuguÃªs, inglÃªs e espanhol. Todo o cÃ³digo Ã© do projeto original, sob a licenÃ§a **AGPL-3.0** ([LICENSE](LICENSE), [LICENSE-NOTICE.md](LICENSE-NOTICE.md)). Os modelos de voz tÃªm licenÃ§as prÃ³prias. Clone vozes sÃ³ com permissÃ£o de quem fala.

- README original (inglÃªs): [README.upstream.md](README.upstream.md)
- DocumentaÃ§Ã£o oficial: [docs/](docs/)
- Para instalar a versÃ£o mais recente, prefira o repositÃ³rio original.

## InstalaÃ§Ã£o rÃ¡pida

```sh
# macOS / Linux x86_64
curl -fsSL https://voicestudio.sh/install | sh

# cÃ³digo-fonte (tambÃ©m Linux ARM64)
git clone https://github.com/inematds/VoiceStudio.git
cd VoiceStudio && bun install && bun run setup:api && bun run dev
```

---

Projeto adaptado da comunidade INEMA TDS - Marca Arckhe