---
id: dxPolarChartSeriesTypes.CommonPolarChartSeries.visible
type: Boolean
default: true
---
---
##### shortDescription
Specifies the visibility of a series.

---
When this property is set to **false** for a series, the series appears invisible. If you require all the series to appear so, assign the same value to the **visible** property within the **commonSeriesSettings** configuration object.

In addition, you can show/hide series at runtime by using the [show()](/api-reference/10%20UI%20Components/BaseChart/7%20Chart%20Elements/Series/3%20Methods/show().md '/Documentation/ApiReference/UI_Components/dxPolarChart/Chart_Elements/Series/Methods/#show') or [hide()](/api-reference/10%20UI%20Components/BaseChart/7%20Chart%20Elements/Series/3%20Methods/hide().md '/Documentation/ApiReference/UI_Components/dxPolarChart/Chart_Elements/Series/Methods/#hide') method of a particular series respectively.

[note] When the series is invisible, the marker of its [legend item](/concepts/05%20UI%20Components/PolarChart/10%20Visual%20Elements/120%20Legend.md '/Documentation/Guide/UI_Components/PolarChart/Visual_Elements/#Legend') is faded.