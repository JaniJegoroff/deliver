# Contributing to `fastlane` and its tools

## New Issues

Before submitting a new issue, do the following:

- Verify you're runing the latest version by running `deliver -v` and compare it with the [project page on GitHub](https://github.com/KrauseFx/deliver).
- Verify you have Xcode tools installed by running `xcode-select --install`.
- Make sure to read through the [README](https://github.com/KrauseFx/deliver) of the project.


When submitting a new issue, please provide the following information:

- The full stack trace and output when running `deliver`.
- The command and parameters you used to launch it.
- Your `Deliverfile` and `Fastfile` (if you are using `fastlane`)

### By providing this information it's much faster and easier to help you


## Pull Requests

Pull requests are always welcome :) 

- Your code editor should use the tab spaces of 2
- Make sure to test the changes yourself before submitting
- Run the tests by executing `bundle install` and then `rspec`