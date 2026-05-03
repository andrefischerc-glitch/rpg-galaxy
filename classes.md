# CLASSES

> Cada subclasse concede 3 perícias iniciais, somadas às perícias da raça do personagem. Perícias duplicadas (raça + classe) concedem bônus dobrado.

## Conjurador

### Mago
**Perícias iniciais:** Conhecimento Arcano, Foco Mágico, Investigação
- Elementalista
- Arcanista
- Negro

### Feiticeiro
**Perícias iniciais:** Foco Mágico, Vontade, Conhecimento Religioso
- Invocador
- Necromante
- Espiritualista

### Bruxo
**Perícias iniciais:** Foco Mágico, Conhecimento Arcano, Persuasão
- Patrono
- Ritualístico
- Cultista.

## Bárbaro

### Tanque
**Perícias iniciais:** Combate Defensivo, Aparar, Vigor
- Tanque de defesa
- Tanque de assalto
- Tanque híbrido

### Berserker
**Perícias iniciais:** Combate Bruto, Intimidação, Aguentar Dor
- Sangue
- Desgaste
- Adrenalina

### Selvagem
**Perícias iniciais:** Sobrevivência, Trato com Animais, Combate Bruto
- Pele de Urso
- Pele de Lobo
- Pele de Pantera

## Bardo

### Músico de cordas
**Perícias iniciais:** Performance, Persuasão, Concentração
- Dedilhada
- Percutida
- Friccionadas

### Músico de percussão
**Perícias iniciais:** Performance, Liderança, Concentração
- Percussão direta
- Raspagem
- Agitação

### Músico de Banda
**Perícias iniciais:** Performance, Liderança, Etiqueta
- Maestro de Orquestra
- Coreógrafo
- Vocalista

## Cavaleiro

### Guarda real
**Perícias iniciais:** Liderança, Tática de Combate, Etiqueta
- General
- Instrutor
- Unidade de elite

### Cavaleiro de região
**Perícias iniciais:** Espadas, Cavalgar, Sobrevivência
- Espada do norte
- Espada do leste
- Espada do oeste

### Cavaleiro sem base
**Perícias iniciais:** Espadas, Empunhadura Dupla, Reflexos
- Mestre de armas
- Esgrima Mista
- Empunhadura dupla

## Clérigo

### Paladino
**Perícias iniciais:** Combate Defensivo, Espadas, Devoção
- Escudeiro
- Combatente
- Utilitário

### Devoto
**Perícias iniciais:** Vontade, Conhecimento Religioso, Devoção
- Devoto Caótico
- Devoto Leal
- Devoto Arrependido

### Sacerdote
**Perícias iniciais:** Medicina, Conhecimento Religioso, Empatia
- Curandeiro
- Buffer
- Protetor

## Criminoso

### Ladino
**Perícias iniciais:** Furtividade, Mãos Leves, Acrobacia
- Assassino
- longo alcance
- Furtivo

### Ladrão
**Perícias iniciais:** Mãos Leves, Abrir Fechaduras, Enganação
- Malandro
- àgil
- Sorrateiro

### Bandido
**Perícias iniciais:** Intimidação, Barganha, Combate Bruto
- Negócios
- Mercenário
- Quadrilha

## Guerreiro

### Perfurante
**Perícias iniciais:** Armas de Estocada, Aparar, Reflexos
- Lanceiro
- Rapieira
- Espada de estocada pesada

### Cortante
**Perícias iniciais:** Espadas, Combate Defensivo, Vigor
- Ceifeiro
- Espadachim
- Lenhador

### Impacto
**Perícias iniciais:** Armas Brutas, Combate Bruto, Aguentar Dor
- Desarmado
- Marreta
- Porrete

## Inventor

### Alquimista
**Perícias iniciais:** Alquimia, Herbalismo, Cálculo
- Alquimista de Cura
- Alquimista de Mana
- Alquimista de Dano

### Engenheiro
**Perícias iniciais:** Engenharia, Cálculo, Forja
- Mecânico
- Mágico
- Construtor

### Artesão
**Perícias iniciais:** Ofício Manual, Forja, Aprendizado Rápido
- Escultor
- Ferreiro
- Carpinteiro

## Naturalista

### Druída
**Perícias iniciais:** Conhecimento da Natureza, Foco Mágico, Sobrevivência
- Monstruoso
- Arbório
- Terradi

### Herbalista
**Perícias iniciais:** Herbalismo, Alquimia, Conhecimento da Natureza
- Venenoso
- Chef
- Plantas carnívoras

### Amigo dos Animais
**Perícias iniciais:** Trato com Animais, Sobrevivência, Empatia
- Domésticos
- Selvagens
- hostís

## Patrulheiro

### Escoteiro
**Perícias iniciais:** Sobrevivência, Rastreamento, Conhecimento da Natureza
- Especialista em terrenos
- Especialista em especiárias
- Especialista em sobrevivência

### Caçador
**Perícias iniciais:** Pontaria, Furtividade, Rastreamento
- Fuzileiro
- Arqueiro
- Corpo a corpo

### Reino
**Perícias iniciais:** Geografia, História, Etiqueta
- Conhecedor dos reinos
- Geografia famíliar
- Conhecido dos reis

---

# VIDA DE CADA CLASSE

- Bárbaro: 14 + (2 * var(‘res’))
- Guerreiro: 12 + (2 * var(‘res’))
- Cavaleiro: 12 + (2 * var(‘res’))
- Clérigo: 10 + (2 * var(‘res’))
- Naturalista: 10 + (1 * var(‘res’))
- Patrulheiro: 10 + (1 * var(‘res’))
- Bardo: 8 + (1 * var(‘res’))
- Criminoso: 8 + (1 * var(‘res’))
- Inventor: 8 + (1 * var(‘res’))
- Conjurador: 6 + (1 * var(‘res’))
