
# Checkbox
**obj:`checkbox`**

![lv_checkbox](images/lv_ex_checkbox_1.png)

| Property | Value      | Default    | Description
|----------|------------|------------|--------------
| val      | [int16][9]      | 0          | `1` = checked<br>`0` = unchecked
| text     | [string][10]     | "Checkbox" | The label of the checkbox

!!! note
    The checkbox object ignores the `w` and `h` attribute. These are calculated
    based on the font and text.

???+ example "Example `jsonl`"
    ```json linenums="1"
    {"page":1,"id":5,"obj":"checkbox","x":10,"y":145,"w":105,"text":" Checkbox"}
    ```
Events generated by checkbox are similar to the ones generate by the _toggle_ buttons.

   
[1]: ../data-types.md#colors
[2]: ../data-types.md#boolean
[3]: ../../firmware/configuration/gpio.md#groupid
[4]: ../styling.md#general
[5]: ../styling.md#image
[6]: ../styling.md#value
[7]: ../styling.md#line
[8]: ../styling.md#scale
[9]: ../data-types.md#integer
[10]: ../data-types.md#string
[11]: ../data-types.md#json-object
[12]: ../styling.md
[13]: ../styling.md#padding-and-margin
[14]: ../styling.md#text
[15]: ../data-types.md#variables
[16]: https://lvgl.io/tools/imageconverter
[17]: ../../integrations/home-assistant/sampl_conf.md#using-tags
[18]: ../styling.md#parts