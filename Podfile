platform :ios, '11.0'
use_frameworks!

def common_pods
  pod 'Moya', '~> 11.0'
  pod 'RealmSwift'
  pod 'SwiftDate', '~> 5.0'
  pod 'DZNEmptyDataSet'
  pod 'ScrollableGraphView'
  pod 'ChameleonFramework/Swift', :git => 'https://github.com/viccalexander/Chameleon.git', :branch => 'wip/swift4'
end

target 'TransactionsSample' do

  common_pods
  
  target 'TransactionsSampleTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'TransactionsSampleUITests' do
    inherit! :search_paths
    # Pods for testing
  end
end

