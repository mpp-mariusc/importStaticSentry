# Uncomment the next line to define a global platform for your project
platform :ios, '10.3'

def modular_header_pods
    pod 'Sentry', :git => 'https://github.com/getsentry/sentry-cocoa.git', :tag => '4.0.0' #, :modular_headers => true
end

target 'importStaticSentry' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  # use_frameworks!

  # Pods for importStaticSentry
  modular_header_pods
end
