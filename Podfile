require_relative './mobile_sdk/SalesforceMobileSDK-iOS/mobilesdk_pods'

platform :ios, '13.0'

project 'ARSalesforce.xcodeproj'
target 'ARSalesforce' do
  source 'https://cdn.cocoapods.org/'
  use_frameworks!
  use_mobile_sdk!
end

# Comment the following if you do not want the SDK to emit signpost events for instrumentation. Signposts are  enabled for non release version of the app.
post_install do |installer|
  signposts_post_install(installer)
end
