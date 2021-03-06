# MaterialsTimerOff
```text
elements/materials/Image/MaterialsTimerOff
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsTimerOff icon](../../../icons/materials/Image/MaterialsTimerOff.png) | ![MaterialsTimerOff element](MaterialsTimerOff.element.png) | ![MaterialsTimerOff card](MaterialsTimerOff.card.png) |
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

' loads the MaterialsTimerOff element
include('elements/materials/Image/MaterialsTimerOff')
MaterialsTimerOff('element', 'Timer Off', 'an optional tech field')
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

' loads the MaterialsTimerOff element
include('elements/materials/Image/MaterialsTimerOff')
MaterialsTimerOff('element', 'Timer Off', 'an optional tech field')
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

' loads the MaterialsTimerOff card
include('elements/materials/Image/MaterialsTimerOff')
MaterialsTimerOffCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsTimerOff card
include('elements/materials/Image/MaterialsTimerOff')
MaterialsTimerOffCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
