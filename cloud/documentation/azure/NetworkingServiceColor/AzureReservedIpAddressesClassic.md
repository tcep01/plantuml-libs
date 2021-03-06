# AzureReservedIpAddressesClassic
```text
elements/azure/NetworkingServiceColor/AzureReservedIpAddressesClassic
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureReservedIpAddressesClassic icon](../../../icons/azure/NetworkingServiceColor/AzureReservedIpAddressesClassic.png) | ![AzureReservedIpAddressesClassic element](AzureReservedIpAddressesClassic.element.png) | ![AzureReservedIpAddressesClassic card](AzureReservedIpAddressesClassic.card.png) |
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

' loads the AzureReservedIpAddressesClassic element
include('elements/azure/NetworkingServiceColor/AzureReservedIpAddressesClassic')
AzureReservedIpAddressesClassic('element', 'Reserved Ip Addresses Classic', 'an optional tech field')
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

' loads the AzureReservedIpAddressesClassic element
include('elements/azure/NetworkingServiceColor/AzureReservedIpAddressesClassic')
AzureReservedIpAddressesClassic('element', 'Reserved Ip Addresses Classic', 'an optional tech field')
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

' loads the AzureReservedIpAddressesClassic card
include('elements/azure/NetworkingServiceColor/AzureReservedIpAddressesClassic')
AzureReservedIpAddressesClassicCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AzureReservedIpAddressesClassic card
include('elements/azure/NetworkingServiceColor/AzureReservedIpAddressesClassic')
AzureReservedIpAddressesClassicCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
