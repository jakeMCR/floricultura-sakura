Regras de Versionamento (GitFlow Simplificado)
Branches utilizadas

main — versão estável

develop — integração

feature/* — desenvolvimento de funcionalidades

hotfix/* — correções urgentes

release/* — preparação de versões (opcional)

Fluxo de Trabalho

Criar branch feature/nome-da-feature.

Desenvolver a funcionalidade.

Testar localmente.

Abrir Pull Request para develop.

Passar pela revisão de código.

Após aprovado → merge em develop.

Quando o ciclo terminar → merge para main.

2. Checklist de Code Review

Antes de aprovar um PR, o revisor deve verificar:

✔ Qualidade do código

 Legível e bem organizado

 Nome de variáveis e funções claros

 Sem código morto ou duplicado

 Sem prints/console.log

✔ Boas práticas

 Padrão de commits seguido

 Tratamento de erros básico implementado

 Código simples e direto (KISS)

 Sem violações evidentes de segurança

✔ Testes

 Testes manuais realizados

 Cenários do Plano de Testes atendidos

 Prints anexados (quando aplicável)

✔ Documentação

 README atualizado

 Alterações descritas no PR

 Comentários adicionados quando necessário

3. Atualização do DoD

O DoD foi atualizado para incluir:

Regras de versionamento com GitFlow

Checklist completo de code review

Execução obrigatória de testes manuais

Evidências de teste

Validação da Product Owner

Critérios de documentação

Critérios para Pull Request

📌 O DoD completo está no arquivo DoD.md.
