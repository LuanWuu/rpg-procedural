---
tags:
  - Mecânicas
  - Atributos
  - Progressão
---

# 📊 Atributos

Sistema de atributos do personagem. Cada atributo possui um **valor fixo** e um **multiplicador**, permitindo builds variadas.

> Voltar para [[Mecânicas]]

---

## 🗡️ Atributos de Combate

| Atributo          | Descrição                          |
| ----------------- | ---------------------------------- |
| **HP**            | Quantidade de Vida                 |
| **Estamina**      | Recurso para ações físicas (correr, esquivar, ataque corpo-a-corpo) |
| **Mana**          | Recurso para disparar [[Magia]]    |
| **Defesa**        | Absorção de Dano Físico            |
| **Ataque**        | Multiplicador de Dano Físico em %  |
| **Defesa Mágica** | Absorção de Dano Mágico            |
| **Ataque Mágico** | Multiplicador de Dano Mágico em %  |

## 🔨 Atributo de Proficiência (FAMC)

| Proficiência    | Área           |
| --------------- | -------------- |
| **Forja**       | [[Fabricação]] |
| **Alquimia**    | [[Fabricação]] |
| **Manufatura**  | [[Fabricação]] |
| **Cozinha**     | [[Fabricação]] |

> ⚠️ Proficiência **não sobe com nível**. Sobe apenas por produtos fabricados e por completar **sidequests** (missões secundárias).

---

## ⬆️ Progressão por Nível

A cada nível, o jogador recebe **10 pontos** para distribuir livremente entre **valores fixos** e **multiplicadores**.

Além disso, todos os atributos ganham **+1 ponto fixo** automaticamente por nível.

### Exemplo: Nível 0 → Nível 1

**Nível 0 — Valores Fixos (Origem):**

| Atributo       | Valor |
| -------------- | ----- |
| HP             | 1     |
| Estamina       | 1     |
| Mana           | 1     |
| Defesa         | 1     |
| Ataque         | 1     |
| Defesa Mágica  | 1     |
| Ataque Mágico  | 1     |

**Nível 0 — Multiplicadores:**

Todos os multiplicadores começam em **1.0**.

**Nível 1 — Distribuindo 10 pontos (exemplo: 5 em HP fixo, 5 em HP multiplicador):**

- HP Fixo: `1 + 5 = 6` → valor base do jogo é **100**, então HP = `100 + 5 = 105`
- HP Multiplicador: `1.00 + 0.05 = 1.05`
- HP Final: `105 × 1.05 = 110.25` → **arredonda para 110**

> 💡 O jogador escolhe onde investir seus pontos, criando builds únicas entre tanque, DPS mágico, DPS físico, etc.

---

## 🔗 Relacionados

- [[RPG]] — Sistema de progressão geral
- [[Árvore de Skill]] — Habilidades especializadas por classe
- [[Fabricação]] — Sistema de crafting (ligado à proficiência FAMC)
