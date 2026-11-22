# Guia de contribuição do safelayer editor

Se você usar IA para escrever um relato ou comentar neste repositório, leia a seção [Uso de IA](#uso-de-ia).

Abaixo está como reportar problemas, sugerir funções e ajudar com textos e traduções.

> [!NOTE]
> O código-fonte do safelayer editor não é aberto, então **não recebemos pull requests de código**. Você contribui com relatos, sugestões e traduções, e isso decide boa parte do que entra em cada versão.

## Trabalhamos às claras

A equipe acompanha este repositório de perto. Quando achamos um bug, abrimos uma issue aqui. Quando temos uma ideia nova, ela vira uma sugestão aqui. Quando uma correção sai, ela aparece nas [notas de versão](https://github.com/bingzhanstudios/effects-dae-atualizacoes/releases) e avisamos na issue.

Fazemos assim para que você veja que os relatos da comunidade passam pelo mesmo processo que os nossos, e para que fique registrado o "porquê" das coisas: quem chega depois entende por que o app funciona do jeito que funciona.

### Triagem e rótulos

Lemos todas as issues novas e usamos rótulos para organizar:

| Rótulo | Quer dizer |
|---|---|
| `bug` | Algo que já existe e não funciona do jeito certo |
| `sugestão` | Uma função nova ou uma melhoria |
| `texto` | Erro de escrita, tradução estranha ou texto faltando |
| `precisa de informação` | Precisamos de mais detalhes de quem abriu |
| `planejado` | Entrou nos planos de uma próxima versão |
| `corrigido` | Já saiu numa versão; diga se continua acontecendo |

Fique de olho nas notificações do GitHub: se pedirmos mais informação e não tiver resposta em **14 dias**, podemos fechar a issue. Dá para reabrir quando quiser.

---

## Reportar falha de segurança

**Não reporte falhas de segurança em issues públicas.** Veja como reportar em particular no [SECURITY.md](SECURITY.md).

## Antes de tudo, abra uma issue

Uma regra simples para ninguém perder tempo, nem você, nem nós:

> 👉 Tem uma dúvida, achou um problema ou quer propor uma função? **Procure ou abra uma issue ANTES.**

### Procure primeiro

Antes de abrir, procure nas issues **abertas e fechadas**: o app muda rápido, e é bem provável que alguém já tenha visto o mesmo problema, ou que ele já esteja corrigido na versão mais nova.

Se nada descreve o seu caso, ótimo: abra uma issue nova.

### Abra uma issue nova

- Não sabe se é bug ou sugestão? Abra uma issue.
- Tem uma dúvida que não está respondida no [README](README.md) nem nas notas de versão? Abra uma issue.
- Quer saber se pensamos em fazer uma função? Abra uma issue.
- Teve uma ótima ideia? Abra uma sugestão.
- Achou uma issue igual à sua? Ótimo: reaja com 👍 e acrescente o que for novo (passos, prints, versão).

Ao clicar em **[New issue](https://github.com/bingzhanstudios/effects-dae-atualizacoes/issues/new/choose)**, escolha o tipo mais perto do que você quer:

| Tipo | Para quê |
|---|---|
| **Relato de bug** 🐛 | Erros ou comportamento inesperado |
| **Sugestão** 🚀 | Uma função nova ou uma melhoria (sugerir não obriga ninguém a fazer) |
| **Texto ou tradução** 📝 | Erro de escrita, tradução estranha ou texto faltando em português, inglês ou espanhol |

### Preencha o modelo

**Preencha o que o modelo pede, com o máximo de detalhes.** Quanto mais informação, maior a chance de entendermos e resolvermos. Ajuda muito:

- **A versão do safelayer editor:** em **Configurações → Sobre**.
- **Instalador ou portátil.**
- **O computador:** processador, memória e placa de vídeo (no Windows: **Configurações → Sistema → Sobre**).
- **A versão do Windows.**

  > 👉 Dica: aperte **Win+R**, digite `winver` e Enter. Ou rode no Prompt de Comando:

  ```bat
  C:\> ver

  Microsoft Windows [versão 10.0.26100.2314]
  ```

  > … ou no PowerShell:

  ```powershell
  PS C:\> [System.Environment]::OSVersion.Version

  Major  Minor  Build  Revision
  -----  -----  -----  --------
  10     0      26100  0
  ```

- **O arquivo que você estava usando**, quando der: o formato (MP4, MOV, PNG, SVG…), a resolução e a duração.
- **Adoramos passo a passo detalhado!** Que passos fazem o problema acontecer? Pode caprichar: o máximo de detalhe que você aguentar escrever provavelmente é *quase* o suficiente para nós.
- **Prefira o texto da mensagem de erro** (copie e cole); print só quando não der para copiar.
- **Para problema de exportação**, diga o formato, o codec e o tamanho escolhidos na janela de Exportar.

### NÃO comente "+1"

> ⚠️ **Não comente "+1", "comigo também" ou parecidos:** eles só fazem barulho na issue.

Se você não tem nada novo para acrescentar mas é afetado pelo problema, reaja à issue original com o botão **[😊]** e escolha 👍. Assim conseguimos medir quantas pessoas cada problema atinge.

---

## Como organizamos as issues

- **Bugs** são partes do app que existem mas não funcionam direito. Corrigir é achar onde quebra e consertar.
- **Sugestões pequenas** cabem numa versão só e não pedem muita discussão de design.
- **Sugestões grandes** mexem em várias telas ou criam configurações novas. Nelas, antes de construir, escrevemos uma especificação: como vai funcionar, o que muda para quem usa e o que acontece se algo der errado. Comentários de quem usa nessa fase valem ouro.

## Textos e traduções

O app está em português, inglês e espanhol. Viu um texto estranho, cortado ou faltando? Abra uma issue **Texto ou tradução** com o print da tela, o texto que está lá e o texto que você sugere.

## Uso de IA

Pode usar IA para ajudar a escrever um relato, desde que:

- você **confira que é verdade**: os passos, a versão e a mensagem de erro têm que ser os que aconteceram com você;
- o relato continue **curto e direto** (texto gerado costuma inflar);
- você **diga** quando um trecho grande foi escrito por IA.

Relatos inventados ou que não dão para reproduzir podem ser fechados.

---

## Obrigado

Obrigado desde já pela ajuda! Cada relato bem feito vira uma versão melhor. Agora, que tal ver o [que mudou na última versão](https://github.com/bingzhanstudios/effects-dae-atualizacoes/releases/latest)? 😄

Ao participar, você concorda com o nosso [Código de conduta](CODE_OF_CONDUCT.md).
