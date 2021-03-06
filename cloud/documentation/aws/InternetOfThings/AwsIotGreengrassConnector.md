# AwsIotGreengrassConnector
```text
elements/aws/InternetOfThings/AwsIotGreengrassConnector
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsIotGreengrassConnector icon](../../../icons/aws/InternetOfThings/AwsIotGreengrassConnector.png) | ![AwsIotGreengrassConnector element](AwsIotGreengrassConnector.element.png) | ![AwsIotGreengrassConnector card](AwsIotGreengrassConnector.card.png) |
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
include('styles/aws')

' loads the AwsIotGreengrassConnector element
include('elements/aws/InternetOfThings/AwsIotGreengrassConnector')
AwsIotGreengrassConnector('element', 'Iot Greengrass Connector', 'an optional tech field')
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
include('styles/aws')

' loads the AwsIotGreengrassConnector element
include('elements/aws/InternetOfThings/AwsIotGreengrassConnector')
AwsIotGreengrassConnector('element', 'Iot Greengrass Connector', 'an optional tech field')
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
include('styles/aws')

' loads the AwsIotGreengrassConnector card
include('elements/aws/InternetOfThings/AwsIotGreengrassConnector')
AwsIotGreengrassConnectorCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
include('styles/aws')

' loads the AwsIotGreengrassConnector card
include('elements/aws/InternetOfThings/AwsIotGreengrassConnector')
AwsIotGreengrassConnectorCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
