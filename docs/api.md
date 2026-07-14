---
layout: default
title: API pública
description: Status e princípios da futura API pública do MILU Software.
permalink: /api/
---

# API pública

A API pública do MILU está em preparação para integrações autorizadas. Este repositório ainda não publica endpoints de produção, credenciais, estruturas internas ou contratos privados.

## Objetivos

A API deverá permitir, de forma controlada:

- consultar recursos autorizados;
- integrar pedidos e orçamentos;
- conectar catálogos e parceiros;
- receber eventos por webhook;
- automatizar fluxos sem expor a operação interna.

## Princípios previstos

- autenticação por credenciais específicas da integração;
- isolamento por empresa;
- permissões por escopo;
- versionamento explícito;
- idempotência em operações sensíveis;
- limites de uso;
- auditoria e rastreabilidade;
- respostas de erro padronizadas.

## Autenticação

O modelo público de autenticação ainda será formalizado. Tokens e chaves serão exclusivos por ambiente e integração. Credenciais nunca devem ser incluídas em código público, prints, issues ou exemplos reais.

## Ambientes

Quando a API for liberada, a documentação deverá diferenciar:

- ambiente de testes;
- ambiente de produção;
- URLs base;
- escopos disponíveis;
- política de expiração e rotação de credenciais.

## Webhooks

Os webhooks deverão possuir assinatura verificável, identificação do evento, data de emissão e mecanismo de repetição segura. O consumidor deve tratar eventos duplicados de forma idempotente.

## Status atual

Acesso público geral ainda não está liberado. Parceiros interessados devem aguardar a publicação do contrato OpenAPI e das regras de acesso.
