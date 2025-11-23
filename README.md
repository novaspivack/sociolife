# About SocioLife

SocioLife is an advanced artificial life simulation exploring emergent social behaviors, tribal dynamics, economic systems, warfare, diplomacy, and technological evolution in a complex multi-agent ecosystem.

SocioLife is written in javascript and runs in your browser. It's graphics and compute intensive, so it's best run on a modern multicore PC.

This work is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License. You are free to share and adapt this work for non-commercial purposes with proper attribution to Nova Spivack (www.novaspivack.com).

## Game Mechanics

### Economic System

- **Commercial Bonds**: Tribes form trade relationships (cyan/blue dashed lines) that provide mutual economic benefits. Both parties gain wealth from trade, with stronger bonds providing greater benefits. Commercial bonds increase resource production (food, materials, ore, treasure) and spawn more money-making roles (Merchants, Artisans, Miners, Builders, Farmers).

- **Taxation**: Tribes tax their populations on all forms of value (energy, wealth, and resources). Taxes are converted to what the tribe needs most - if a nest needs health, taxes convert to HP; otherwise they convert to wealth. This ensures tribes can sustain themselves through their populations' economic activity.

- **Resource Value Scale**: Resources have different values from least (Food) to most (Treasure). Higher-value resources provide more energy and wealth when collected. Agents prioritize gathering valuable resources.

- **Population-Based Wealth**: Nests generate wealth based on their population size and productive roles, creating a balanced economic system where larger, more productive tribes are naturally wealthier.

### Diplomacy

- **Diplomatic Bonds**: Tribes form alliances (yellow/gold lines) through Diplomats who visit other nests. Strong diplomatic bonds provide humanitarian aid - allies send wealth and HP to help struggling partners, but only if they can afford it without risking their own survival.

- **Wartime Aggressive Diplomacy**: When a tribe is at war, their Diplomats aggressively seek alliances with enemies of their opponent and neutral parties, forming strategic partnerships to strengthen their position.

- **Reconstruction Aid**: After a war, diplomatic partners of the winner receive a boon in resources and economy, rewarding alliance during conflict.

- **Diplomatic Aid Conditions**: Allies only provide aid if they are healthy, wealthy, not in too many wars, and the aid won't put their own nest at risk.

### War System

- **War Bonds**: Warring tribes are connected by angry red dashed bonds with animated particles moving both ways, clearly showing active conflicts.

- **War Costs**: Wars are expensive - both nests and agents consume significantly more energy during conflicts. Structural damage to nests increases with each active war, creating stacking penalties for multiple simultaneous conflicts.

- **Spoils of War**: When a nest is defeated, its wealth, resources, energy, and structural value (treasure) are divided among the winning tribes. If there are no war winners, all value is scattered widely around the nest location as random resources.

- **Citizen Conversion**: All citizens (agents) of a defeated tribe are converted to the winning tribe(s), distributed randomly among the victors.

- **Post-War Reconstruction (Baby Boom)**: War winners experience a massive baby boom - their wealth doubles immediately, HP is restored, and they spawn agents at greatly increased rates for an extended period. During this time, they receive continuous wealth generation and resource spawning to support the larger population.

- **War-Time Spawning**: During war, nests spawn fighting roles (Soldiers, Raiders, Guardians) at greatly increased rates to support the conflict.

### Agent Bonds

- **Elastic Bonds**: Flexible white bonds between agents that allow movement and stretching. These represent friendships, alliances, and social connections.

- **Rigid Bonds**: Strong red-orange bonds (thicker lines) that are harder to break and provide stability bonuses. These represent deep commitments and family ties.

- **Group Formation**: Agents with multiple bonds can form stable groups that provide enhanced capabilities, combat bonuses, and shared resources.

### Nest Survival

- **Dying Nest Recovery**: When a nest is in distress (low HP or wealth), it activates emergency survival mechanisms: raises taxes from agents, spawns more resource-gathering workers, and directly produces resources to aid recovery.

- **Structural Health**: Nests have structural health that represents accumulated infrastructure. When a nest dies, this structural value becomes treasure distributed to winners or scattered as resources.

## Key Features

- Complex agent-based simulation with genetic inheritance and evolution
- Multi-tribal societies with dynamic diplomatic and commercial relations
- Technological progression through research trees and specialized roles
- Specialized agent roles: soldiers, merchants, diplomats, artisans, scientists, farmers, miners, builders, and more
- Food chain ecology with predators, prey, and grazers
- Resource management with value-based economy (food to treasure scale)
- Group agents: agents can form stable groups with enhanced capabilities
- Nest system: tribes build and maintain nests that spawn agents and manage resources

## How to Use

- Click the canvas to spawn new agents at that location
- Use the Infect Tool to introduce plagues (cataclysms) that spread disease
- Spawn Monsters to disrupt civilizations and test defenses
- Adjust settings in the Settings panel to explore different dynamics
- Click agents to inspect their DNA, relationships, and status
- Watch as tribes evolve, trade, form alliances, wage wars, and develop technology
- Observe bonds: yellow for diplomacy, cyan for commerce, red for war between nests; white/red-orange for agent bonds
- Monitor the HUD for population, generation count, and other statistics

## Tips

- Increase birth rate if populations are declining too quickly
- Adjust bonding rate to see different social structures and group formations
- Change energy burn rate to affect survival pressure and population dynamics
- Experiment with tech progression speeds to see how technology affects gameplay
- Enable sound for audio feedback on key events (births, deaths, trades, diplomacy, wars)
- Watch for wartime diplomacy: tribes at war will seek allies among enemies of their opponents
- Economic bonds provide mutual benefits: both parties gain wealth from trade
- War winners receive spoils, convert defeated citizens, and experience extended baby booms
- Agents automatically eat food when they touch it if not at full energy
- All resource types convert to useful value (energy or wealth) for agents, tribes, and nests

## License

This work is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License.
