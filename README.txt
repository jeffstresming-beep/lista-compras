═══════════════════════════════════════════════════════
  🛒 LISTA DE COMPRAS — GUIA DE INSTALAÇÃO NO ANDROID
═══════════════════════════════════════════════════════

MÉTODO: GitHub Pages (gratuito) → PWABuilder → APK

───────────────────────────────────────────────────────
PASSO 1 — CRIAR CONTA NO GITHUB (se ainda não tiver)
───────────────────────────────────────────────────────
1. Acesse: https://github.com
2. Clique em "Sign up" e crie uma conta gratuita

───────────────────────────────────────────────────────
PASSO 2 — CRIAR REPOSITÓRIO E SUBIR OS ARQUIVOS
───────────────────────────────────────────────────────
1. No GitHub, clique em "+" > "New repository"
2. Nome: lista-compras  (sem espaços)
3. Marque "Public"
4. Clique em "Create repository"
5. Clique em "uploading an existing file"
6. Arraste TODOS os arquivos desta pasta:
     • index.html
     • manifest.json
     • sw.js
     • icon-192.png
     • icon-512.png
7. Clique em "Commit changes"

───────────────────────────────────────────────────────
PASSO 3 — ATIVAR GITHUB PAGES
───────────────────────────────────────────────────────
1. No repositório, clique em "Settings"
2. Menu lateral: "Pages"
3. Em "Source", selecione "Deploy from a branch"
4. Branch: main  |  Pasta: / (root)
5. Clique em "Save"
6. Aguarde ~2 minutos
7. Sua URL será: https://SEU_USUARIO.github.io/lista-compras/

   ✅ Teste a URL no navegador antes de continuar!

───────────────────────────────────────────────────────
PASSO 4 — GERAR O APK NO PWABUILDER
───────────────────────────────────────────────────────
1. Acesse: https://www.pwabuilder.com
2. Cole sua URL do GitHub Pages na caixa de busca
3. Clique em "Start"
4. O site vai validar sua PWA (todos os itens devem ficar verdes)
5. Clique em "Package for Stores"
6. Escolha "Android"
7. Clique em "Generate Package"
8. Baixe o arquivo .apk gerado

───────────────────────────────────────────────────────
PASSO 5 — INSTALAR O APK NO ANDROID
───────────────────────────────────────────────────────
1. Transfira o .apk para o celular (WhatsApp, cabo USB, e-mail, etc.)
2. Abra o arquivo no celular
3. Se aparecer aviso de segurança:
   Configurações > Apps > Instalar apps desconhecidos > permitir
4. Conclua a instalação
5. O app aparece na tela inicial com ícone verde 🛒

───────────────────────────────────────────────────────
ALTERNATIVA RÁPIDA — INSTALAR COMO PWA SEM APK
───────────────────────────────────────────────────────
Mais simples: apenas abra a URL do GitHub Pages no
Chrome do Android e toque em:
  Menu (⋮) > "Adicionar à tela inicial"

O app é instalado com ícone e funciona offline —
sem precisar gerar APK!

───────────────────────────────────────────────────────
DÚVIDAS?
───────────────────────────────────────────────────────
• GitHub Pages: https://pages.github.com
• PWABuilder:   https://www.pwabuilder.com/blog/pwabuilder-and-android

═══════════════════════════════════════════════════════
