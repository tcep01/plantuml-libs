# AzureMonitorRunningApps
```text
elements/azure/FlatSymbols/CneEnterprise/AzureMonitorRunningApps
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureMonitorRunningApps icon](../../../../icons/azure/FlatSymbols/CneEnterprise/AzureMonitorRunningApps.png) | ![AzureMonitorRunningApps element](AzureMonitorRunningApps.element.png) | ![AzureMonitorRunningApps card](AzureMonitorRunningApps.card.png) |
## Element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the AWS style
include('styles/aws')

' loads the AzureMonitorRunningApps element
include('elements/azure/FlatSymbols/CneEnterprise/AzureMonitorRunningApps')
AzureMonitorRunningApps('element', 'Monitor Running Apps', 'an optional tech field')
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

' loads the AWS style
include('styles/aws')

' loads the AzureMonitorRunningApps element
include('elements/azure/FlatSymbols/CneEnterprise/AzureMonitorRunningApps')
AzureMonitorRunningApps('element', 'Monitor Running Apps', 'an optional tech field')
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

' loads the AWS style
include('styles/gcp')

' loads the AzureMonitorRunningApps card
include('elements/azure/FlatSymbols/CneEnterprise/AzureMonitorRunningApps')
AzureMonitorRunningAppsCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the GCP style
include('styles/gcp')

' loads the AzureMonitorRunningApps card
include('elements/azure/FlatSymbols/CneEnterprise/AzureMonitorRunningApps')
AzureMonitorRunningAppsCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```