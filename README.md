# Ateliê da Fortis — Protótipo inicial

Primeira versão pública do montador de **terço tradicional de cinco dezenas**, com identidade preto/dourado e logotipo original da Fortis in Christo.

## Incluído
- Tela de boas-vindas com animação decorativa suave de cruz (a animação de Jesus poderá ser produzida numa etapa futura).
- 8 etapas de personalização após a abertura, com voltar/avançar.
- Acabamento dourado, prata e ouro velho; seleção de entremeio, crucifixo, 11 categorias de missangas (incluindo madeira), Pai-Nosso, linha, estilo de montagem, adornos e nome.
- Prévia **ilustrativa em SVG**, sem prometer correspondência fotográfica exata.
- Preferências guardadas **no mesmo navegador** por `localStorage`.
- Tela final com resumo, faixa de orçamento e envio por WhatsApp (35) 99708-9696.
- Link de feedback via WhatsApp.

## Importante: ainda não incluído
- **Painel administrativo, login privado, banco de dados e envio de fotos.** Isso precisa ser desenvolvido com segurança, usando serviços externos apropriados.
- Catálogo e imagens reais do estoque: os itens exibidos nas galerias são **demonstrativos**, não informações sobre produtos existentes.
- Foto realista feita por IA: produzida posteriormente no atendimento, fora do site.
- Depoimentos reais e animação com Jesus, que dependem de conteúdo autorizado.
- Preços efetivos: a pergunta de orçamento é apenas uma referência de expectativa do cliente.

## Publicar pelo GitHub + Cloudflare Pages
1. Crie um repositório no GitHub e coloque os arquivos **`index.html`, `style.css`, `script.js`, `assets/logo-fortis.png`** na raiz, preservando a pasta `assets`.
2. No Cloudflare, crie um projeto **Pages** conectado ao repositório GitHub.
3. Para site HTML estático, deixe o comando de build vazio; diretório de saída `/` (raiz do repositório), quando solicitado. Caso seja necessário, escolha a opção de site estático sem framework.
4. Publique, teste no celular e verifique as etapas e o link WhatsApp.

O painel administrativo será uma segunda fase. **Não coloque senhas ou chaves secretas no `script.js`** nem em arquivos públicos do repositório.
