# GcpCloudFirewallRules
```text
elements/gcp/Networking/GcpCloudFirewallRules
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![GcpCloudFirewallRules icon](../../../icons/gcp/Networking/GcpCloudFirewallRules.png) | ![GcpCloudFirewallRules element](GcpCloudFirewallRules.element.png) | ![GcpCloudFirewallRules card](GcpCloudFirewallRules.card.png) |
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
include('styles/gcp')

' loads the GcpCloudFirewallRules element
include('elements/gcp/Networking/GcpCloudFirewallRules')
GcpCloudFirewallRules('element', 'Cloud Firewall Rules', 'an optional tech field')
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
include('styles/gcp')

' loads the GcpCloudFirewallRules element
include('elements/gcp/Networking/GcpCloudFirewallRules')
GcpCloudFirewallRules('element', 'Cloud Firewall Rules', 'an optional tech field')
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
include('styles/gcp')

' loads the GcpCloudFirewallRules card
include('elements/gcp/Networking/GcpCloudFirewallRules')
GcpCloudFirewallRulesCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
include('styles/gcp')

' loads the GcpCloudFirewallRules card
include('elements/gcp/Networking/GcpCloudFirewallRules')
GcpCloudFirewallRulesCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
