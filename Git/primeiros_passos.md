## O que é o Git?

O Git é um sistema de controle de versão distribuído, criado por Linus Torvalds em 2005, com o objetivo de ser rápido e eficiente. Ele é amplamente utilizado por desenvolvedores de software para controlar as mudanças no código fonte durante o desenvolvimento de um software.

## Por que usar o Git?

Imagine que você trabalha em uma empresa e está desenvolvendo um software. Você e sua equipe estão trabalhando em diferentes partes do código:
- Um está fazendo a tela de login;
- Outro está fazendo a tela de cadastro;
- Outro está fazendo a tela de perfil do usuário;

Como vocês vão juntar essas partes do código? Como vocês vão saber quem fez o que? Como vocês vão saber o que mudou no código? Como vocês vão voltar para uma versão anterior do código caso algo dê errado?

O Git resolve todos esses problemas. Com ele, é possível:
- Juntar as partes do código;
- Saber quem fez o que;
- Saber o que mudou no código;
- Voltar para uma versão anterior do código.
- E muito mais!

## Git vs GitHub

É importante entender que existe uma diferença entre o Git e o GitHub:
- O Git é um sistema de controle de versão(VCS) que ***controla*** as mudanças no código no seu computador;
- O GitHub é uma plataforma de hospedagem de código que ***armazena*** o código na internet para que outras pessoas possam acessar e colaborar com o desenvolvimento do software

Ou seja, o Git é a ferramenta que você vai usar para controlar as mudanças no código no seu computador, enquanto o GitHub é a plataforma que você vai usar para deixar o código disponível na internet para outras pessoas acessarem.

## Como usar o Git e Github?
Instale o Git no seu computador e crie uma conta no GitHub.
- Instale o [Git](https://git-scm.com/downloads) no seu computador;
- Abra o terminal e digite `git --version` para verificar se o Git foi instalado corretamente;
- No terminal digite `git config --global user.name "Seu Nome Completo"` e `git config --global user.email "email@email.com"` para configurar o nome e email que serão usados no Git (Essas informações serão usadas para identificar quem fez as mudanças no código e estarão visíveis para todos que acessarem o repositório);
- Crie uma conta no GitHub;

Como pegar projetos do GitHub?
- No GitHub, vá até o repositório que você quer clonar;
- Clique no botão "Code" e copie o link https do repositório;
- No terminal, digite `git clone link_do_repositorio` para clonar o repositório no seu computador.

Como enviar projetos para o GitHub?
- Após fazer as mudanças no código, digite `git add .` para selecionar TODAS as mudanças;
- Digite `git commit -m "Mensagem do commit"` para salvar as mudanças e descrever o que foi feito;
- Digite `git push origin nome_da_branch` para enviar as mudanças para o GitHub.