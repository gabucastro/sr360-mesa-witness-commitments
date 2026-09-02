# sr360-mesa-witness-commitments

Canal público de **compromisso criptográfico** da âncora da Mesa SR360 v7.

Este repositório **não contém evidência bruta**. Quando estiver em operação, ele
carrega um único artefato com três campos — o algoritmo, uma raiz de Merkle
(RFC 6962) e a janela de publicação. Nenhum nome de arquivo, nenhuma contagem,
nenhum conteúdo.

A evidência bruta correspondente vive em repositório privado separado, e não é
publicada aqui.

**Ainda não está em operação.** Neste momento o repositório existe apenas para
verificar se as regras de proteção de branch são aplicadas neste plano.

## Proteção da branch

A `main` é alvo do ruleset `main-append-only`, com `Restrict deletions` e
`Block force pushes` marcados e lista de bypass vazia.
