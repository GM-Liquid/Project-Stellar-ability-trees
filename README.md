# Project-Stellar-ability-trees
``mermaid
graph TD;
    classDef default fill:#ffffff,stroke:#000000,stroke-width:1px;
    classDef abilityLevel fill:#f9f9f9,stroke:#333333,stroke-width:1px;

    basic(("Ki Source: Basic Ability\nCost: 100 Azur"))
    L1A1(("Ability 1 Level 1\nCost: 200 Azur"))
    L1A2(("Ability 2 Level 1\nCost: 200 Azur"))
    L1A3(("Ability 3 Level 1\nCost: 200 Azur"))
    L1A4(("Ability 4 Level 1\nCost: 200 Azur"))
    L1A5(("Ability 5 Level 1\nCost: 200 Azur"))
    L1A6(("Ability 6 Level 1\nCost: 200 Azur"))

    L2A1(("Ability 1 Level 2\nCost: 600 Azur"))
    L2A2(("Ability 2 Level 2\nCost: 600 Azur"))
    <!-- ... more abilities for Level 2 ... -->
    
    L3A1(("Ability 1 Level 3\nCost: 1200 Azur"))
    <!-- ... more abilities for Level 3 ... -->

    L4A1(("Ability 1 Level 4\nCost: 2500 Azur"))
    <!-- ... more abilities for Level 4 ... -->

    <!-- Repeat the pattern for the remaining levels up to 9 -->

    basic --| "Ability Level 1" | L1A1
    basic -- L1A2
    basic -- L1A3
    basic -- L1A4
    basic -- L1A5
    basic -- L1A6

    L1A1 --| "Ability Level 2" | L2A1
    L1A2 -- L2A2
    <!-- ... link more abilities to Level 2 ... -->

    L2A1 --| "Ability Level 3" | L3A1
    <!-- ... link abilities to Level 3 ... -->

    L3A1 --| "Ability Level 4" | L4A1
    <!-- ... link abilities to Level 4 ... -->

    <!-- ... continue linking all levels ... -->

    class basic,default;
    class L1A1,L1A2,L1A3,L1A4,L1A5,L1A6,L2A1,L2A2,L3A1,L4A1 abilityLevel;
