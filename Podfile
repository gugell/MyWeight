platform :ios, '10.0'

target 'MyWeight' do
  use_frameworks!

  target 'MyWeightTests' do
    inherit! :search_paths
    inhibit_all_warnings!

    pod 'SwiftGen', '5.2.1'
    pod 'Nimble'
    pod 'Quick'
    pod 'Nimble-Snapshots'
  end

  target 'MyWeightUITests' do
    inherit! :search_paths
  end
end
