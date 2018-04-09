# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

abstract_target 'Hogshead' do
  use_frameworks!
  inhibit_all_warnings!

  pod 'RxSwift', '~> 4.0'
  pod 'RxCocoa', '~> 4.0'
  pod 'RxDataSources', '~> 3.0'
  pod 'Swinject'
  pod 'SwinjectStoryboard'

  target 'AlphaOne' do
  end

  target 'AlphaOneTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'AlphaOneUITests' do
    inherit! :search_paths
    # Pods for testing
  end

end
