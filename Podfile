# Uncomment the next line to define a global platform for your project

platform :ios, '16'

source 'https://github.com/touchlab/KMMBridgeCocoaTest-releases.git'

target 'ios' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for ios
  if ENV.include?("LOCAL_KOTLIN_PATH")
    pod 'allshared', :path => ENV["LOCAL_KOTLIN_PATH"]
  else
    pod 'allshared', '0.1.0'
  end

  target 'iosTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'iosUITests' do
    # Pods for testing
  end
end
