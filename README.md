# ios-etalon-app

## List of technical requirenments:

1. Architecture
   - MVVM-C
     - Unidirectional data flow
     - MVVM with bindings
     - Coordinators
   - Rx
   - Complex UI
     - same data in different lists
     - different type of navigation for the same screen (pop + present)
   - REST api
     - decodable JSONs
     - pagination
   - Persist remote data
     - offline mode with restricted access
   - Theme Manager
     - Theme switch
     - support iOS 13 dark + custom themes
2. Libs
   - RxSwift
   - Moya
   - Realm
   - Swiftgen

3. Other requirenments
   - swift
   - codable
   - ios 12+
   - Swiftlint
   - Fastlane
   - git flow + dev/staging/prod envs
   - reusable data sources
   - iphone + ipad
   - storyboards + autolayout
   - UIKit
