# AwsIotShadow
```text
elements/aws/InternetOfThings/AwsIotShadow
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsIotShadow icon](../../../icons/aws/InternetOfThings/AwsIotShadow.png) | ![AwsIotShadow element](AwsIotShadow.element.png) | ![AwsIotShadow card](AwsIotShadow.card.png) |
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

' loads the AwsIotShadow element
include('elements/aws/InternetOfThings/AwsIotShadow')
AwsIotShadow('element', 'Iot Shadow', 'an optional tech field')
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

' loads the AwsIotShadow element
include('elements/aws/InternetOfThings/AwsIotShadow')
AwsIotShadow('element', 'Iot Shadow', 'an optional tech field')
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

' loads the AwsIotShadow card
include('elements/aws/InternetOfThings/AwsIotShadow')
AwsIotShadowCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AwsIotShadow card
include('elements/aws/InternetOfThings/AwsIotShadow')
AwsIotShadowCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
