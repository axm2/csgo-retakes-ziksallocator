# retakes-ziksallocator
A more complex weapon allocator with extra configurable preferences.

My version adds support for sm_retakes_pistol_num which allows for the first x rounds to be pistol rounds.
and also changes some default values.

## Console Variables

- `sm_retakes_pistol_num`
  - **Description**: Number of pistol rounds after map change
  - **Default**: `5`
- `sm_retakes_random_chance`
  - **Description**: Percentage chance of a random weapon round
  - **Default**: `0`
- `sm_retakes_pistol_only`
  - **Description**: Enable pistol round only mode
  - **Default**: `0`
- `sm_retakes_headshot_only`
  - **Description**: Enable headshot only mode
  - **Default**: `0`
- `sm_retakes_wins_until_force`
  - **Description**: Win streak until T force buys
  - **Default**: `7`
- `sm_retakes_pistol_startmoney`
  - **Description**: Pistol round start money
  - **Default**: `800`
- `sm_retakes_fullbuy_startmoney`
  - **Description**: Normal round start money
  - **Default**: `16000`
- `sm_retakes_grenade_maxvalue`
  - **Description**: Maximum total value of randomly allocated grenades
  - **Default**: `800`
- `sm_retakes_decoy_chance`
  - **Description**: Percentage chance of decoys being considered for random grenade allocation
  - **Default**: `0`
