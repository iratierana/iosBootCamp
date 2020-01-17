# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

update_fastlane
cocoapods

default_platform(:ios)
platform :ios do
  desc "Description of what the lane does"
  lane :build do
    gym(
	skip_codesigning: true,
        skip_archive: true
    )
    hola
  end
  lane :hola do
    run_tests()
    # add actions here: https://docs.fastlane.tools/actions
  end
end