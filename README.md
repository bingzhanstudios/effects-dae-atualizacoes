<!-- Substitua docs/hero.png por uma imagem de capa da suíte (1280×640 recomendado). -->
<p align="center">
  <img src="docs/hero.png" alt="Safelayer Creatives" width="100%">
</p>
<h1 align="center">Safelayer Creatives</h1>
 
<p align="center">
  Suíte open-source de criação para designers, editores de vídeo e criativos.
</p>
<p align="center">
  <a href="https://github.com/myangdae/effects-dae-atualizacoes/releases/latest"><img alt="Última versão" src="https://img.shields.io/github/v/release/myangdae/effects-dae-atualizacoes?label=vers%C3%A3o&style=flat-square"></a>
  <a href="https://github.com/myangdae/effects-dae-atualizacoes/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/myangdae/effects-dae-atualizacoes/total?label=downloads&style=flat-square"></a>
  <img alt="Plataformas" src="https://img.shields.io/badge/plataformas-Windows%20%7C%20Linux-informational?style=flat-square">
</p>
<p align="center">
  <a href="#download">Download</a> ·
  <a href="https://github.com/myangdae/effects-dae-atualizacoes/releases">Notas de versão</a> ·
  <a href="#atualizações">Atualizações</a> ·
  <a href="#suporte">Suporte</a>
</p>
---
 
## Sobre
 
A **Safelayer Creatives** reúne, em um único instalador, as ferramentas de que um criativo precisa no dia a dia: edição de vídeo, edição de imagem e gestão de identidade visual de clientes.
 
| App | Para quê |
|---|---|
| **Safelayer Cut** | Editor de vídeo com timeline, pré-visualização destacável e exportação. Presets prontos para Reels/TikTok, YouTube, Post e Feed. |
| **Safelayer Stroke** | Editor de imagem. |
| **Safelayer Mark** | Brand kit: guarda logo, cores, fontes, tagline, site e @ de cada cliente e preenche templates e mockups automaticamente. |
 
> **Sobre este repositório:** aqui ficam apenas os **builds publicados** (instaladores e notas de versão). <!-- Se o código-fonte estiver público, troque esta frase por: "O código-fonte está em [link]." -->
 
## Download
 
Baixe a versão mais recente na página de **[Releases](https://github.com/myangdae/effects-dae-atualizacoes/releases/latest)** e abra **Assets** para ver os arquivos.
 
| Sistema | Arquivo | Indicado para |
|---|---|---|
| Windows | `effects-dae-<versão>-instalador.exe` | **Recomendado.** Instala os apps no menu Iniciar e se atualiza sozinho. |
| Windows | `effects-dae-<versão>-portatil.exe` | Rodar sem instalar (pendrive, máquina sem permissão de administrador). Avisa quando há versão nova. |
| Linux | `*.AppImage` | Qualquer distribuição. Dê permissão de execução e abra. |
 
```bash
# Linux
chmod +x Safelayer*.AppImage
./Safelayer*.AppImage
```
 
### Requisitos
 
<!-- Confirme os requisitos com a equipe antes de publicar. -->
- Windows 10 ou 11 (64 bits), ou distribuição Linux 64 bits
- Placa de vídeo com suporte a aceleração por hardware (recomendado para o Safelayer Cut)
## Atualizações
 
A versão instalada procura atualizações **ao abrir e a cada 6 horas**, baixa o pacote em segundo plano e avisa quando a atualização está pronta para aplicar. Não é preciso baixar o instalador de novo.
 
A versão portátil não se atualiza sozinha: ela avisa que há uma versão nova e leva você à página de download.
 
### Verificar a integridade do download
 
Cada release lista o hash **SHA-256** de seus arquivos. Para conferir no Windows:
 
```powershell
Get-FileHash .\effects-dae-<versão>-instalador.exe -Algorithm SHA256
```
 
O resultado deve ser idêntico ao publicado na release.
 
## Notas de versão
 
O histórico completo de mudanças fica em **[Releases](https://github.com/myangdae/effects-dae-atualizacoes/releases)**. Cada versão traz as novidades, as correções e os problemas conhecidos.
 
## Suporte
 
- **Encontrou um bug?** Abra uma [issue](https://github.com/myangdae/effects-dae-atualizacoes/issues) informando a versão, o sistema operacional e os passos para reproduzir.
- **Tem uma sugestão?** Use as issues também, com o rótulo `sugestão`.
- **Falha de segurança?** Não abra issue pública. Escreva para `<e-mail de segurança>`.
## Créditos
 
Desenvolvido por **[Bingzhan Studio®](#)** em parceria com **[Safelayer Creatives](#)** e **AURE Lab**.
 
## Licença
 
<!-- Informe a licença do projeto (ex.: MIT, GPL-3.0) e adicione o arquivo LICENSE na raiz. -->
Distribuído sob a licença `<licença>`. Veja [LICENSE](LICENSE).
