# AzureEnterpriseApplications
```text
elements/azure/IdentityServiceColor/AzureEnterpriseApplications
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureEnterpriseApplications icon](../../../icons/azure/IdentityServiceColor/AzureEnterpriseApplications.png) | ![AzureEnterpriseApplications element](AzureEnterpriseApplications.element.png) | ![AzureEnterpriseApplications card](AzureEnterpriseApplications.card.png) |
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

' loads the AzureEnterpriseApplications element
include('elements/azure/IdentityServiceColor/AzureEnterpriseApplications')
AzureEnterpriseApplications('element', 'Enterprise Applications', 'an optional tech field')
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

' loads the AzureEnterpriseApplications element
include('elements/azure/IdentityServiceColor/AzureEnterpriseApplications')
AzureEnterpriseApplications('element', 'Enterprise Applications', 'an optional tech field')
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

' loads the AzureEnterpriseApplications card
include('elements/azure/IdentityServiceColor/AzureEnterpriseApplications')
AzureEnterpriseApplicationsCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AzureEnterpriseApplications card
include('elements/azure/IdentityServiceColor/AzureEnterpriseApplications')
AzureEnterpriseApplicationsCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
