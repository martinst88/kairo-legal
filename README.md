# Kairo Works — Central Legal

Pacote pronto para publicação em **GitHub Pages** no repositório `kairo-legal`.

## Conteúdo

Este pacote reúne Política de Privacidade e Termos de Uso para:

- Verdade ou Desafio
- PitLane
- Isekai: Neon Armada
- Cupid Love Dice
- Cupid Date Night Challenges
- Lúmina
- Búzios e Cartas
- Vira e Pira

Cada documento está disponível em HTML e Markdown.

## Estrutura

```text
/
├── index.html
├── .nojekyll
├── legal-manifest.json
├── assets/
│   └── legal.css
└── apps/
    └── <app>/
        ├── privacy/
        │   ├── index.html
        │   └── document.md
        └── terms/
            ├── index.html
            └── document.md
```

## Publicar no GitHub Pages

1. Faça upload do conteúdo deste pacote para a raiz do repositório `kairo-legal`.
2. Abra **Settings → Pages**.
3. Em **Build and deployment**, selecione **Deploy from a branch**.
4. Selecione `main` e `/ (root)`.
5. Salve.

A URL padrão ficará no formato:

`https://martinst88.github.io/kairo-legal/`

## Regra operacional importante

A documentação legal precisa permanecer sincronizada com o aplicativo realmente publicado.

Sempre revise a política quando houver mudança em:
- SDKs de anúncios;
- analytics;
- Firebase;
- crash reporting;
- permissões;
- login/conta;
- sincronização em nuvem;
- compras ou assinaturas;
- coleta ou compartilhamento de dados;
- exclusão de dados;
- classificação etária.

## Observação sobre as fontes

Os documentos dos aplicativos já existentes foram consolidados a partir das páginas públicas da Kairo Works indicadas em `SOURCE_AUDIT.md`, com normalização de apresentação e linguagem. O Vira e Pira foi preparado como documento novo.

Antes de substituir documentos oficiais já utilizados no Google Play Console, valide se a configuração técnica de cada versão publicada corresponde ao texto.
