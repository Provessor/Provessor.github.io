# Spellcheck

1. TOC
{:toc}

## Spellcheck on GitHub online editor
From what I can tell: not possible. It is designed to be a prose editor.

## Spellcheck in VSCode
Possible. Requies installing extensions such as [Spell Right](https://marketplace.visualstudio.com/items?itemName=ban.spellright). It is nice to see that many of these support querying the OS's (at least on Windows and MacOS) native spell checking API.

## Spellcheck in Emacs
Just works out of the box. Depends on an external program, historically this was `ispell` but more recently has been either `aspell` or `hunspell`. Notably `hunspell` seems to be favoured in many places such as Firefox and Chrome because of its active development history and more permissive licencing[^1].


[^1]: [Aspell and Hunspell: A Tale of Two Spell Checkers](https://battlepenguin.com/tech/aspell-and-hunspell-a-tale-of-two-spell-checkers/)
