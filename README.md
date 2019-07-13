### ion.rangeslider
---
https://github.com/IonDen/ion.rangeSlider

```js
$("#range").ionRangeSlider({
  type: "double",
  min: 0,
  max: 1000,
  from: 200,
  to: 500,
  grid: true
});
var slider = $("#range").data("ionRangeSlider");
slider.reset();

slider.update({
  from: 300,
  to: 400
});
slider.reset();
slider.destory();

$("#example").ionRangeSlider({
  min: 0,
  max: 10000,
  from: 1000,
  to: 9000,
  type: 'double',
  prefix: "$",
  grid: true,
  grid_num: 10
});

$("#example_id").ionRangeSlider();

slider.update({
  from: 300,
  to: 400
});

slider.reset();
slider.destroy();

$("#range").ionRangeSlider({
  type:"double",
  min: 0,
  max: 1000,
  from: 200,
  to: 500,
  grid: true
});

var slider = $("#range").data("ionRangeSlider");
slider.reset();
```

```
Obj: {
  "input": object,
  "slider": object,
  "min": 1000,
  "max": 100000,
  "from": 10000,
  "from_percent": 10,
  "from": 0,
  "to": 90000,
  "to_percent": 90,
  "to_value": 0,
  "min_pretty": "1 000",
  "max_pretty": "1000 000",
  "from_pretty": "10 000",
  "to_pretty": "90 000"
}
```

```html
<input type="text" id="example_id" name="example_name" value="" />
```

