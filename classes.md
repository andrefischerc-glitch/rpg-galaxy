# CLASSES

> Cada subclasse concede 3 perícias iniciais, somadas às perícias da raça do personagem. Perícias duplicadas (raça + classe) concedem bônus dobrado.

## Conjurador

### Mago
**Recurso:** Mana
**Perícias iniciais:** Conhecimento Arcano, Foco Mágico, Investigação
- Elementalista
- Arcanista
- Negro

### Feiticeiro
**Recurso:** Alma
**Perícias iniciais:** Foco Mágico, Vontade, Conhecimento Religioso
- Invocador
- Necromante
- Espiritualista

### Bruxo
**Recurso:** Alma
**Perícias iniciais:** Foco Mágico, Conhecimento Arcano, Persuasão
- Patrono
- Ritualístico
- Cultista.

## Bárbaro

### Tanque
**Recurso:** Foco
**Perícias iniciais:** Combate Defensivo, Aparar, Vigor
- Tanque de defesa
- Tanque de assalto
- Tanque híbrido

### Berserker
**Recurso:** Foco
**Perícias iniciais:** Combate Bruto, Intimidação, Aguentar Dor
- Sangue
- Desgaste
- Adrenalina

### Selvagem
**Recurso:** Foco
**Perícias iniciais:** Sobrevivência, Trato com Animais, Combate Bruto
- Pele de Urso
- Pele de Lobo
- Pele de Pantera

## Bardo

### Músico de cordas
**Recurso:** Foco
**Perícias iniciais:** Performance, Persuasão, Concentração
- Dedilhada
- Percutida
- Friccionadas

### Músico de percussão
**Recurso:** Foco
**Perícias iniciais:** Performance, Liderança, Concentração
- Percussão direta
- Raspagem
- Agitação

### Músico de Banda
**Recurso:** Foco
**Perícias iniciais:** Performance, Liderança, Etiqueta
- Maestro de Orquestra
- Coreógrafo
- Vocalista

## Cavaleiro

### Guarda real
**Recurso:** Foco
**Perícias iniciais:** Liderança, Tática de Combate, Etiqueta
- General
- Instrutor
- Unidade de elite

### Cavaleiro de região
**Recurso:** Foco
**Perícias iniciais:** Espadas, Cavalgar, Sobrevivência
- Espada do norte
- Espada do leste
- Espada do oeste

### Cavaleiro sem base
**Recurso:** Foco
**Perícias iniciais:** Espadas, Empunhadura Dupla, Reflexos
- Mestre de armas
- Esgrima Mista
- Empunhadura dupla

## Clérigo

### Paladino
**Recurso:** Fé
**Perícias iniciais:** Combate Defensivo, Espadas, Devoção
- Escudeiro
- Combatente
- Utilitário

### Devoto
**Recurso:** Fé
**Perícias iniciais:** Vontade, Conhecimento Religioso, Devoção
- Devoto Caótico
- Devoto Leal
- Devoto Arrependido

### Sacerdote
**Recurso:** Fé
**Perícias iniciais:** Medicina, Conhecimento Religioso, Empatia
- Curandeiro
- Buffer
- Protetor

## Criminoso

### Ladino
**Recurso:** Foco
**Perícias iniciais:** Furtividade, Mãos Leves, Acrobacia
- Assassino
- longo alcance
- Furtivo

### Ladrão
**Recurso:** Foco
**Perícias iniciais:** Mãos Leves, Abrir Fechaduras, Enganação
- Malandro
- àgil
- Sorrateiro

### Bandido
**Recurso:** Foco
**Perícias iniciais:** Intimidação, Barganha, Combate Bruto
- Negócios
- Mercenário
- Quadrilha

## Guerreiro

### Perfurante
**Recurso:** Foco
**Perícias iniciais:** Armas de Estocada, Aparar, Reflexos
- Lanceiro
- Rapieira
- Espada de estocada pesada

### Cortante
**Recurso:** Foco
**Perícias iniciais:** Espadas, Combate Defensivo, Vigor
- Ceifeiro
- Espadachim
- Lenhador

### Impacto
**Recurso:** Foco
**Perícias iniciais:** Armas Brutas, Combate Bruto, Aguentar Dor
- Desarmado
- Marreta
- Porrete

## Inventor

### Alquimista
**Recurso:** Foco
**Perícias iniciais:** Alquimia, Herbalismo, Cálculo
- Alquimista de Cura
- Alquimista de Mana
- Alquimista de Dano

### Engenheiro
**Recurso:** Foco
**Perícias iniciais:** Engenharia, Cálculo, Forja
- Mecânico
- Mágico
- Construtor

### Artesão
**Recurso:** Foco
**Perícias iniciais:** Ofício Manual, Forja, Aprendizado Rápido
- Escultor
- Ferreiro
- Carpinteiro

## Naturalista

### Druída
**Recurso:** Foco
**Perícias iniciais:** Conhecimento da Natureza, Foco Mágico, Sobrevivência
- Monstruoso
- Arbório
- Terradi

### Herbalista
**Recurso:** Foco
**Perícias iniciais:** Herbalismo, Alquimia, Conhecimento da Natureza
- Venenoso
- Chef
- Plantas carnívoras

### Amigo dos Animais
**Recurso:** Foco
**Perícias iniciais:** Trato com Animais, Sobrevivência, Empatia
- Domésticos
- Selvagens
- hostís

## Patrulheiro

### Escoteiro
**Recurso:** Foco
**Perícias iniciais:** Sobrevivência, Rastreamento, Conhecimento da Natureza
- Especialista em terrenos
- Especialista em especiárias
- Especialista em sobrevivência

### Caçador
**Recurso:** Foco
**Perícias iniciais:** Pontaria, Furtividade, Rastreamento
- Fuzileiro
- Arqueiro
- Corpo a corpo

### Reino
**Recurso:** Foco
**Perícias iniciais:** Geografia, História, Etiqueta
- Conhecedor dos reinos
- Geografia famíliar
- Conhecido dos reis

---

# VIDA DE CADA CLASSE

- Bárbaro: 14 + (2 * var('res'))
- Guerreiro: 12 + (2 * var('res'))
- Cavaleiro: 12 + (2 * var('res'))
- Clérigo: 10 + (2 * var('res'))
- Naturalista: 10 + (1 * var('res'))
- Patrulheiro: 10 + (1 * var('res'))
- Bardo: 8 + (1 * var('res'))
- Criminoso: 8 + (1 * var('res'))
- Inventor: 8 + (1 * var('res'))
- Conjurador: 6 + (1 * var('res'))

---

# RECURSO DE CADA CLASSE

Cada classe possui um recurso específico (Mana, Alma, Fé ou Foco) calculado a partir da fórmula de vida. Veja a explicação completa em **Sistema**.

## Mana — Mago

- Mago: 60 + (10 * var('res'))

## Alma — Bruxo e Feiticeiro

- Bruxo: 30 + (5 * var('res'))
- Feiticeiro: 30 + (5 * var('res'))

## Fé — Clérigo

- Paladino: 50 + (10 * var('res'))
- Devoto: 50 + (10 * var('res'))
- Sacerdote: 50 + (10 * var('res'))

## Foco — Demais Classes

- Bárbaro: 14 + (2 * var('res'))
- Guerreiro: 12 + (2 * var('res'))
- Cavaleiro: 12 + (2 * var('res'))
- Naturalista: 10 + (1 * var('res'))
- Patrulheiro: 10 + (1 * var('res'))
- Bardo: 8 + (1 * var('res'))
- Criminoso: 8 + (1 * var('res'))
- Inventor: 8 + (1 * var('res'))
