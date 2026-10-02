# LOOK — Moda Feminina

Landing page da LOOK, loja de moda feminina com curadoria própria e atendimento personalizado em Januária, Minas Gerais.

## Publicar na Vercel

1. Importe `lucasvbs/look_modas` na Vercel.
2. Mantenha o **Root Directory** na raiz do repositório (`.`). O projeto usa um workspace pnpm e carrega fotos que ficam fora da pasta do site.
3. A configuração em `vercel.json` já define instalação, build, pasta de saída e fallback para as rotas da página.
4. Clique em **Deploy**. Não são necessárias variáveis de ambiente.

Configuração usada:

- Instalação: `pnpm install --frozen-lockfile`
- Build: `pnpm --filter @workspace/look-moda-feminina run build`
- Saída: `artifacts/look-moda-feminina/dist/public`

O site é estático e não precisa de servidor ou banco de dados para funcionar.