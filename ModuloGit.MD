# Curso Digital: Git
- Registro de mudanças em arquivos, que possibilita recuperar ou acesso a versões anteriores;\
- Desenvolvimneto de código em colaboração com outros integrantes.

## o que é git?
### Snapshots do estado do projeto\
- Git cmd\;
- Git desktop\;
- Git vscode.

## Git status
- Untracked # arquivo adicionado no projeto\;
- Unmodified # salvo no estado atual (já recebeu commit e está salvo)\;
- Modified # sofreu ateração (não recebeu commit e não está salvo)\;
- Staged # sofreu ateração e foi para area de tranferencia "area do git add" (não recebeu commit e não está salvo).

## Comandos
- Git clone http #clone repositório\;
- Git init #inicia o git\;
- Git status # status do projeto # Git status\;
- Git diff # o que foi modificado nos modificados\;
- Git diff --staged #arquivos modificados no staged\;
- Git commit -m "add new title"\;
- Git log #lista ultimos commits\;
- Git restore  File #Retornar modificacoes no arquivo\;
- Git restore --staged File #Retornar um arquivo do staged antes do commit\;
- Git push\;
- Git pull\;
- Git fetch\;
- Git diff origin/branch\;
- Git branch new_name;
- Git log --oneline --decorate.