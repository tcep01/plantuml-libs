# AzureResourceGroups
```text
elements/azure/GeneralServiceIcons/AzureResourceGroups
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureResourceGroups icon](../../../icons/azure/GeneralServiceIcons/AzureResourceGroups.png) | ![AzureResourceGroups element](AzureResourceGroups.element.png) | ![AzureResourceGroups card](AzureResourceGroups.card.png) |
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

' loads the AzureResourceGroups element
include('elements/azure/GeneralServiceIcons/AzureResourceGroups')
AzureResourceGroups('element', 'Resource Groups', 'an optional tech field')
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
include('styles/azure')

' loads the AzureResourceGroups element
include('elements/azure/GeneralServiceIcons/AzureResourceGroups')
AzureResourceGroups('element', 'Resource Groups', 'an optional tech field')
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

' loads the AzureResourceGroups card
include('elements/azure/GeneralServiceIcons/AzureResourceGroups')
AzureResourceGroupsCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
include('styles/azure')

' loads the AzureResourceGroups card
include('elements/azure/GeneralServiceIcons/AzureResourceGroups')
AzureResourceGroupsCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
