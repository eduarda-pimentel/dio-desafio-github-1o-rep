# :open_file_folder: O que é Git?

Git é um dos sistemas de versionamento de código mais usados. Ele é gratuito e open-sources, rápido e eficiente. 

### &rarr; Comandos básicos do Git

| Comando | Função |
| --------| -------|
| git __clone__ | clonar repositório remoto já existente para a pasta local|
| git __commit__| guardar alterações no repositório local|
| git __pull__ | puxar todas as alterações do repositório remoto|
| git __push__ | forçar todas as mudanças no repoistório remoto |
| git __config__ | alterar configurações de um repositório. Pode ser feita em três escopos: <ul> ,<li>--global (configs do usuário); </li> <li>--system (de odo o sistema/todos os usuários); </li> <li>--local (do repositório local)</li>|
|git __restore__| descarta todas as alterações feitas em um commit ou branch específico|
|git __reset__| remove os commits posteriores ao especificado. Pode ser feito de três formas: <br> <ul><li>--soft (remove commits posteriores ao indicado e coloca na área de preparação)</li><li>--mixed (coloca os arquivos e adiciona à árvore de trabalhos, ficando "untracked")</li><li>--hard (apaga os arquivos dos commits posteriores)</li></ul>

# :open_file_folder: O que é GitHub?

É a plataforma de hospedagem de código para controle de versão com Git. Permite que os usuários contribuam para projetos privados ou open-source.

## Como é estruturado um repositório?

Cada repositório possui um ramo principal __(main)__, que por definição é o primeiro criado, quando se cria um repositório novo. É o branch que o GitHub exibe quando alguém acessa o seu projeto. Por definição, também é o branch que é clonado quando alguém clona o repositório, e também serve como base para os pull requests e commits do código (a menos que seja especificado outro branch durante a ação).

É possível também adicionar outros ramos __(branches)__ ao seu repositório, que agem como um ambiente isolado onde se podem testar novas funcionalidades e corrigir erros com segurança, sem compromentar o funcionamento do código como um todo.Uma vez que o trabalho em um branch está "acabado", é possível mesclá-lo ao ramo principal.

## :link: Links úteis
[GitHub docs - como trabalhar com branches](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)
[Git cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)