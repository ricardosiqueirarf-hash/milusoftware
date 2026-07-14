---
layout: default
title: Integrações
description: Integrações públicas, requisitos e status no MILU Software.
permalink: /integracoes/
---

# Integrações

As integrações ampliam o MILU sem misturar credenciais ou dados entre empresas. Cada conexão deve ser configurada e autorizada individualmente.

## Status das integrações

| Integração | Finalidade | Status público |
|---|---|---|
| Evolution API | Conectar atendimento e CRM ao WhatsApp | Disponível mediante configuração |
| Asaas | Cobranças por boleto e Pix | Disponível mediante configuração |
| Banco Inter | Importação de saldo e extrato para o financeiro | Planejada / em estudo técnico |
| API para parceiros | Integração com sistemas externos autorizados | Acesso controlado, documentação em preparação |

## WhatsApp com Evolution API

A integração permite sincronizar conversas e conectar o atendimento ao contexto comercial do MILU. A estabilidade depende também da instância, da infraestrutura e das regras do provedor utilizado.

Boas práticas:

- utilizar uma instância exclusiva para a empresa;
- proteger URL, token e identificadores de conexão;
- não publicar credenciais em repositórios;
- acompanhar o status da sessão;
- respeitar regras de uso e privacidade do WhatsApp.

## Asaas

Quando habilitada, a integração pode apoiar a emissão e o acompanhamento de cobranças relacionadas a orçamentos aprovados.

A empresa continua responsável por:

- possuir conta ativa no provedor;
- validar taxas e condições comerciais;
- manter credenciais válidas;
- conferir cobranças antes do envio ao cliente;
- atender às obrigações fiscais e financeiras aplicáveis.

## Banco Inter

A integração bancária está planejada para alimentar o financeiro com saldo e extrato de contas empresariais. A implementação deve usar autenticação oficial, certificado, controle de duplicidade e conciliação segura.

Nenhuma credencial bancária deve ser enviada por mensagem, issue pública ou arquivo de documentação.

## Credenciais

Credenciais de integrações são informações confidenciais. Nunca publique:

- tokens;
- client secrets;
- certificados privados;
- chaves de API;
- senhas;
- URLs internas com autenticação incorporada.
