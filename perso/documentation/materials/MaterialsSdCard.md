# MaterialsSdCard
```text
elements/materials/MaterialsSdCard
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsSdCard icon](../../icons/materials/MaterialsSdCard.png) | ![MaterialsSdCard element](MaterialsSdCard.element.png) | ![MaterialsSdCard card](MaterialsSdCard.card.png) |
## Element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/perso"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the MaterialsSdCard element
include('elements/materials/MaterialsSdCard')
MaterialsSdCard('element', 'Sd Card', 'an optional tech field')
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

' loads the MaterialsSdCard element
include('elements/materials/MaterialsSdCard')
MaterialsSdCard('element', 'Sd Card', 'an optional tech field')
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

' loads the MaterialsSdCard card
include('elements/materials/MaterialsSdCard')
MaterialsSdCardCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsSdCard card
include('elements/materials/MaterialsSdCard')
MaterialsSdCardCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
