# MaterialsNotificationsPaused
```text
elements/materials/Social/MaterialsNotificationsPaused
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsNotificationsPaused icon](../../../icons/materials/Social/MaterialsNotificationsPaused.png) | ![MaterialsNotificationsPaused element](MaterialsNotificationsPaused.element.png) | ![MaterialsNotificationsPaused card](MaterialsNotificationsPaused.card.png) |
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

' loads the MaterialsNotificationsPaused element
include('elements/materials/Social/MaterialsNotificationsPaused')
MaterialsNotificationsPaused('element', 'Notifications Paused', 'an optional tech field')
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

' loads the MaterialsNotificationsPaused element
include('elements/materials/Social/MaterialsNotificationsPaused')
MaterialsNotificationsPaused('element', 'Notifications Paused', 'an optional tech field')
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

' loads the MaterialsNotificationsPaused card
include('elements/materials/Social/MaterialsNotificationsPaused')
MaterialsNotificationsPausedCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsNotificationsPaused card
include('elements/materials/Social/MaterialsNotificationsPaused')
MaterialsNotificationsPausedCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
