# MaterialsCropSquare
```text
elements/materials/Image/MaterialsCropSquare
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsCropSquare icon](../../../icons/materials/Image/MaterialsCropSquare.png) | ![MaterialsCropSquare element](MaterialsCropSquare.element.png) | ![MaterialsCropSquare card](MaterialsCropSquare.card.png) |
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

' loads the MaterialsCropSquare element
include('elements/materials/Image/MaterialsCropSquare')
MaterialsCropSquare('element', 'Crop Square', 'an optional tech field')
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

' loads the MaterialsCropSquare element
include('elements/materials/Image/MaterialsCropSquare')
MaterialsCropSquare('element', 'Crop Square', 'an optional tech field')
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

' loads the MaterialsCropSquare card
include('elements/materials/Image/MaterialsCropSquare')
MaterialsCropSquareCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsCropSquare card
include('elements/materials/Image/MaterialsCropSquare')
MaterialsCropSquareCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
