Lanche do Professor — Cardápio Digital Interativo

Cardápio digital de página única (SPA) criado para a lanchonete Lanche do Professor, localizada em Seropédica. O sistema permite que o cliente visualize produtos, adicione itens ao carrinho e finalize o pedido via WhatsApp, sem necessidade de pagamento online.


---

🚀 Funcionalidades Principais

Cardápio dinâmico gerado via JavaScript a partir da variável productDatabase.

Filtros por categoria (Pastéis, Caldos, Salgados, etc.).

Carrinho persistente usando localStorage.

Cálculo automático de subtotal, entrega e total.

Taxa de entrega dinâmica (R$ 5,00 ou grátis acima de R$ 10,00).

Checkout com nome, retirada ou entrega.

Envio do pedido via WhatsApp com mensagem formatada.

Design responsivo, incluindo menu hambúrguer no mobile.

Animações AOS (fade-up) no scroll.



---

🗂️ Estrutura Geral

HTML

Página única contendo: hero, filtros, grid de produtos e modal do carrinho.

Componentes estilizados com classes próprias + AOS.


CSS

Layout responsivo.

Estilo simples e direto para cardápio moderno.

Media queries para mobile e desktop.


JavaScript

Geração do cardápio dinamicamente.

Funções de filtro.

Controle do carrinho (add, remove, update).

Persistência com localStorage.

Função de checkout que monta a mensagem do WhatsApp.



---

📦 Como Usar / Editar

1. Alterar produtos

No final do arquivo, procure por:

const productDatabase = [ ... ]

Basta adicionar, remover ou editar itens.

2. Alterar o número do WhatsApp

Procure por:

https://wa.me/5521998488983

Troque para o número desejado.

3. Publicar o site

Pode ser hospedado em:

GitHub Pages

Netlify

Vercel

Qualquer hospedagem estática


Nenhum backend é necessário.


---

📱 Fluxo do Usuário

1. Entra no site.


2. Vê o cardápio.


3. Filtra se quiser.


4. Adiciona ao carrinho.


5. Abre o carrinho.


6. Preenche nome e método.


7. Finaliza via WhatsApp.




---

🧪 Pontos Técnicos Importantes

SPA totalmente client-side.

Uso de localStorage para persistência.

Modal criado manualmente com JS.

Função de montagem da mensagem do WhatsApp com encode automático.



---

🛠️ Melhorias Futuras (opcional)

Campo de observações do pedido.

Sistema de cupons.

Modo claro/escuro.

Análise de vendas via Google Sheets.



---
