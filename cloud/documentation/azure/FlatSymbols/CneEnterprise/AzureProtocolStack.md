# AzureProtocolStack
```text
elements/azure/FlatSymbols/CneEnterprise/AzureProtocolStack
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureProtocolStack icon](../../../../icons/azure/FlatSymbols/CneEnterprise/AzureProtocolStack.png) | ![AzureProtocolStack element](AzureProtocolStack.element.png) | ![AzureProtocolStack card](AzureProtocolStack.card.png) |
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
include('styles/azure')

' loads the AzureProtocolStack element
include('elements/azure/FlatSymbols/CneEnterprise/AzureProtocolStack')
AzureProtocolStack('element', 'Protocol Stack', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../../"

' loads the library
!include ../../../../library.puml

' loads the style
include('styles/azure')

' loads the AzureProtocolStack element
include('elements/azure/FlatSymbols/CneEnterprise/AzureProtocolStack')
AzureProtocolStack('element', 'Protocol Stack', 'an optional tech field')
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
include('styles/azure')

' loads the AzureProtocolStack card
include('elements/azure/FlatSymbols/CneEnterprise/AzureProtocolStack')
AzureProtocolStackCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../../"

' loads the library
!include ../../../../library.puml

' loads the style
include('styles/azure')

' loads the AzureProtocolStack card
include('elements/azure/FlatSymbols/CneEnterprise/AzureProtocolStack')
AzureProtocolStackCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
