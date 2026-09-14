# Portfólio Rafael Palmeira

Portfólio responsivo em React e Vite, inspirado na estrutura e no ritmo visual do Bright TSA e adaptado para o conteúdo de Rafael Palmeira.

## Executar localmente

```bash
npm install
npm run dev
```

## Gerar a versão de produção

```bash
npm run build
npm run test:sites
```

## Atualizar conteúdo

As informações pessoais, os projetos, os filtros e a trajetória ficam em `src/content.js`.

As imagens ficam em `public/assets`.

Os componentes e as interações ficam em `src/App.jsx`.

Os ajustes visuais próprios ficam em `src/styles.css`. O arquivo `src/reference.css` concentra a base visual usada para manter a proximidade com a referência.

## Páginas

• `/` apresenta o perfil e o carrossel de projetos no desktop. No mobile, os projetos aparecem em sequência vertical.

• `/work/` reúne os filtros e a grade completa de projetos.

• `/about/` apresenta a visão de design, o retrato, as disciplinas e a trajetória profissional.
