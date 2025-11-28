✅ 1. Regras de Versionamento (GitFlow Simplificado)

Adicionar no documento:

Branches oficiais

main → versão estável (produção)

develop → integração das features

feature/ → desenvolvimento de funcionalidades
Ex.: feature/cadastro-usuario

hotfix/ → correções urgentes

release/ (opcional) → preparar versões estáveis

Como trabalhar

Criar branch feature/nome-da-feature

Commits pequenos e descritivos

Abrir Pull Request para develop

Code review obrigatório

Merge só quando:

PR aprovado

Testes manuais OK

DoD completo

✅ 2. Checklist de Code Review (para colocar em docs/)
Checklist de Revisão

 Código segue formatação padrão

 Nome de variáveis e funções claros

 Nenhum “console.log” / “print” de debug

 Tratamento de erro implementado

 Nenhum dado sensível no código

 Comportamento testado localmente

 Documentação atualizada

 Commit e PR bem descritos

 Código não quebra funcionalidades existentes

✅ 3. Atualização da DoD – Definition of Done
Definition of Done — Floricultura Sakura

Para considerar uma história concluída, deve atender:

1. Código

O código está na branch correta (feature/*).

PR aberto e revisado.

Sem warnings ou erros no build.

2. Testes

Teste manual executado.

Cenário de teste documentado.

Evidências anexadas (print, vídeo).

3. Qualidade

Code review concluído com checklist marcado.

Documentação atualizada (README, arquivos /docs).

4. Aceitação

Product Owner validou a entrega.

História movida para “Done”.
