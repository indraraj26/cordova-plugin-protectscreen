
# ProtectScreen
 

## Installation
`cordova plugin add cordova-plugin-protectscreen`

## Usage
When a screenshot occurs on iOS, a 'UserDidTakeScreenshot' event is triggered .
```
document.addEventListener("UserDidTakeScreenshot", function() {
    window.alert("Screenshot Taken");
}, false);  
```
## License 
MIT.

## Credit

Tommy-Carlos Williams (http://github.com/devgeeks)
