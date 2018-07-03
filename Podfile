platform :ios, '11.0'
use_frameworks!

def common_pods
  pod 'RxSwift',    '~> 4.0'
  pod 'RxCocoa'
  pod 'LicensePlist'
  pod 'SwiftLint'
  pod 'SnapKit', '~> 4.0.0'
  pod 'Nuke', '~> 5.0'
  pod 'SwiftGen'
  pod 'Reusable'
  pod 'APIKit', :git => 'https://github.com/ishkawa/APIKit', :branch => 'master'
  pod 'XLPagerTabStrip', '~> 8.0.1'
  pod 'RealmSwift'
  pod 'Mattress', '~> 1.0.0'
end

target 'pohe-ios' do
  common_pods
end

target 'pohe-iosUITests' do
  common_pods
end
