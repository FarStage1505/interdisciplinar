# Site de autenticação — baseado no vídeo enviado

Projeto estático que recria o fluxo mostrado na gravação de tela:

- Login (Welcome back)
- Continue with Google
- Forgot password / Reset password
- Create your account
- Estados de validação dos formulários
- Janela demonstrativa de seleção de conta Google
- Layout escuro, card central, bordas discretas e botão vermelho

## Como executar

Não é necessário instalar dependências.

1. Extraia o ZIP.
2. Abra `index.html` no navegador.

Para rodar por um servidor local, no diretório do projeto use, por exemplo:

```bash
python -m http.server 5500
```

Depois acesse `http://localhost:5500`.

## Observação sobre Google

A tela de "Escolha uma conta" foi recriada como um modal para reproduzir o comportamento visual do vídeo. O Google OAuth real não está conectado, pois isso exige credenciais/configuração de um projeto OAuth.

## Estrutura

```text
site-auth-video/
├── index.html
├── styles.css
├── app.js
└── README.md
```
