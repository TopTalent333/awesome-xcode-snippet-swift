# Code Snippets

[![Language](https://img.shields.io/badge/Swift-3-orange.svg)](https://developer.apple.com/swift/)
[![Platform](https://img.shields.io/badge/Xcode-8-lightgrey.svg)](http://cocoadocs.org/docsets/KeyboardHideManager)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](http://mit-license.org/)

## Install

1. Copy to Terminal or run line by line:

	```bash
	mkdir ~/Library/Developer/Xcode/UserData/CodeSnippets/
	cd ~/Library/Developer/Xcode/UserData/CodeSnippets/
	git init
	git remote add origin https://github.com/bonyadmitr/code-snippets-swift-xcode.git
	git fetch
	git checkout -t origin/master
	```

1. Restart Xcode

## Available code snippets:

### maybe need create snippets with public/private

## ViewController

#### viewDidLoad

```swift
override func viewDidLoad() {
    super.viewDidLoad()
    <#code#>
}
```

#### viewWillAppear

```swift
override func viewWillAppear(_ animated: Bool) {
    super.viewWillAppear(animated)
    <#code#>
}
```

#### viewWillDisappear

```swift
override func viewWillDisappear(_ animated: Bool) {
    super.viewWillDisappear(animated)
    <#code#>
}
```

#### viewDidLayoutSubviews

```swift
override func viewDidLayoutSubviews() {
    super.viewDidLayoutSubviews()
    <#code#>
}
```

## View

#### awakeFromNib

```swift
override func awakeFromNib() {
    super.awakeFromNib()
    <#code#>
}
```

### initSetup

```swift
override init(frame: CGRect) {
    super.init(frame: frame)
    setup()
}
    
required init?(coder aDecoder: NSCoder) {
    super.init(coder: aDecoder)
    setup()
}
    
func setup() {
    
}
```

#### layoutSubviews

```swift
override func layoutSubviews() {
    super.layoutSubviews()
    <#code#>
}
```

## Class

#### classController

```swift
import UIKit

class <#name#>Controller: UIViewController {

}
```

## Other

#### markNew (mNew)

```swift
// MARK: - <#new#>
```

## Touch

#### touchesBegan

```swift
public override func touchesBegan(_ touches: Set<UITouch>, with event: UIEvent?) {
    super.touchesBegan(touches, with: event)
    <#code#>
}
```

#### touchesCancelled

```swift
public override func touchesCancelled(_ touches: Set<UITouch>, with event: UIEvent?) {
    super.touchesCancelled(touches, with: event)
    <#code#>
}
```

#### touchesEnded

```swift
public override func touchesEnded(_ touches: Set<UITouch>, with event: UIEvent?) {
    super.touchesEnded(touches, with: event)
    <#code#>
}
```

#### touchesMoved

```swift
public override func touchesMoved(_ touches: Set<UITouch>, with event: UIEvent?) {
    super.touchesMoved(touches, with: event)
    <#code#>
}
```

## And many others

<!--
## IBOutlet

#### pMapView

```swift
@IBOutlet weak var mapView: MKMapView!
```

#### pLabel

```swift
@IBOutlet weak var <#name#>Label: UILabel!
```

#### pView

```swift
@IBOutlet weak var <#name#>View: UIView!
```

## IBAction

#### 

```swift
@IBAction func action<#name#>Button(_ sender: UIButton) {
    
}
```

#### aBarButton

```swift
@IBAction func action<#name#>BarButton(_ sender: UIBarButtonItem) {
    
}
```

#### 

```swift

```

#### 

```swift

```

#### 

```swift

```

#### 

```swift

```

#### 

```swift

```

#### 

```swift

```-->