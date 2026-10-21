---
title: "Lição 12 - Publique o site com o GitHub Pages"
description: "Use o aplicativo GitHub Copilot para configurar um fluxo de trabalho do Pages, revisar o pull request e verificar se o Space Quiz está no ar."
authors:
  - jamesmontemagno
lastUpdated: 2026-10-12
---

Publique o Space Quiz no GitHub Pages para que todos possam acessá-lo. O Copilot pode preparar o fluxo de trabalho e orientar a publicação, mas você é responsável por revisar as alterações e confirmar que o site está no ar.

Nesta lição, você vai:

- pedir ao Copilot para configurar a publicação no GitHub Pages.
- revisar o fluxo de trabalho e o pull request antes de mesclá-lo.
- acompanhar a publicação e verificar o site publicado.

## Cenário

O Space Quiz já está em um repositório do GitHub, mas ainda precisa de uma maneira simples para que outras pessoas possam experimentá-lo. Publicar o site de um único arquivo com o GitHub Pages o disponibiliza em uma URL pública, sem adicionar um servidor ou uma dependência de runtime.

## Peça ao Copilot para publicar o site

Na sessão do aplicativo Copilot para `space-quiz`, envie este prompt:

```plaintext
Enable GitHub Pages for this repository. Create a GitHub Actions workflow that builds the website if needed and deploys it to GitHub Pages. Add a README describing the app and how to run it locally if one does not already exist. Create a pull request with these changes and merge it after required checks pass. Monitor the deployment until it succeeds, then report the final URL of the live website. If you lack permission to enable Pages or merge, tell me exactly what I need to approve or do; do not report success until the site is live.
```

![Diagrama em três etapas: um pull request de space-quiz mesclado; uma execução bem-sucedida de Deploy website no GitHub Actions com as etapas Build website, Upload artifact e Deploy to Pages; e o Space Quiz publicado em yourname.github.io/space-quiz/.](../../../_images/first-steps-app-pages-deploy.svg)

> [!WARNING]
> Este prompt pede ao agente para criar e mesclar um pull request e alterar as configurações do Pages no repositório. Antes de continuar, revise o diff, as permissões de publicação e todas as solicitações de aprovação do GitHub.

## Revise o fluxo de trabalho e verifique a publicação

1. Confirme que o README só será adicionado se o repositório ainda não tiver um.
2. Revise as alterações do pull request, incluindo as etapas de build e publicação do fluxo de trabalho.
3. Mescle o pull request somente depois que as verificações obrigatórias forem aprovadas.
4. Acompanhe a execução de publicação do GitHub Actions até ela ser concluída com sucesso.
5. Abra a URL informada e confirme que o Space Quiz é carregado.

Se o agente não puder habilitar o Pages ou mesclar o pull request, siga as instruções específicas fornecidas. Não considere a tarefa concluída até que a publicação seja bem-sucedida e o site esteja no ar.

## Resumo e próximos passos

O Space Quiz agora está disponível como um site publicado, e você verificou a publicação em vez de depender do relato do agente. Continue para a [Lição 13: revisão e próximos passos][next-lesson].

[next-lesson]: ../13-review/
