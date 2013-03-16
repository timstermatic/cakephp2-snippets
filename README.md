CakePHP 2.x Snippets
=================

Collection of CakePHP 2.x snippets for use with the vim plugin, snipMate

Requires snipMate: https://github.com/msanders/snipmate.vim

Instalation:
-------------

Clone into your snippets directory.

To make the snippets available to php and ctp files add the following to after/plugin/snippets.vim

    call ExtractSnipsFile(g:snippets_dir.'cakephp.snippets', 'php')
    call ExtractSnipsFile(g:snippets_dir.'cakephp.snippets', 'ctp')

