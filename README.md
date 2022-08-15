# MSPBuildSystem
Mac Source Ports Build System

This repo contains the Mac Source Ports build system files. As much as possible I'm trying to break away from using MSP-specific forks and instead use the original project's code, this makes it easier to incorporate their latest code and release strategies. 

The table below is a representation of the migration process. 


|         Source Port         | Migrated | Uses Project's Repo | Uses MacSourcePorts Fork | Versioning Strategy                          |                                      Notes                                      |
|:---------------------------:|:--------:|:-------------------:|:------------------------:|----------------------------------------------|:-------------------------------------------------------------------------------:|
| ArxLibertatis               | ☑️        | ☑️                   |                          | Versioned project tags                       |                                                                                 |
| augustus                    | ☑️        | ☑️                   |                          | Versioned project tags                       |                                                                                 |
| CorsixTH                    | ☑️        | ☑️                   |                          | Versioned project tags, separate arch builds |                                                                                 |
| DevilutionX                 | ☑️        | ☑️                   |                          | Versioned project tags                       |                                                                                 |
| dhewm3                      | ☑️        |                     | ☑️                        | Latest code from our fork                    | Need to do a PR to get some Mac code in                                         |
| disasteroids3d              | ☑️        |                     | ☑️                        | Latest code                                  | This one is fine to leave as our fork. It is rarely going to change             |
| DXX-Rebirth                 | ☑️        | ☑️                   |                          | Latest code                                  | Project does use tags, but not since 2018                                       |
| ECWolf                      | ☑️        |                     | ☑️                        | Latest code                                  | Uses bitucket. Project does not do version tags                                 |
| EDuke32                     |          |                     |                          |                                              |                                                                                 |
| GemRB                       | ☑️        |                     |                          | Latest code                                  | Most recent tag has build issues on macOS, going with latest until next release |
| ioquake3                    |          |                     |                          |                                              |                                                                                 |
| iortcw                      |          |                     |                          |                                              |                                                                                 |
| jk2mv                       |          |                     |                          |                                              |                                                                                 |
| julius                      | ☑️        | ☑️                   |                          | Versioned project tags                       |                                                                                 |
| Maelstrom                   | ☑️        |                     | ☑️                        | Latest code                                  | This one is fine to leave as our fork. It will rarely change                    |
| OpenJK/OpenJO               |          |                     |                          |                                              |                                                                                 |
| OpenJKDF2                   | ☑️        |                     | ☑️                        | Versioned project tags                       | This one needs some attention before I can try and use the project's repo       |
| OpenRCT2                    |          |                     |                          |                                              |                                                                                 |
| OpenTyrian                  |          |                     |                          |                                              |                                                                                 |
| OpenTyrian2000              |          |                     |                          |                                              |                                                                                 |
| OpenXcom                    | ☑️        | ☑️                   |                          | Latest code                                  | Project does use tags, but not since 2014                                       |
| RBDOOM-3-BFG                |          |                     |                          |                                              |                                                                                 |
| Serious-Engine (INCOMPLETE) |          |                     |                          |                                              |                                                                                 |
| rottexpr                    |          |                     |                          |                                              |                                                                                 |
| shockolate                  |          |                     |                          |                                              |                                                                                 |
| The Ur-Quan Masters         |          |                     |                          |                                              |                                                                                 |
| vkQuake                     |          |                     |                          |                                              |                                                                                 |
| yquake2                     | ☑️        | ☑️                   |                          | Versioned project tags                       |                                                                                 |
