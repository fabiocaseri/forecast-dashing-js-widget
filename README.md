## Description

[dashing-js](http://fabiocaseri.github.com/dashing-js) widget to display weather from [forecast.io](http://forecast.io).
This widget was forked from <https://gist.github.com/mjamieson/5274790> to add Skycons and the forecast for later in the day.
Ported from [@toddq's work](https://gist.github.com/toddq/5422352)

## Preview
<img src="http://i.imgur.com/EZNs1y2.png" />

## Installation

```shell
$ dashing-js install https://github.com/fabiocaseri/forecast-dashing-js-widget/archive/master.zip
```

## Usage
Adjust the widget to your desired location by editing the latitude and longitude in the jobs file.
Also fill the api key field, you can get one here: <https://developer.forecast.io>

To include the widget in a dashboard, add the following to your dashboard layout file:

```html
    <li data-row="1" data-col="1" data-sizex="1" data-sizey="1">
      <div data-id="forecast" data-view="Forecast" data-color="white" data-title="Rome Weather Forecast"></div>
    </li>
```

## Settings

+   Forecast API Key from [developer.forecast.io](https://developer.forecast.io)
+   Latitude and Longitude for your desired location. Easily obtained from forward geocoding sites such as [freegeocoder.co.uk](http://www.freegeocoder.co.uk/latitude-longitude-search/)
+   Configurable temperature units. (US, SI, UK)