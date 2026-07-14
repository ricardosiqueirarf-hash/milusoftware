---
layout: default
title: Segurança e privacidade
description: Princípios públicos de segurança e privacidade do MILU Software.
permalink: /seguranca/
---

# Segurança e privacidade

O MILU é uma plataforma multiempresa. A segurança deve proteger dados, usuários, integrações e processos operacionais de cada organização.

## Princípios públicos

- separação dos dados por empresa;
- autenticação individual;
- permissões por função;
- proteção de credenciais e segredos;
- auditoria de ações relevantes;
- validação de entradas e operações sensíveis;
- backups e recuperação compatíveis com o ambiente contratado;
- uso de conexões seguras com serviços externos.

## Responsabilidade dos usuários

A empresa usuária deve:

- utilizar senhas fortes e individuais;
- remover acessos de pessoas desligadas;
- revisar permissões periodicamente;
- proteger computadores e dispositivos conectados;
- não compartilhar tokens ou certificados;
- confirmar dados financeiros antes de executar cobranças ou conciliações.

## Dados sensíveis

Não publique em issues, commits, prints ou documentação:

- dados pessoais de clientes;
- documentos fiscais;
- extratos bancários;
- tokens e chaves de API;
- senhas;
- certificados privados;
- URLs internas autenticadas;
- estruturas completas do banco de dados.

## Relato de vulnerabilidade

Vulnerabilidades devem ser relatadas de forma privada conforme o arquivo [SECURITY.md](../SECURITY.md). Não abra uma issue pública contendo detalhes exploráveis.

## Limites desta documentação

Por segurança, esta documentação não descreve controles internos, regras de firewall, estruturas de banco, políticas de rotação de segredos ou detalhes de infraestrutura.
