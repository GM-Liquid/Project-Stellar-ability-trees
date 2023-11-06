
```mermaid
classDiagram
    class BasicAbility {
        +name: String
        +description: String
        +cost: Integer
    }
    class AbilityLevel1 {
        +inherit: BasicAbility
        +cost: 200 Azur
        +description: no ability
    }
    class AbilityLevel2 {
        +inherit: BasicAbility
        +cost: 600 Azur
        +description: no ability
    }
    class AbilityLevel3 {
        +inherit: BasicAbility
        +cost: 1200 Azur
        +description: no ability
    }
    class AbilityLevel4 {
        +inherit: BasicAbility
        +cost: 2500 Azur
        +description: no ability
    }
    class AbilityLevel5 {
        +inherit: BasicAbility
        +cost: 7000 Azur
        +description: no ability
    }
    class AbilityLevel6 {
        +inherit: BasicAbility
        +cost: 10000 Azur
        +description: no ability
    }
    class AbilityLevel7 {
        +inherit: BasicAbility
        +cost: 14000 Azur
        +description: no ability
    }
    class AbilityLevel8 {
        +inherit: BasicAbility
        +cost: 20000 Azur
        +description: no ability
    }
    class AbilityLevel9 {
        +inherit: BasicAbility
        +cost: 50000 Azur
        +description: no ability
    }

    BasicAbility <|-- AbilityLevel1
    BasicAbility <|-- AbilityLevel2
    BasicAbility <|-- AbilityLevel3
    BasicAbility <|-- AbilityLevel4
    BasicAbility <|-- AbilityLevel5
    BasicAbility <|-- AbilityLevel6
    BasicAbility <|-- AbilityLevel7
    BasicAbility <|-- AbilityLevel8
    BasicAbility <|-- AbilityLevel9
