
```mermaid
classDiagram
    class Ability {
        +String name
        +String description
        +int cost 
    }

    class AbilityLevel1 {
        Fireball
        Яркий луч вылетает из вашего указательного пальца в точку, выбранную вами в пределах дистанции, где и происходит взрыв пламени с гулким ревом. Все существа в пределах сферы с радиусом 20 футов с центром в этой точке должны совершить спасбросок Ловкости. Цель получает 8к6 урона огнём при провале или половину этого урона при успехе. Этот огонь огибает углы. Он воспламеняет горючие предметы, которые никто не несет и не носит.
        2000 Azur
    }
    class AbilityLevel2 {
        +cost: cost (200)
        +description: no ability
    }
    class AbilityLevel3 {
        +cost: cost (200)
        +description: no ability
    }
    class AbilityLevel4 {
        +cost: 2500 Azur (amount)
        +description: no ability
    }
    class AbilityLevel5 {
        +cost: 7000 Azur (amount)
        +description: no ability
    }
    class AbilityLevel6 {
        +cost: 10000 Azur (amount)
        +description: no ability
    }
    class AbilityLevel7 {
        +cost: 14000 Azur (amount)
        +description: no ability
    }
    class AbilityLevel8 {
        +cost: 20000 Azur (amount)
        +description: no ability
    }
    class AbilityLevel9 {
        +cost: 50000 Azur (amount)
        +description: no ability
    }

    BasicAbility --|> AbilityLevel1
    BasicAbility --|> AbilityLevel2
    BasicAbility --|> AbilityLevel3
    BasicAbility --|> AbilityLevel4
    BasicAbility --|> AbilityLevel5
    BasicAbility --|> AbilityLevel6
    BasicAbility --|> AbilityLevel7
    BasicAbility --|> AbilityLevel8
    BasicAbility --|> AbilityLevel9
