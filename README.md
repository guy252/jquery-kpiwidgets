
### NumTrendKPI
![NumTrendKPI](https://raw.githubusercontent.com/inneractive-opensrc/jquery-kpiwidgets/master/readmeImages/numTrendKPI.png)

## Installation

```sh
npm install jquery-kpiwidgets
```
### Usage

```js
var numTrend = $("#numAndTrendKPI").NumTrendKPI({
    title: "TOTAL REVENUE",
    footer: "GOAL SET: $3500/WEEK",
    data: {
        value: 4900,
        trend: "up",
        symbol: "$"
    },
    clickHandler: function () {
        alert("this is a click");
    }
});
```

```html
<div class="kpi-container-div">
    <div id="numAndTrendKPI" class="kpi-item"></div>
</div>
```
### [Complete Documentation](https://github.com/inneractive-opensrc/jquery-kpiwidgets/wiki/NumTrendKPI)

***
