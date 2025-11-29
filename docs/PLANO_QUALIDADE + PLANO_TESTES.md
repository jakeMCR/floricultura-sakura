Plano de Qualidade 

1. Objetivo 

Garantir que o aplicativo da Floricultura Sakura siga padrões mínimos de qualidade, organização, versionamento e validação. 

2. O que será validado 

Funcional 

Cadastro e login 

Catálogo de arranjos 

Detalhes do produto 

Carrinho 

Finalização de pedido 

Agendamento de entrega 

Não funcional 

Usabilidade 

Responsividade 

Disponibilidade mínima 

Segurança básica 

3. Responsáveis 

Atividade 

Responsável 

Code Review 

Ana (Scrum Master / Dev) 

Organização das branches 

Ana 

Aprovação final das histórias 

Jaqueline (PO) 

Testes manuais 

Ambas 

Atualização dos documentos 

Jaqueline 

 

 

4. Como as revisões serão evidenciadas 

Prints do GitHub (Pull Requests, commits, merges) 

Arquivos salvos em /docs/testes 

Capturas de tela do aplicativo (Protótipo ou simulação) 

Checklist do code review anexado 

Comentários de validação do PO 

5. Critérios de Qualidade do Projeto 

Código organizado em pastas 

Nome de cada arquivo e função deve representar o que faz 

Commits claros com padrão: 

feat: descrição 

fix: descrição 

docs: descrição 

chore: descrição 

Figma consistente com o protótipo 

Minimizar retrabalho 

Documentação sempre atualizada 

6. Padrão de Comunicação 

WhatsApp (grupo interno) → comunicação rápida 

GitHub Issues → histórico técnico 

Documento Sprint/Backlog → registro da entrega 

Plano de Testes 

1. Objetivo do Plano de Testes 

Verificar o funcionamento correto das funcionalidades principais do MVP e garantir que os fluxos básicos estejam sem erros. 

2. Escopo dos Testes 

Serão testados: 

Cadastro 

Login 

Catálogo 

Detalhes do produto 

Adicionar/remover do carrinho 

Finalizar pedido 

Agendar entrega 

3. Tipos de Testes 

Teste Funcional Manual 

Teste de Interface e Navegação 

Teste de Usabilidade (simples) 

Teste de Aceitação do PO 

 

4. Ambiente de Testes 

Protótipo no Figma 

Simulação do fluxo no navegador (modo protótipo) 

Prints como evidência 

5. Casos de Teste (prontos para colar no documento) 

CT01 – Cadastro 

Item 

Descrição 

Objetivo 

Confirmar que o usuário consegue se cadastrar 

Pré-condição 

Tela de cadastro aberta 

Passo a passo 

Preencher nome, telefone, endereço → clicar confirmar 

Resultado esperado 

 

Cadastro criado e ir para catálogo 

CT02 – Login 

Item 

Descrição 

Objetivo 

Verificar login com dados válidos 

Passo a passo 

Inserir telefone + senha 

Resultado esperado 

Acessa o catálogo 

 

CT03 – Ver catálogo 

Item 

Descrição 

Objetivo 

Validar listagem de arranjos 

Resultado esperado 

Imagens, nomes e preços exibidos corretamente 

 

CT04 – Ver detalhes 

| Resultado esperado | Detalhes completos + botão “Adicionar ao carrinho” | 

CT05 – Adicionar ao carrinho 

| Resultado esperado | Item aparece no carrinho com subtotal atualizado | 

CT06 – Remover item 

| Resultado esperado | Item some do carrinho e subtotal atualiza | 

CT07 – Finalizar pedido 

| Resultado esperado | Número do pedido gerado | 

CT08 – Agendar entrega 

| Resultado esperado | Data e período salvos corretamente | 

 


