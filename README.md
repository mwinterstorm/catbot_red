catbot
======

## UPDATE
I have decided to re-write catBot as a proper nodejs app. see [repo here](https://github.com/mwinterstorm/catBot)

## Alpha state ##

Bot for matrix. Currently designed for my personal use - mainly silly and fun

Built on Node Red

### Integrations
1. Nightscout 
    1. will report latest sugar with '!meow sugar'
    1. graph of sugar last 3 hours (WIP)
1. Home Assistant (WIP)
    1. camera / person detection alerting - currently hardcoded to my cameras
    1. integrates with Assist in Home Assistant 
    1. location (WIP)
1. Emote reactions to certain phrases 
    1. working but reactions hardcoded 
1. Message replies 
    1. working but reactions hardcoded 
1. updates its profile pic from cat pictures 
    1. working - pulls from a configurable matrix room
1. cat facts from cat fact api
    1. Working - need better plan for getting verified facts
