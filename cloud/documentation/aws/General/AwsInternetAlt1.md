# AwsInternetAlt1
```text
elements/aws/General/AwsInternetAlt1
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsInternetAlt1 icon](../../../icons/aws/General/AwsInternetAlt1.png) | ![AwsInternetAlt1 element](AwsInternetAlt1.element.png) | ![AwsInternetAlt1 card](AwsInternetAlt1.card.png) |
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

' loads the AwsInternetAlt1 element
include('elements/aws/General/AwsInternetAlt1')
AwsInternetAlt1('element', 'Internet Alt1', 'an optional tech field')
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

' loads the AwsInternetAlt1 element
include('elements/aws/General/AwsInternetAlt1')
AwsInternetAlt1('element', 'Internet Alt1', 'an optional tech field')
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

' loads the AwsInternetAlt1 card
include('elements/aws/General/AwsInternetAlt1')
AwsInternetAlt1Card('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AwsInternetAlt1 card
include('elements/aws/General/AwsInternetAlt1')
AwsInternetAlt1Card('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
