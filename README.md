# Assistente Shopee Pro — página de vendas (MVP)

## Arquivos
- `index.html` — página pronta, responsiva, sem bibliotecas externas.
- `assets/` — pasta para enviar seus prints e imagens reais.
- `COPY_E_ESTRUTURA.md` — copy editorial e análise das referências.

## Publicar em cinco passos
1. Edite `index.html` e substitua `CONFIG.checkoutUrl = ""` pelo link completo da Kiwify (https://...).
2. Coloque os arquivos de mídia na pasta `assets/` com os nomes abaixo. Os espaços sinalizados aparecem automaticamente enquanto as imagens não forem adicionadas.
3. Abra `index.html` no navegador e teste o layout no celular.
4. Configure entrega automática do GPT na Kiwify e execute uma compra de teste antes de anunciar.
5. Configure Pixel/CAPI e eventos conforme sua infraestrutura. Este HTML não instala pixel automaticamente.

## Mídias — nomes de arquivo (recomendado WebP)
- `assets/demo-gpt-principal.webp` — print principal real da IA (hero)
- `assets/demo-resultado.webp` — print de uma resposta completa, produtos ou margem
- `assets/print-pesquisa-produtos.webp` — resultado de pesquisa
- `assets/print-criacao-anuncio.webp` — resultado de anúncio
- `assets/print-calculo-margem.webp` — simulação de precificação
- `assets/prova-principal.webp` — prova real do produto em uso / depoimento autorizado
- `assets/prova-feedback-1.webp` — depoimento verdadeiro (opcional)
- `assets/prova-feedback-2.webp` — depoimento verdadeiro (opcional)

O formato `.webp` é recomendado, mas você pode editar as extensões no HTML se usar PNG/JPG. Não coloque prints falsos nem ganhos simulados como resultados reais.

## Atenção à oferta
- Produto na Kiwify: **Assistente Shopee Pro**.
- Valor de teste: **R$ 29,90** (pagamento único, não promessa de acesso vitalício).
- ChatGPT exige conta do usuário e pode impor limites.
- GPTs estão anunciados para descontinuação em **11/12/2026**. Não prometa acesso vitalício ou indefinido.
- Adicione CNPJ/nome comercial, contato de suporte e páginas de privacidade/termos antes de lançar.
- A página não contém prova social inventada, ofertas com cronômetro falso ou promessas de renda.
- Esta entrega é uma página de venda direta; o quiz é opcional para um segundo teste e não foi incluído neste MVP.
