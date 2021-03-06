# AzureSqlManagedInstances
```text
elements/azure/DatabasesServiceColor/AzureSqlManagedInstances
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureSqlManagedInstances icon](../../../icons/azure/DatabasesServiceColor/AzureSqlManagedInstances.png) | ![AzureSqlManagedInstances element](AzureSqlManagedInstances.element.png) | ![AzureSqlManagedInstances card](AzureSqlManagedInstances.card.png) |
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

' loads the AzureSqlManagedInstances element
include('elements/azure/DatabasesServiceColor/AzureSqlManagedInstances')
AzureSqlManagedInstances('element', 'Sql Managed Instances', 'an optional tech field')
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

' loads the AzureSqlManagedInstances element
include('elements/azure/DatabasesServiceColor/AzureSqlManagedInstances')
AzureSqlManagedInstances('element', 'Sql Managed Instances', 'an optional tech field')
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

' loads the AzureSqlManagedInstances card
include('elements/azure/DatabasesServiceColor/AzureSqlManagedInstances')
AzureSqlManagedInstancesCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AzureSqlManagedInstances card
include('elements/azure/DatabasesServiceColor/AzureSqlManagedInstances')
AzureSqlManagedInstancesCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
