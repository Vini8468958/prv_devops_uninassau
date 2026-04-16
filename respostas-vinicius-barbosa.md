# Respostas (Git e GitHub - básico)

1. * git init: cria um repositório Git novo em uma pasta local.

* git clone: copia um repositório já existente (geralmente do GitHub) para sua máquina.

2. Mostra o estado atual do repositório:

* arquivos modificados
* arquivos adicionados
* arquivos não rastreados
* em qual branch você está

3. O git add coloca arquivos na área de staging (preparação).
Ou seja, você escolhe o que exatamente vai entrar no commit.

4. * git fetch: baixa as alterações do repositório remoto, sem aplicar no seu código.

* git pull: baixa e já mistura (merge) automaticamente com sua branch atual.

5. Um branch é uma ramificação do projeto.
Serve para:

* desenvolver funcionalidades separadas
* evitar quebrar o código principal
* trabalhar em equipe sem conflitos diretos

6. É uma solicitação para mesclar mudanças de uma branch para outra.
No GitHub, também permite:

* revisão de código
* comentários
* aprovação antes de juntar o código

7. * Origem (source): de onde vêm as mudanças (ex: develop)
* Destino (target): para onde as mudanças vão (ex: main)

8. O Git gera um conflito de merge.
Você precisa resolver manualmente, escolhendo qual versão manter (ou combinando as duas).

9. Define quais arquivos o Git deve ignorar, como:

* arquivos temporários
* senhas/configurações locais
* pastas como node_modules

10. É o arquivo principal de documentação do projeto.
Normalmente contém:

* descrição do projeto
* como instalar/usar
* tecnologias utilizadas
* instruções para contribuir