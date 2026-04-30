```mermaid
classDiagram
    class Character {
        +Name: string
        +Health: int
        +Damage: int
        +Character(string name, int health, int damage)
        +Describe(): void
        +Attack(): void
    }

    class Witch {
        +Intelligence: int
        +Witch(string name, int health, int damage, int intelligence)
        +Describe(): void
        +Attack(): void
    }

    Character <|-- Witch
