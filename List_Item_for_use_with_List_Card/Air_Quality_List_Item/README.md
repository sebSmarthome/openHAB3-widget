![Screen1](https://github.com/sebSmarthome/openHAB3-widget/raw/main/List_Item_for_use_with_List_Card/Air_Quality_List_Item/screenshots/AirQualityListItemScreenShot.gif)

This is an UI **List Item** Widget to view the Air Quality information with the [Air Quality Binding](https://www.openhab.org/addons/bindings/airquality/).

**Only use with “List Card” with accordion and rich list items option set to true.<br>Do not use it as a “default list item widget”**

Support to use a light and a dark background.

**Configuration parameters:**

* All title string
* All Icons - Use f7:iconName (Framework7 icon), material:iconName (Material icon) or iconify:iconSet:iconName
* Visibility of Gauges and Label item (No2, O3, PM10, PM2.5)

**items**

* Indice AQI Item
* Poluant dominent Item
* No2 value item
* No2 Alert Level item
* O3 value item
* O3 Alert Level item
* PM10 value item
* PM10 Alert Level item
* PM2.5 value item
* PM2.5 Alert Level item

## Screenshots

![Screen4](https://github.com/sebSmarthome/openHAB3-widget/raw/main/List_Item_for_use_with_List_Card/Air_Quality_List_Item/screenshots/AirQualityListItemScreenShot.gif)

**Standard Library List Card**

![Screen2](https://github.com/sebSmarthome/openHAB3-widget/raw/main/List_Item_for_use_with_List_Card/Air_Quality_List_Item/screenshots/AirQualityListItemScreenShot3.PNG)

**Configure List**

![Screen3](https://github.com/sebSmarthome/openHAB3-widget/raw/main/List_Item_for_use_with_List_Card/Astro_Moon_List_Item/screenshots/AstroMoonListItemScreenShot2.PNG)

## Changelog

### Version 0.2

* New parameters for Gauges visibility
* New Gauges Indice
* use @ symbol in front of an item name string as a shortcut to the displayState from the items dictionary with a fallback to the raw state
  
### Version 0.1

* initial release

## Resources

<https://github.com/sebSmarthome/openHAB3-widget/blob/main/List_Item_for_use_with_List_Card/Air_Quality_List_Item/frs_Air_Quality_list_item.yaml>