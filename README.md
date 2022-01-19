# Custom-action-sheet-

## Usage

```swift
let alertController: UIAlertControllerDimmed = UIAlertControllerDimmed(title: nil, message: "Error!!", preferredStyle: .alert)
alertController.addAction(UIAlertAction(title: "OK", style: .cancel, handler: nil))
alertController.presentWithGrayBackground()
```
