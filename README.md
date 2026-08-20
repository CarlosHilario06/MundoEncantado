# Mundo Encantado Avaré — Site

Site institucional (landing page) da Mundo Encantado Avaré — locação de itens para festas e eventos.

Locação e montagem personalizada de festas há 18 anos em Avaré/SP.

## 📁 Estrutura do projeto

```
/
├── index.html          → página principal (todo o site está aqui)
├── assets/              → fotos do catálogo, organizadas por categoria
│   ├── estrutura/       → tendas e ambientes
│   ├── mesas/            → mesas, cadeiras e toalhas
│   ├── loucas/           → pratos, talheres e taças
│   ├── brinquedos/       → brinquedos infláveis e recreação
│   ├── rusticos/         → móveis rústicos
│   ├── portfolio/        → decorações completas
│   └── hero/              → foto de fundo do topo do site
└── logo/                → logo da marca (ícone e versão completa)
```

Não existe nenhuma etapa de build — é um site 100% estático (HTML + CSS + um pouco de JS). Basta abrir o `index.html` ou publicar a pasta inteira em qualquer serviço de hospedagem estática.

## 🚀 Como publicar no GitHub Pages (passo a passo)

1. **Crie um repositório novo no GitHub**
   - Vá em [github.com/new](https://github.com/new)
   - Dê um nome, por exemplo `mundo-encantado-site`
   - Deixe como **público** (necessário para o GitHub Pages gratuito)
   - Não marque nenhuma opção de "adicionar README" (já temos um)

2. **Suba os arquivos**
   - Baixe este projeto (o arquivo `.zip` que te mandei) e descompacte
   - Na página do repositório recém-criado, clique em **"uploading an existing file"**
   - Arraste **todos** os arquivos e pastas (`index.html`, a pasta `assets/`, a pasta `logo/`, o `README.md`) para dentro
   - Clique em **Commit changes** (o botão verde) lá embaixo

3. **Ative o GitHub Pages**
   - No repositório, vá em **Settings** (aba no topo)
   - No menu lateral esquerdo, clique em **Pages**
   - Em **Source**, selecione a branch `main` e a pasta `/ (root)`
   - Clique em **Save**

4. **Pronto!**
   - Espere 1–2 minutos e recarregue a página de **Settings → Pages**
   - Vai aparecer um link tipo:
     `https://seu-usuario.github.io/mundo-encantado-site/`
   - Esse é o link do site no ar — pode compartilhar no Instagram, WhatsApp, onde quiser

## 🌐 Usando o domínio próprio (mundoencantadoavare.com.br)

Se/quando registrar o domínio `www.mundoencantadoavare.com.br`:

1. No repositório do GitHub: **Settings → Pages → Custom domain**, digite o domínio e salve
2. No painel do seu registrador de domínio (Registro.br, por exemplo), crie os seguintes registros DNS:
   - Um registro **CNAME** apontando `www` para `seu-usuario.github.io`
   - Ou registros **A** apontando `@` para os IPs do GitHub Pages (o próprio GitHub mostra esses IPs na tela de configuração acima)
3. Pode levar algumas horas para propagar

## ✏️ Como editar o site depois

- **Trocar texto**: abra o `index.html` em qualquer editor (Notepad, VS Code, ou até o editor de texto do próprio GitHub, clicando no lápis ✏️ ao lado do arquivo) e altere o texto diretamente
- **Trocar telefone/WhatsApp**: procure por `wa.me/55` no `index.html` — os dois números usados são:
  - `5514996840898` (material, decoração, louças)
  - `5514996026467` (tendas e estrutura)
- **Adicionar/trocar fotos**: coloque a nova foto dentro da pasta certa em `assets/` e ajuste o nome do arquivo referenciado no `index.html` (procure pela categoria, ex: `assets/mesas/img_01.jpg`)
- Depois de editar, é só fazer commit direto pelo site do GitHub (ou usar Git localmente) — o GitHub Pages atualiza sozinho em 1–2 minutos

## 📞 Contato usado no site

- **WhatsApp material**: (14) 99684-0898
- **WhatsApp tendas/estrutura**: (14) 99602-6467
- **Instagram**: [@mundoencantadoavare](https://instagram.com/mundoencantadoavare)
- **Endereço**: Rua Antonieta Paulucci, 1132 — Avaré/SP, CEP 18708-320

---

Site desenvolvido com apoio do Claude (Anthropic).
