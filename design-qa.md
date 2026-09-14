# Design QA

## Resultado

Status final: aprovado.

Nenhum problema P0, P1 ou P2 permanece aberto.

## Evidências usadas

| Área | Referência | Implementação | Resultado |
| --- | --- | --- | --- |
| Home desktop | Bright TSA, captura desktop | Home local no navegador em 1363 × 936 | Aprovado |
| Work desktop | Bright TSA, captura desktop | Work local no navegador em 1363 × 936 | Aprovado |
| About desktop | Bright TSA, captura desktop | About local no navegador em 1363 × 936 | Aprovado |
| Home mobile | Captura enviada pelo usuário | Home local em iframe de 390 × 844 | Aprovado |
| Work mobile | Captura enviada pelo usuário | Work local em iframe de 390 × 844 | Aprovado |
| About mobile | Captura enviada pelo usuário | About local em iframe de 390 × 844 | Aprovado |

## Verificações funcionais

• As rotas `/`, `/work/` e `/about/` carregam corretamente.

• O carrossel desktop responde aos controles e à rolagem.

• No mobile, o carrossel vira uma sequência vertical com seis projetos.

• Os quatro filtros de Work respondem e atualizam a grade.

• O modal de projeto abre, fecha pelo botão e fecha com Escape.

• O menu responsivo permanece fixo na parte inferior em 390 × 844.

• A largura útil mobile é de 375 px e não há overflow horizontal.

• Links de LinkedIn, Instagram e currículo estão presentes.

• O build de produção e os quatro testes do pacote Sites passaram.

## Hierarquia visual e fidelidade

• A composição desktop preserva a introdução à esquerda e o projeto em destaque à direita.

• A página Work preserva o seletor visual por pastas e a grade de cartões grandes.

• A página About preserva o cartão editorial de texto, retrato, assinatura e bloco temático escuro.

• Raios, superfícies claras, tipografia, navegação flutuante e ritmo vertical acompanham a referência.

• O conteúdo e as imagens foram adaptados para Rafael Palmeira sem inventar métricas de projeto.

• O copy foi refinado para destacar direção, liderança hands-on, colaboração transversal, sistemas e craft.

• A imagem exata enviada pelo usuário foi validada no menu e na assinatura da Home, enquanto o retrato fotográfico permanece na página About.

## Console

Nenhum erro da aplicação foi encontrado. O navegador de revisão registrou apenas uma mensagem de metadados proveniente de uma extensão do ambiente, sem relação com o site.
