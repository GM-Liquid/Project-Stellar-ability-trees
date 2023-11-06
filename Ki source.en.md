
```mermaid
classDiagram
    class BasicAbility {
        +description: String
        +cost: String (amount)
    }
    class AbilityLevel1 {
        +cost (200)
        +description: no ability 
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
