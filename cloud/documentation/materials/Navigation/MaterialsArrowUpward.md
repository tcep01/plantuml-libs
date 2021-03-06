# MaterialsArrowUpward
```text
elements/materials/Navigation/MaterialsArrowUpward
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsArrowUpward icon](../../../icons/materials/Navigation/MaterialsArrowUpward.png) | ![MaterialsArrowUpward element](MaterialsArrowUpward.element.png) | ![MaterialsArrowUpward card](MaterialsArrowUpward.card.png) |
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

' loads the MaterialsArrowUpward element
include('elements/materials/Navigation/MaterialsArrowUpward')
MaterialsArrowUpward('element', 'Arrow Upward', 'an optional tech field')
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

' loads the MaterialsArrowUpward element
include('elements/materials/Navigation/MaterialsArrowUpward')
MaterialsArrowUpward('element', 'Arrow Upward', 'an optional tech field')
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

' loads the MaterialsArrowUpward card
include('elements/materials/Navigation/MaterialsArrowUpward')
MaterialsArrowUpwardCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsArrowUpward card
include('elements/materials/Navigation/MaterialsArrowUpward')
MaterialsArrowUpwardCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
