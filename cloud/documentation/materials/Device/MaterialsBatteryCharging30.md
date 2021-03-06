# MaterialsBatteryCharging30
```text
elements/materials/Device/MaterialsBatteryCharging30
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsBatteryCharging30 icon](../../../icons/materials/Device/MaterialsBatteryCharging30.png) | ![MaterialsBatteryCharging30 element](MaterialsBatteryCharging30.element.png) | ![MaterialsBatteryCharging30 card](MaterialsBatteryCharging30.card.png) |
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

' loads the MaterialsBatteryCharging30 element
include('elements/materials/Device/MaterialsBatteryCharging30')
MaterialsBatteryCharging30('element', 'Battery Charging30', 'an optional tech field')
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

' loads the MaterialsBatteryCharging30 element
include('elements/materials/Device/MaterialsBatteryCharging30')
MaterialsBatteryCharging30('element', 'Battery Charging30', 'an optional tech field')
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

' loads the MaterialsBatteryCharging30 card
include('elements/materials/Device/MaterialsBatteryCharging30')
MaterialsBatteryCharging30Card('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsBatteryCharging30 card
include('elements/materials/Device/MaterialsBatteryCharging30')
MaterialsBatteryCharging30Card('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
