# WeatherApplication

Since I stareted developing an apps for iOS devices I always was thinking what to make, what to learn new and today I decided to make a simply app for iOS. This is also presentation of my skills using web requests and parsing JSON into array.

This app uses famous framework and also has an auto-layout so it means it fits for all iPhone devices without any problem.

Frameworks I used for this :: Cocoa Pods
Alamofire, SwiftyJSON, NVActivityIndicatorView

ALAMOFIRE: https://cocoapods.org/pods/Alamofire <br/>
SWIFTYJSON: https://cocoapods.org/pods/SwiftyJSON <br/>
NVActivityIndicatorView: https://cocoapods.org/pods/NVActivityIndicatorView

For "catching" weather I used "OpenWeatherMap" api for daily/current weather data:
URL: https://openweathermap.org/current

Applicaion is also using current user geolocation, so it means after you open an app you need to give a permission to app to return you current weather data for your city. 

<img src="https://i.imgur.com/iVVVy8u.png" width="360" height="640">

Once you did it, you will never be asked for it. Also it has an "loading" circle during searching current location to provide you weather info. Application includes changing background, depends if it is day or night. Image in center also depends of weather condition, so fits for all weather conditions: sunny, rainy, snowy etc.

<img src="https://i.imgur.com/biWKQnS.png" width="360" height="640">

:: NOTICE ::

You should register to OpenWeatherMap and use your own api key if you want. It is going to better than mine, because it is limited to calls.
