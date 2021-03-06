# MaterialsOpenInNew
```text
elements/materials/Action/MaterialsOpenInNew
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsOpenInNew icon](../../../icons/materials/Action/MaterialsOpenInNew.png) | ![MaterialsOpenInNew element](MaterialsOpenInNew.element.png) | ![MaterialsOpenInNew card](MaterialsOpenInNew.card.png) |
## Element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the style
include('styles/materials')

' loads the MaterialsOpenInNew element
include('elements/materials/Action/MaterialsOpenInNew')
MaterialsOpenInNew('element', 'Open In New', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the style
include('styles/materials')

' loads the MaterialsOpenInNew element
include('elements/materials/Action/MaterialsOpenInNew')
MaterialsOpenInNew('element', 'Open In New', 'an optional tech field')
@enduml
```
## Card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the style
include('styles/materials')

' loads the MaterialsOpenInNew card
include('elements/materials/Action/MaterialsOpenInNew')
MaterialsOpenInNewCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the style
include('styles/materials')

' loads the MaterialsOpenInNew card
include('elements/materials/Action/MaterialsOpenInNew')
MaterialsOpenInNewCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
