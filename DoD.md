# Definition of Done (DoD) - Floricultura Sakura

Geral:
- Código compilável / executável localmente.
- Documentação atualizada no docs/ quando aplicável.
- Pull Request com descrição e linked issue.

Qualidade de código:
- Código revisado por pelo menos 1 colega (Code Review).
- Lint aplicado e sem erros críticos.
- Testes automatizados básicos (se aplicável) ou testes manuais documentados.

Entrega:
- Feature testada no ambiente local.
- Atualização do CHANGELOG.
- Merge feito via Pull Request para `develop` (e depois para `main`).

1. Critérios Gerais

Para que uma tarefa seja considerada concluída, ela deve atender todos os requisitos abaixo:

✔ 1.1 Código

O código está na branch correta (feature/nome-da-feature).

Não contém erros de compilação ou warnings críticos.

Segue padrão de formatação e organização definido pela equipe.

Não contém prints de debug (console.log, print, etc.).

✔ 1.2 Versionamento (GitFlow Simplificado)

Toda tarefa deve ser desenvolvida em uma branch feature/*.

As merges são feitas via Pull Request.

Todas as branches foram atualizadas com a develop antes do merge.

Conflitos resolvidos antes da revisão.

✔ 1.3 Testes

Testes manuais executados com base nos cenários definidos no Plano de Testes.

Evidências de testes anexadas (prints ou vídeo).

A funcionalidade atende ao comportamento esperado.

Nenhum erro crítico identificado durante o teste.

✔ 1.4 Code Review

Pelo menos uma pessoa do time revisou a tarefa.

Checklist de revisão preenchido:

 Código legível

 Nome de variáveis claras

 Sem duplicação desnecessária

 Tratamento de erro básico

 Documentação atualizada

 Commits organizados

 Funcionalidade testada

Pull Request aprovado pelo revisor.

✔ 1.5 Documentação

README atualizado (se necessário).

Documentos relevantes atualizados no diretório /docs.

Comentários adicionados no código quando necessário.

✔ 1.6 Aceitação

A funcionalidade atende aos critérios da User Story.

A equipe verificou que o fluxo está funcionando no protótipo/simulação.

Product Owner (Jaqueline) realizou a validação final.

A história foi movida para DONE.
