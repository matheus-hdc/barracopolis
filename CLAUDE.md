# Barracópolis: site

Página estática da política de privacidade do jogo Barracópolis (código em `matheus-hdc/praia-idle`),
publicada pelo GitHub Pages em https://matheus-hdc.github.io/barracopolis/. Em português, sem travessão.
Ao mudar o que o jogo coleta, atualizar o texto e a data.

## Fluxo de trabalho: issues e Pull Requests

Regra permanente, para qualquer agente de IA, de qualquer modelo, que trabalhar neste repositório:

1. **Toda tarefa (correção, melhoria ou funcionalidade nova) vira uma issue no GitHub antes de começar.**
2. **Trabalhar em branch, nunca commitar direto em `main`.**
3. **Entregar por Pull Request.** Na descrição do PR, mencionar a issue relacionada (`Closes #N` ou `Refs #N`).
4. **PRs gerenciam o deploy:** só vai para o ar o que passou por PR.

A `main` é protegida no GitHub: push direto e push forçado são recusados, inclusive para admin.
