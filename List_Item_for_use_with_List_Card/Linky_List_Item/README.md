![Screen1](https://github.com/sebSmarthome/openHAB3-widget/raw/main/List_Item_for_use_with_List_Card/Linky_List_Item/screenshots/LinkyListItemScreenShot.gif)

This is an UI **List Item** Widget to view the consumption of your home from the Linky electric meter by Enedis(French), use with the [Linky Binding](https://www.openhab.org/addons/bindings/linky/) and zigbee2mqtt with Lixee ZLinky_TIC or [Teleinfo Binding](https://www.openhab.org/addons/bindings/teleinfo/).

Linky electric meter with TIC mode: Historical, electricity connection: single phase and pricing mode: HCHP.

Only use with **List Card** with accordion and rich list items option set to true.

Support to use a light and a dark background.

**Configuration parameters:**

* All title string
* Icons - Use f7:iconName (Framework7 icon), material:iconName (Material icon) or iconify:iconSet:iconName
* Visibility of Label item (Apparent power, Yesterday, Current week, Current month, Current year, Meter index)

**items Linky Binding Binding**

* Yesterday energy usage item
* Yesterday's peak power item
* Timestamp of the power peak item
* Current week energy usage item
* Last week energy usage item
* Current month energy usage item
* Last month energy usage item
* Current year energy usage item
* Last year energy usage item
  
**items Teleinfo Binding or ZLinky_TIC**

* Subscribed intensity level item (TIC:ISOUSC)
* RMS current item (TIC:IINST)
* Current pricing period item (TIC:PTEC)
* Apparent power item (TIC:PAPP)
* HC index item (TIC:HCHC)
* HP index item (TIC:HCHP)

## Screenshots

![Screen4](https://github.com/sebSmarthome/openHAB3-widget/raw/main/List_Item_for_use_with_List_Card/Linky_List_Item/screenshots/LinkyListItemScreenShot4.gif)

**Standard Library List Card**

![Screen2](https://github.com/sebSmarthome/openHAB3-widget/raw/main/List_Item_for_use_with_List_Card/Linky_List_Item/screenshots/LinkyListItemScreenShot3.png)

**Configure List**

![Screen3](https://github.com/sebSmarthome/openHAB3-widget/raw/main/List_Item_for_use_with_List_Card/Astro_Moon_List_Item/screenshots/AstroMoonListItemScreenShot2.PNG)

## Changelog

### Version 0.1

* initial release

## Resources

<https://github.com/sebSmarthome/openHAB3-widget/blob/main/List_Item_for_use_with_List_Card/Linky_List_Item/frs_Linky_list_item.yaml>