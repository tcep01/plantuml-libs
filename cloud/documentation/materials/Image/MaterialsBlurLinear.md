# MaterialsBlurLinear
```text
elements/materials/Image/MaterialsBlurLinear
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsBlurLinear icon](../../../icons/materials/Image/MaterialsBlurLinear.png) | ![MaterialsBlurLinear element](MaterialsBlurLinear.element.png) | ![MaterialsBlurLinear card](MaterialsBlurLinear.card.png) |
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
include('styles/materials')

' loads the MaterialsBlurLinear element
include('elements/materials/Image/MaterialsBlurLinear')
MaterialsBlurLinear('element', 'Blur Linear', 'an optional tech field')
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
include('styles/materials')

' loads the MaterialsBlurLinear element
include('elements/materials/Image/MaterialsBlurLinear')
MaterialsBlurLinear('element', 'Blur Linear', 'an optional tech field')
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
include('styles/materials')

' loads the MaterialsBlurLinear card
include('elements/materials/Image/MaterialsBlurLinear')
MaterialsBlurLinearCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
include('styles/materials')

' loads the MaterialsBlurLinear card
include('elements/materials/Image/MaterialsBlurLinear')
MaterialsBlurLinearCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
