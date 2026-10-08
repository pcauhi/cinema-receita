# 🎬 Cinema Receita

**1 selfie + 1 receita = 1 vídeo cinematográfico com a sua cara cozinhando.**

Skill para o Claude que transforma suas fotos e qualquer receita em um prompt pronto para o
Seedance 2.5. Você cola o prompt, envia suas fotos e recebe um vídeo vertical de 15 s pronto
para Reels e TikTok.

Criado por [@cauhi](https://www.instagram.com/cauhi) · [cauhi.com](https://cauhi.com)

---

## O que você precisa

- Uma conta no **Claude** (claude.ai ou Claude Code)
- Uma conta em uma plataforma com **Seedance 2.5** (ex.: Higgsfield)
- **2 fotos suas**: rosto nítido, boa luz, boca fechada (uma de frente e uma levemente de lado é o ideal)
- **Uma receita** (link ou texto)

## Como instalar

**No claude.ai (mais fácil)**
1. Baixe este repositório (botão verde **Code → Download ZIP**).
2. No Claude, vá em **Configurações → Capacidades → Skills** e envie o `.zip`.
3. Abra um chat novo.

**No Claude Code**
```bash
git clone https://github.com/pcauhi/cinema-receita ~/.claude/skills/cinema-receita
```

## Como usar

No chat, envie suas fotos e escreva:

> Usa o cinema-receita para transformar essa receita em vídeo: [link ou texto da receita]

O Claude devolve um prompt em inglês. Depois:

1. No Seedance 2.5, escolha o modo de **referência de imagem**.
2. Envie as mesmas fotos (na mesma ordem).
3. Cole o prompt. Formato **9:16**, **15 s**, áudio ligado.
4. **Gere primeiro um rascunho barato (480p)**. Ficou bom? Aí finalize em alta qualidade.

## Dicas

- Prefira receitas com **ação**: carne na chapa, massa sendo esticada, fritura, fogo.
- Se o rosto não ficar parecido, envie mais uma foto com luz natural e gere de novo.
- O vídeo sai **sem fala e sem música**: coloque legenda e trilha na edição.

Veja um exemplo real em [`exemplos/picanha.md`](exemplos/picanha.md).

## Custos

A skill é grátis. Gerar o vídeo não: o Seedance 2.5 roda em plataformas pagas (ex.: Higgsfield, por créditos).
Faça sempre o rascunho barato antes de finalizar.

## Licença

[MIT](LICENSE): use, modifique e compartilhe à vontade, mantendo o crédito.
