# Notas Fiscas Eletronicas (NF-e)

## O que é?
Notas fiscai eletronicas são documentos emitidos durante qualquer procedimento de compra de produtos ou venda de produtos/serviçõs seja entre empresas ou seja entre empresa + consumidor

## Formato:
NFE são totalmente eletronicas, tendo em contrapartida sua versão simplificada e fisica a DANFE. Sua versão completa pode ser consultada por meio da chave presente na danfe, assim retornando seu arquivo no formato XML.

## SEFAZ
é o orgão nacional, dividido em regiões estaduais onde são criadas as notas fiscais, por meio deste sistema/integração nacional é possível recuperar, criar e recusar as notas fiscas feitas contra a empresa.

---

# Conhecimento de transporte Eletronico (CT-e)
## O que é?
São documentos difitais emitidos sobre a prestação de serviços de transporte de cargas. Tem como finalidade documentar as prestações de serviço de transporte de carga. É obrigátorio em qualquer tipo de modal. Sua versão fisica e simplicafada é o DACTE.

## Emitente
Empresa transportadora resposável por emitir a CTe

## Remetente
Responsável por enviar a mercadoria

## Expedidor
Empresa transportadora responsável por entregar a carga para a empresa transportadora que da inicio do serviço.

## Recebedor
Recebe a carga antes da entrega final. podendo ser outra empresa transportadora ou centro logistico.

## Destinatario
Que recebe na ponta final

## Tomador
Quem paga o frete da operação: Ele pode ser o Remetente, Destinatario, Recebedor, Expedidor

### Exemplos práticos de preenchimento do CT-e

**Caso 1 — Transporte direto**

Nesse cenário:

Emitente: Transportadora A
Remetente: Empresa X
Destinatário: Empresa Y
Tomador do Serviço: Empresa X ou Empresa Y


**Caso 2 — Duas transportadoras (Redespacho)**

Transportadoras A e B participam da operação. A carga sai da Empresa X e vai para a Empresa Y.

* **Primeira Etapa** — CT-e da Transportadora A
    Emitente: Transportadora A
    Remetente: Empresa X
    Destinatário: Empresa Y
    Recebedor: Transportadora B
    Tomador: Empresa X, Empresa Y ou Recebedor

* **Segunda Etapa** — CT-e da Transportadora B
    Emitente: Transportadora B
    Remetente: Empresa X
    Destinatário: Empresa Y
    Expedidor: Transportadora A
    Tomador: Empresa X, Empresa Y ou Expedidor
    Esse é um caso clássico de Redespacho.
