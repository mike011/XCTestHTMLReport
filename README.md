![title](https://i.imgur.com/yTtjLP6.png)

## What is it?

Xcode-like HTML report for Unit and UI Tests

![screenshot](https://i.imgur.com/NHRzoXG.jpg)

## Features

- Supports parallel testing
- Supports attachments:
  - .png
  - .jpeg
  - .txt
- Navigate through the report with the keyboard's arrow keys
- Filter out successful or failed tests
- Displays information about the target device
- Displays activity logs

## Usage

Install XCTestHTMLReport and run your UI tests using fastlane

``` bash
$ fastlane test
```

### Multiple Result Bundle Path

You can also pass multiple times the -r option.

``` bash
$ xchtmlreport -r TestResults1 -r TestResults2

Report successfully created at TestResults1/index.html
```

This will create only one HTML Report in the path you passed with the -r option


## Results

Can be found here at ./fastlane/test_output/index.html

## Contribution

Please create an issue whenever you find an issue or think a feature could be a good addition to XCTestHTMLReport. Always make sure to follow the [Contributing Guidelines](https://github.com/TitouanVanBelle/XCTestHTMLReport/blob/master/CONTRIBUTING.md). Feel free to take a shot at these issues.

## License

XCTestHTMLReport is [available under the MIT license](https://github.com/TitouanVanBelle/XCTestHTMLReport/blob/master/LICENSE).
