# AwsThinkboxDraft
```text
elements/aws/Compute/AwsThinkboxDraft
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsThinkboxDraft icon](../../../icons/aws/Compute/AwsThinkboxDraft.png) | ![AwsThinkboxDraft element](AwsThinkboxDraft.element.png) | ![AwsThinkboxDraft card](AwsThinkboxDraft.card.png) |
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

' loads the AwsThinkboxDraft element
include('elements/aws/Compute/AwsThinkboxDraft')
AwsThinkboxDraft('element', 'Thinkbox Draft', 'an optional tech field')
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

' loads the AwsThinkboxDraft element
include('elements/aws/Compute/AwsThinkboxDraft')
AwsThinkboxDraft('element', 'Thinkbox Draft', 'an optional tech field')
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

' loads the AwsThinkboxDraft card
include('elements/aws/Compute/AwsThinkboxDraft')
AwsThinkboxDraftCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AwsThinkboxDraft card
include('elements/aws/Compute/AwsThinkboxDraft')
AwsThinkboxDraftCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
