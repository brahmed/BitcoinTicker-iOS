# Uncomment the next line to define a global platform for your project
platform :ios, '9.0'

target 'BitcoinTicker' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!


# Pods for BitcoinTicker
pod 'SwiftyJSON', '~> 4.0'
pod 'Alamofire'
end

post_install do |installer|
installer.pods_project.targets.each do |target|
target.build_configurations.each do |config|
config.build_settings['SWIFT_VERSION'] = '4.2'
config.build_settings['MACOSX_DEPLOYMENT_TARGET'] = '10.13'
end
end
end
