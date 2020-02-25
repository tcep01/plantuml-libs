# AwsIotAnalyticsDataSet
```text
elements/aws/InternetOfThings/AwsIotAnalyticsDataSet
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsIotAnalyticsDataSet icon](../../../icons/aws/InternetOfThings/AwsIotAnalyticsDataSet.png) | ![AwsIotAnalyticsDataSet element](AwsIotAnalyticsDataSet.element.png) | ![AwsIotAnalyticsDataSet card](AwsIotAnalyticsDataSet.card.png) |
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

' loads the AwsIotAnalyticsDataSet element
include('elements/aws/InternetOfThings/AwsIotAnalyticsDataSet')
AwsIotAnalyticsDataSet('element', 'Iot Analytics Data Set', 'an optional tech field')
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

' loads the AWS style
include('styles/aws')

' loads the AwsIotAnalyticsDataSet element
include('elements/aws/InternetOfThings/AwsIotAnalyticsDataSet')
AwsIotAnalyticsDataSet('element', 'Iot Analytics Data Set', 'an optional tech field')
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

' loads the AwsIotAnalyticsDataSet card
include('elements/aws/InternetOfThings/AwsIotAnalyticsDataSet')
AwsIotAnalyticsDataSetCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the GCP style
include('styles/gcp')

' loads the AwsIotAnalyticsDataSet card
include('elements/aws/InternetOfThings/AwsIotAnalyticsDataSet')
AwsIotAnalyticsDataSetCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```