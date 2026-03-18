---
tags:
  - Mecânicas
  - Dungeon
  - Exploração
  - Procedural
---

# 🏰 Dungeon

Sistema de dungeons geradas proceduralmente. Cada dungeon é composta por andares com dificuldade crescente.

> Voltar para [[Mecânicas]]

---

## 🧱 Estrutura

- Geração **procedural** de layout por blocada (seções de blocos)
- Cada dungeon possui **múltiplos andares** verticais
- A dificuldade escala conforme o jogador avança nos andares

## 👹 Chefes

| Tipo       | Frequência          | Descrição                                      |
| ---------- | ------------------- | ---------------------------------------------- |
| **Miniboss** | Todo andar          | Um inimigo forte do andar (versão "pika" do bioma) |
| **Boss**     | A cada 10 andares   | Boss principal do **bioma** atual               |

## 🌍 Biomas

Cada conjunto de 10 andares pertence a um bioma, com:
- Inimigos temáticos (ver [[Inimigos]])
- Boss exclusivo do bioma
- Estética visual própria
- Ver detalhes em [[Biomas]]

---

## 🔗 Relacionados

- [[Mecânicas]] — Índice geral
- [[Inimigos]] — Modelos procedurais de inimigos
- [[Biomas]] — Ambientação por bioma
- [[Árvore de Skill]] — Builds recomendadas para dungeons
