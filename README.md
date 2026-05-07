# Acadêmico — Guia de Deploy

## Estrutura do projeto

```
academico-project/
├── index.html          ← o site principal
├── resumos/            ← pasta para guardar os resumos HTML
│   └── unit14_banking.html
└── README.md           ← este guia
```

---

## Passo 1 — Criar conta no GitHub

1. Acesse **github.com** e clique em **Sign up**
2. Use seu e-mail, crie uma senha e confirme
3. Escolha o plano **Free**

---

## Passo 2 — Criar o repositório

1. No GitHub, clique no **+** no canto superior direito → **New repository**
2. Nome do repositório: `academico`
3. Deixe marcado como **Public**
4. Clique em **Create repository**

---

## Passo 3 — Fazer upload dos arquivos

Na página do repositório vazio que apareceu:

1. Clique em **uploading an existing file**
2. Arraste a pasta `academico-project` inteira (ou os arquivos um por um)
3. No campo de mensagem escreva: `primeiro upload`
4. Clique em **Commit changes**

---

## Passo 4 — Criar conta no Vercel

1. Acesse **vercel.com**
2. Clique em **Sign Up**
3. Escolha **Continue with GitHub** — isso conecta os dois automaticamente

---

## Passo 5 — Publicar o site

1. No Vercel, clique em **Add New → Project**
2. Selecione o repositório `academico` que aparece na lista
3. Clique em **Deploy** (não precisa mudar nada)
4. Aguarde ~30 segundos

Pronto! O Vercel vai te dar um link tipo:
**`https://academico-xxxx.vercel.app`**

Mande esse link para as suas amigas testarem!

---

## Como atualizar o site depois

Sempre que quiser atualizar o site:

1. Vá no repositório no GitHub
2. Clique no arquivo que quer atualizar (ex: `index.html`)
3. Clique no ícone de lápis ✏️ (Edit)
4. Faça as alterações
5. Clique em **Commit changes**

O Vercel detecta automaticamente e atualiza o site em ~30 segundos para todo mundo.

---

## Como adicionar novos resumos HTML

1. Peça ao Claude para gerar o resumo em HTML
2. Baixe o arquivo `.html`
3. Faça upload para a pasta `resumos/` no GitHub
4. No site, vá em **Resumos → ✦ Importar HTML** e selecione o arquivo

---

## Domínio próprio (futuro)

Quando quiser um endereço tipo `academico.com.br`:

1. Compre o domínio na **Hostinger** (~R$40/ano para .com.br)
2. No Vercel, vá em **Settings → Domains**
3. Adicione seu domínio e siga as instruções

---

## Próximos passos para monetizar

Quando quiser cobrar pelo acesso:

1. **Supabase** (gratuito) — para criar sistema de login
2. **Mercado Pago** — para receber pagamentos via Pix/cartão
3. Me chame e atualizo o site com essas funcionalidades!
