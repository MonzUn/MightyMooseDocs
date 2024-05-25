# **Plugin Management and Help**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Chronicler            | Chron           |                                                      | User               | Displays a list of all available Chronicler commands. This is the parent command of all other Chronicler command.                         |
| Status                |                 |                                                      | Admin              | Displays the plugin status display.                                                                                                       |
| Version 				|                 |                                                      | User               | Displays the installed and latest available plugin version.                                                                               |
| Documentation 		|                 |                                                      | User               | Opens the documentation web page.							                                                                              |
| EnableEventRecording  |                 |                                                      | Admin              | Enables event recording.                                                                                                                  |
| DisableEventRecording |                 |                                                      | Admin              | Disables event recording.                                                                                                                 |


# **Custom Event Lookups**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| ListEventTypes        |                 |                                                      | User               | List all event types and their IDs.                                                                                                       |
| Events                |                 | Events, Page (1)                                     | Admin              | List the latest entries for a set of event types. Separate event types by space.                                                          |
| UserEvents            |                 | UsernameOrID, Events, Page (1)                       | Admin              | List the latest entries for a set of event types for a user. Separate event types by space.                                               |
| MyEvents              |                 | Page (1)                                             | Admin              | List the latest entries for a set of event types for yourself. Separate event types by space.                                             |
| LocationEvents        |                 | X, Y, Z, Radius (5), Page (1)                        | Admin              | List the latest entries of the specified types for a location. Separate event types by space.                                             |
| MyLocationEvents      |                 | Events, Radius (5), Page (1)                         | Admin              | List the latest entries of the specified types for your current location.                                                                 |


# **User Lookups**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| User                  |                 | UsernameOrID, Page (1)                               | Admin              | List the latest entries for a user.                                                                                                       |
| Me                    |                 | Page (1)                                             | User               | List the latest entries for yourself.                                                                                                     |


# **Location Lookups**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Location              |                 | X, Y, Z, Radius (5), Page (1)                        | Admin              | List the latest entries for a location.                                                                                                   |
| MyLocation            | MyLoc           | Radius (5), Page (1)                                 | Admin              | List the latest entries for your current location.                                                                                        |


# **Trade Lookups**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Trades                |                 | Page (1)                                             | Admin              | List the latest trade entries.                                                                                                            |
| UserTrades            |                 | UsernameOrID, Page (1)                               | Admin              | List the latest trade entries for a user.                                                                                                 |
| MyTrades              |                 | Page (1)                                             | User               | List the latest trade entries for you.                                                                                                    |


# **Currency Lookups**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Currency              |                 | Page (1)                                             | Admin              | List the latest currency entries.                                                                                                         |
| LocationCurrency      |                 | X, Y, Z, Radius (5), Page (1)                        | Admin              | List the latest currency entries for a location.                                                                                          |
| MyLocationCurrency    |                 | Radius (5), Page (1)                                 | Admin              | List the latest currency entries for your current location.                                                                               |
| UserCurrency          |                 | UsernameOrID, Page (1)                               | Admin              | List the latest currency entries for a user.                                                                                              |
| MyCurrency            |                 | Page (1)                                             | User               | List the latest currency entries for you.                                                                                                 |

# **Property Lookups**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Property              |                 | Page (1)                                             | Admin              | List the latest property entries.                                                                                                         |
| LocationProperties    |                 | X, Y, Z, Radius (50), Page (1)                       | Admin              | List the latest property entries for a location.                                                                                          |
| MyLocationProperties  |                 | Radius (50), Page (1)                                | Admin              | List the latest property entries for your current location.                                                                               |
| UserProperties        |                 | UsernameOrID, Page (1)                               | Admin              | List the latest property entries for a user.                                                                                              |
| MyProperties          |                 | Page (1)                                             | User               | List the latest property entries for you.                                                                                                 |

# **Block Lookups**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Blocks                |                 | Page (1)                                             | Admin              | List the latest block entries.                                                                                                            |
| LocationBlocks        |                 | X, Y, Z, Radius (5), Page (1)                        | Admin              | List the latest block entries for a location.                                                                                             |
| MyLocationBlocks      |                 | Radius (5), Page (1)                                 | Admin              | List the latest block entries for your current location.                                                                                  |
| UserBlocks            |                 | UsernameOrID, Page (1)                               | Admin              | List the latest block entries for a user.                                                                                                 |
| MyBlocks              |                 | Page (1)                                             | User               | List the latest block entries for you.                                                                                                    |

# **Object Lookups**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Objects               |                 | Page (1)                                             | Admin              | List the latest object entries.                                                                                                           |
| LocationObjects       |                 | X, Y, Z, Radius (5), Page (1)                        | Admin              | List the latest object entries for a location.                                                                                            |
| MyLocationObjects     |                 | Radius (5), Page (1)                                 | Admin              | List the latest object entries for your current location.                                                                                 |
| UserObjects           |                 | UsernameOrID, Page (1)                               | Admin              | List the latest object entries for a user.                                                                                                |
| MyObjects             |                 | Page (1)                                             | User               | List the latest object entries for you.                                                                                                   |


# **Inventory Lookups**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Inventory             |                 | Page (1)                                             | Admin              | List the latest inventory entries.                                                                                                        |
| LocationInventory     |                 | X, Y, Z, Radius (5), Page (1)                        | Admin              | List the latest inventory entries for a location.                                                                                         |
| MyLocationInventory   |                 | Radius (5), Page (1)                                 | Admin              | List the latest inventory entries for your current location.                                                                              |
| UserInventory         |                 | UsernameOrID, Page (1)                               | Admin              | List the latest inventory entries for a user.                                                                                             |
| MyInventory           |                 | Page (1)                                             | User               | List the latest inventory entries for you.                                                                                                |

# **Garbage Lookups**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Trash                 |                 | Page (1)                                             | Admin              | List the latest trash entries.                                                                                                            |
| LocationTrash         |                 | X, Y, Z, Radius (5), Page (1)                        | Admin              | List the latest trash entries for a location.                                                                                             |
| MyLocationTrash       |                 | Radius (5), Page (1)                                 | Admin              | List the latest trash entries for your current location.                                                                                  |
| UserTrash             |                 | UsernameOrID, Page (1)                               | Admin              | List the latest trash entries for a user.                                                                                                 |
| MyTrash               |                 | Page (1)                                             | User               | List the latest trash entries for you.                                                                                                    |

# **Tree Lookups**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Trees                 |                 | Page (1)                                             | Admin              | List the latest tree entries.                                                                                                             |
| LocationTrees         |                 | X, Y, Z, Radius (5), Page (1)                        | Admin              | List the latest tree entries for a location.                                                                                              |
| MyLocationTrees       |                 | Radius (5), Page (1)                                 | Admin              | List the latest tree entries for your current location.                                                                                   |
| UserTrees             |                 | UsernameOrID, Page (1)                               | Admin              | List the latest tree entries for a user.                                                                                                  |
| MyTrees               |                 | Page (1)                                             | User               | List the latest tree entries for you.                                                                                                     |

# **Plant Lookups**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Plants                |                 | Page (1)                                             | Admin              | List the latest plant entries.                                                                                                            |
| LocationPlants        |                 | X, Y, Z, Radius (5), Page (1)                        | Admin              | List the latest plant entries for a location.                                                                                             |
| MyLocationPlants      |                 | Radius (5), Page (1)                                 | Admin              | List the latest plant entries for your current location.                                                                                  |
| UserPlants            |                 | UsernameOrID, Page (1)                               | Admin              | List the latest plant entries for a user.                                                                                                 |
| MyPlants              |                 | Page (1)                                             | User               | List the latest plant entries for you.                                                                                                    |

# **Animal Lookups**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Animals               |                 | Page (1)                                             | Admin              | List the latest animal entries.                                                                                                           |
| LocationAnimals       |                 | X, Y, Z, Radius (5), Page (1)                        | Admin              | List the latest animal entries for a location.                                                                                            |
| MyLocationAnimals     |                 | Radius (5), Page (1)                                 | Admin              | List the latest animal entries for your current location.                                                                                 |
| UserAnimals           |                 | UsernameOrID, Page (1)                               | Admin              | List the latest animal entries for a user.                                                                                                |
| MyAnimals             |                 | Page (1)                                             | User               | List the latest animal entries for you.                                                                                                   |

# **Residency Lookups**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Residency             |                 | Page (1)                                             | Admin              | List the latest residency entries.                                                                                                        |
| UserResidency         |                 | UsernameOrID, Page (1)                               | Admin              | List the latest residency entries for a user.                                                                                             |
| MyResidency           |                 | Page (1)                                             | User               | List the latest residency entries for you.                                                                                                |

# **Election Lookups**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Elections             |                 | Page (1)                                             | Admin              | List the latest election entries.                                                                                                         |
| UserElections         |                 | UsernameOrID, Page (1)                               | Admin              | List the latest election entries for a user.                                                                                              |
| MyElections           |                 | Page (1)                                             | User               | List the latest election entries for you.                                                                                                 |

# **Profession Lookups**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Professions           |                 | Page (1)                                             | Admin              | List the latest profession entries.                                                                                                       |
| UserProfessions       |                 | UsernameOrID, Page (1)                               | Admin              | List the latest profession entries for a user.                                                                                            |
| MyProfessions         |                 | Page (1)                                             | User               | List the latest profession entries for you.                                                                                               |

# **Character Lookups**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Characters            |                 | Page (1)                                             | Admin              | List the latest character entries.                                                                                                        |
| UserCharacter         |                 | UsernameOrID, Page (1)                               | Admin              | List the latest character entries for a user.                                                                                             |
| MyCharacter           |                 | Page (1)                                             | User               | List the latest character entries for you.                                                                                                |

# **Login/Logout Lookups**

| **Name**              | **Alias**       | **Parameters**                                       | **Permissions**    | **Description**                                                                                                                           |
|-----------------------|-----------------|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| LoginLogouts          |                 | Page (1)                                             | Admin              | List the latest login/logout entries.                                                                                                     |
| UserLoginLogouts      |                 | UsernameOrID, Page (1)                               | Admin              | List the latest login/logout entries for a user.                                                                                          |
| MyLoginLogouts        |                 | Page (1)                                             | User               | List the latest login/logout entries for you.                                                                                             |