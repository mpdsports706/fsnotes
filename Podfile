use_frameworks!
platform :osx, '10.11'

def available_pods
    pod 'MASShortcut'
    pod 'Down', '~> 0.4.2'
    pod 'Highlightr', :git => 'https://github.com/glushchenko/Highlightr.git', :branch => 'swift4-osx'
    pod 'Marklight', :git => 'https://github.com/glushchenko/Marklight.git', :branch => 'feature/swift4'
end

target 'FSNotes' do
    available_pods
end

target 'FSNotes (CloudKit)' do
    available_pods
end
