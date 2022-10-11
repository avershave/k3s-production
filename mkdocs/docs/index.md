# Application Directory

## Foundry and Crucible

| location                     | api                     | description                                                                                                                                                      |
| ---------------------------- | ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [/identity](/identity)       | [api](/identity/api)    | _Identity_ manages logins/credentials across all of the apps. It can integrate with any OAuth2/OIDC application.                                                 |
| [/topomojo](/topomojo)       | [api](/topomojo/api)    | _TopoMojo_ allows users to build on-demand labs.                                                                                                                 |
| [/alloy](/alloy)             | [api](/alloy/api)       | _Alloy_ joins the other independent Crucible apps together to provide a complete Crucible experience (i.e. labs, on-demand exercises, exercises, etc.).          |
| [/player](/player)           | [api](/player/api)      | _Player_ is the centralized interface where users, teams, and administrators go to participate in the cyber exercise.                                            |
| [/caster](/caster)           | [api](/caster/api)      | _Caster_ provides a web interface that gives exercise developers a way to create, share, and manage topology configurations.                                     |
| [/steamfitter](/steamfitter) | [api](/steamfitter/api) | _Steamfitter_ creates scenarios consisting of a series of scheduled tasks, manual tasks, and injects which run against virtual machines in an exercise/delivery. |
| [/identity](/identity)       | [api](/identity/api)    | _Identity_ manages logins/credentials across all of the apps. It can integrate with any OAuth2/OIDC application.                                                 |

## Learning Management System

| location                         | description                                                                                      |
| -------------------------------- | ------------------------------------------------------------------------------------------------ |
| [moodle](https://moodle.$DOMAIN) | _Moodle_ is an LMS that provides the framework that handles all aspects of the learning process. |

# Third-party Applications

The following third-party applications are loaded on this cluster:

| location                   | description                                                   |
| -------------------------- | ------------------------------------------------------------- |
| [/gitea](/gitea)           | _Gitea_ provides a user interface for editing the web content |
| [/gitlab](/gitlab)         | _Gitlab_ Module repo for caster                               |
| [/stackstorm](/stackstorm) | _StackStorm_ Task processing for steamfitter                  |

![CMU SEI Unitmark](assets/cmu-sei-unitmark.png)
