# ViralLab Web

Versão web do ViralLab — funciona no celular e em qualquer navegador.

## Como publicar no GitHub Pages

### Passo 1 — Criar repositório
1. Acesse github.com e clique em "+" → "New repository"
2. Nome: `virallab-web`
3. Visibilidade: **Public** (obrigatório para GitHub Pages gratuito)
4. Clique em "Create repository"

### Passo 2 — Subir os arquivos
1. Clique em "uploading an existing file"
2. Arraste os arquivos deste ZIP (index.html + pasta .github)
3. Clique em "Commit changes"

### Passo 3 — Ativar o GitHub Pages
1. No repositório, clique em **Settings**
2. No menu lateral, clique em **Pages**
3. Em "Source", selecione **GitHub Actions**
4. Salve

### Passo 4 — Publicar
1. Vá na aba **Actions**
2. Clique em **Deploy ViralLab Web**
3. Clique em **Run workflow**
4. Aguarde ~1 minuto

Seu site estará em:
**https://SEU-USUARIO.github.io/virallab-web**

## Diferença da versão desktop
- Versão web: abre no browser, funciona no celular
- Versão desktop: instala como .exe no Windows
- Ambas usam a chave de API do próprio usuário
- A chave fica salva no browser (localStorage) — não sai do dispositivo
