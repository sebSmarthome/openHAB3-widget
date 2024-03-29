![Screen1](https://github.com/sebSmarthome/openHAB3-widget/raw/main/List_Item_for_use_with_List_Card/UV_List_Item/screenshots/UVListItemScreenShot4.PNG)

This is an UI **List Item** Widget to view the UV Index information with the [OpenUV Binding](https://www.openhab.org/addons/bindings/openuv/).

**Only use with “List Card” with accordion and rich list items option set to true.<br>Do not use it as a “default list item widget”**

Support to use a light and a dark background.

**Configuration parameters:**

* All title string
* Icons - Use f7:iconName (Framework7 icon), material:iconName (Material icon) or iconify:iconSet:iconName
* Visibility of Gauges and Label item (Max UV Index for the day, Ozone level, Safe exposure time)

**items**

* UVIndex Item
* Alert Item - Alert level associated to given UV Index
* UVMax item - Max UV Index for the day
* UVMaxTime - Max UV Index datetime
* Ozone item - Ozone level
* SafeExposure item - Safe exposure time

## Screenshots

![Screen4](https://github.com/sebSmarthome/openHAB3-widget/raw/main/List_Item_for_use_with_List_Card/UV_List_Item/screenshots/UVListItemScreenShot4.PNG)

**Standard Library List Card**

![Screen2](https://github.com/sebSmarthome/openHAB3-widget/raw/main/List_Item_for_use_with_List_Card/UV_List_Item/screenshots/UVListItemScreenShot3.PNG)

**Configure List**

![Screen3](https://github.com/sebSmarthome/openHAB3-widget/raw/main/List_Item_for_use_with_List_Card/Astro_Moon_List_Item/screenshots/AstroMoonListItemScreenShot2.PNG)

## Changelog

### Version 0.2

* New icons <https://icon-sets.iconify.design/meteocons/> & <https://www.visualpharm.com/free-icons/ozone-595b40b85ba036ed117da791>
* New subtitle UV Max Time
* New parameters for Gauges visibility
* New Gauges Indice
* use @ symbol in front of an item name string as a shortcut to the displayState from the items dictionary with a fallback to the raw state
  
### Version 0.1

* initial release

## Resources

<https://github.com/sebSmarthome/openHAB3-widget/blob/main/List_Item_for_use_with_List_Card/UV_List_Item/frs_UV_list_item.yaml>