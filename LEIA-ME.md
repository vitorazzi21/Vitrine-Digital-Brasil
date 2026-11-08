# Vitrine Digital Brasil: site institucional

Página de apresentação da Vitrine Digital Brasil, sem produtos. Ela explica o que é a Vitrine,
por que foi criada, o significado do nome, por que é segura e quais são os canais oficiais.
É um site estático (HTML + CSS) e funciona no GitHub Pages.

## Estrutura

```
index.html      → todos os textos do site
css/style.css   → visual (cores no topo do arquivo)
img/            → (crie) coloque aqui a imagem capa.jpg para o Facebook
```

## 1. Personalizar

No `index.html`, procure a seção **CONTATO** e troque os links de exemplo:
- `https://facebook.com/suapagina`
- `https://instagram.com/seuperfil`
- `https://wa.me/5511999998888` (55 + DDD + número, só dígitos)
- `contato@seudominio.com`

Para esconder um canal, apague o bloco `<a class="contato ...">...</a>` inteiro.

Para mudar as cores, edite `--verde`, `--amarelo` e `--azul` no começo de `css/style.css`.

## 2. Publicar no GitHub Pages

1. Em https://github.com, clique em **New repository**, dê um nome (ex: `vitrine`) e marque **Public**.
2. Clique em **Add file → Upload files**, arraste o `index.html` e a pasta `css`
   (e a pasta `img`, se tiver). Clique em **Commit changes**.
3. Vá em **Settings → Pages**. Em *Branch*, escolha `main` e `/ (root)`. Salve.
4. Em 1 ou 2 minutos o site estará em `https://SEU-USUARIO.github.io/vitrine/`

## 3. Ligar à página do Facebook

- **Botão da página:** Página do Facebook → *Adicionar botão* → *Saiba mais* → cole o link.
- **Site da página:** *Editar informações* → campo *Site* → cole o link.

### Prévia do link no Facebook
No `index.html`, troque `SEU-USUARIO` e `SEU-REPOSITORIO` nas linhas `og:image` e `og:url`
e envie uma imagem `img/capa.jpg` (ideal 1200×630). Depois use o
[Depurador de compartilhamento](https://developers.facebook.com/tools/debug/) para atualizar a prévia.
