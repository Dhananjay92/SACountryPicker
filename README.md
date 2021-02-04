# SACountryPicker

A Simple Country Picker. 
Country picker with phone code, flag image and name.

### Swift Package Manager. 
Use following link to add package to your project and use latest version for stability.

## Usage 

Import `SACountryPicker`

Use `SACountryPickerView` for Picker view.
```
let picker = SACountryPickerView(frame: CGRect(x: 0, y: 0, width: 300, height: 300))
picker.center = view.center
picker.title = "Select Country"
picker.topColor = .systemGreen
picker.delegate = self
self.view.addSubview(picker) 
```
use delegate `SACountryPickerViewDelegate`
for getting clicked country details.

Also you can get country details by using `SACountryPicker`
For all country list and details
```
SACountryPicker().countryList() 
```
For getting flag image
```
SACountryPicker().imageForCountryCode("IN")
```

### Author

Stebin Alex. 

Please share, If you found this useful. 😊
