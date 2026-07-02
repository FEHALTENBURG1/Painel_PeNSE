# Painel PeNSE 2024 — Tabagismo entre escolares (13–17 anos)

Visualizador interativo das tabelas do capítulo 5 (uso de produtos do tabaco) da
Pesquisa Nacional de Saúde do Escolar 2024 (IBGE), com estimativas e intervalos
de confiança de 95%.

**Recursos**
- 14 indicadores (Tabelas 5.1 a 5.13, incluindo 5.10a), navegáveis na barra lateral
- Três recortes geográficos: Grandes Regiões, Unidades da Federação e Capitais
- Séries comparáveis: Total, sexo (Homem/Mulher) e dependência administrativa (Pública/Privada) — ou categorias de resposta (Tabelas 5.4 e 5.10)
- Gráfico de ponto + IC95%, tabela de dados e mapa coroplético das UFs
- Arquivo único e autocontido (dados e geometrias embutidos) — funciona offline

## Publicar no GitHub Pages

1. Crie um repositório novo (ex.: `pense2024-tabagismo`)
2. Envie o `index.html` (e este README) para a branch `main`:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Painel PeNSE 2024 - tabagismo"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/pense2024-tabagismo.git
   git push -u origin main
   ```
3. No repositório: **Settings → Pages → Source: Deploy from a branch → Branch: main / (root) → Save**
4. Em ~1 minuto o painel estará em `https://SEU_USUARIO.github.io/pense2024-tabagismo/`

Não há build, dependência ou requisição externa — qualquer hospedagem estática serve
(GitHub Pages, Netlify, servidor institucional).

**Fonte dos dados:** IBGE, Diretoria de Pesquisas, Coordenação de População e
Indicadores Sociais, Pesquisa Nacional de Saúde do Escolar 2024.

**Elaboração:** 
Fernanda Haltenburg · Sala de Situação em Saúde · Faculdade de Saúde, Universidade de
Brasília (FS-UnB) · Residência Multiprofissional em Vigilância em Saúde
