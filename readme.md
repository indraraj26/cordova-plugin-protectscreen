
# cordova-plugin-protectscreen
 

## Installation
`cordova plugin add cordova-plugin-protectscreen`

## Usage
When a screenshot occurs (iOS), a 'UserDidTakeScreenshot' event is triggered .

document.addEventListener("UserDidTakeScreenshot", function() {
    window.alert("Screenshot Taken");
}, false);  
    
## License 
MIT.