# Miados e Latidos — Site

Site institucional de página única para o pet shop Miados e Latidos.

## Como publicar na Vercel

1. Suba a pasta inteira (`index.html` + `assets/`) num repositório GitHub, ou arraste-a direto no painel da Vercel: **Add New > Project > Deploy without Git**.
2. Não é necessário build: é um site estático.
3. Na Vercel, deixe o "Framework Preset" como **Other**.
4. Após o deploy, vá em **Settings > Domains** e adicione `www.petshopmiadoselatidos.com.br`.
5. Aponte o DNS do domínio para a Vercel conforme as instruções da própria tela de configuração de domínio.

## Estrutura

- `index.html` — todo o site (HTML + CSS + JS).
- `assets/loja-entrada.jpg`, `assets/loja-corredor.jpg`, `assets/loja-produtos.jpg` — fotos reais da loja, usadas na seção "Nossa loja".
- `assets/cliente-1.jpg` a `assets/cliente-4.jpg` — fotos de pets clientes, usadas na seção "Quem já passou pelo banho e tosa".

## Para personalizar depois

- **Trocar fotos**: substitua os arquivos em `assets/` mantendo o mesmo nome, ou adicione novos arquivos e ajuste os `src` correspondentes no HTML.
- **Horário de funcionamento**: já está com os horários reais (seg-sex 08:00–18:00, sáb 08:00–16:00, dom fechado) na seção "Localização".
- **WhatsApp**: os botões usam o link `https://wa.me/553135657566` com mensagem pré-preenchida.
