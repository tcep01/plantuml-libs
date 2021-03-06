# BrandSyncthing
```text
elements/brand/BrandSyncthing
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![BrandSyncthing icon](../../icons/brand/BrandSyncthing.png) | ![BrandSyncthing element](BrandSyncthing.element.png) | ![BrandSyncthing card](BrandSyncthing.card.png) |
## Element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/perso"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the BrandSyncthing element
include('elements/brand/BrandSyncthing')
BrandSyncthing('element', 'Syncthing', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../"

' loads the library
!include ../../library.puml

' loads the BrandSyncthing element
include('elements/brand/BrandSyncthing')
BrandSyncthing('element', 'Syncthing', 'an optional tech field')
@enduml
```
## Card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/perso"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the BrandSyncthing card
include('elements/brand/BrandSyncthing')
BrandSyncthingCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../"

' loads the library
!include ../../library.puml

' loads the BrandSyncthing card
include('elements/brand/BrandSyncthing')
BrandSyncthingCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
