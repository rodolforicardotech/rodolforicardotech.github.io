---
layout: post
title:  (post) ZSH - Adicionando atalhos e habilitando o Anaconda
author: Rodolfo Ricardo
tags: blog
category: blog
-

O Zsh é um interpretador de comando, famoso terminal! No uso do Git, ajuda bastante na localização. Tudo colorido e estiloso!

Utilizo alguns atalhos no meu terminal para facilitar a produtividade. Então, fui pesquisar como poderia fazer isso no ZSH.

Simples! Abra o arquivo .zshsrc e nele adicione o atalho da seguinte forma:


alias NOME_DO_ATALHO=CAMINHO_OU_COMANDO
Recarregue e rode: source ~/.zshrc

Simples!

Para instalar o Anaconda, precisei fazer o seguinte:
1. vim ~/.zshrc
2. source ~/.bash_profile
3. source ~/.zshrc

Ou seja, foi preciso linkar com o bash, que era o antigo terminal que eu utilizava.

Feito isso, tudo certo e funcional!
