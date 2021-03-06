---
id: dxPolarChartSeriesTypes.CommonPolarChartSeries.point.hoverStyle
type: Object
---
---
##### shortDescription
An object defining configuration properties for a hovered point.

##### propertyOf
dxPolarChartSeriesTypes.linepolarseries,dxPolarChartSeriesTypes.areapolarseries,dxPolarChartSeriesTypes.scatterpolarseries

---
To set a custom 'hover' style for points in all series at once, use the **point**.**hoverStyle** object within the **commonSeriesSettings** configuration object.

If you have several series of one type, you can set point hover style properties to the values specific to this series type using the corresponding object (**area**, **line** or another) within the **commonSeriesSettings** configuration object. The values that are set within series-type-specific configuration objects override the corresponding common values.

In case you have to set a point hover style property for an individual series, use the **hoverStyle** object within the **series**.**point** object of the [series](/api-reference/10%20UI%20Components/dxPolarChart/1%20Configuration/series '/Documentation/ApiReference/UI_Components/dxPolarChart/Configuration/series/') array. The values that are set individually override corresponding common values.