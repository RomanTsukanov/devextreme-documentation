---
id: dxChart.Options.valueAxis.breaks
type: Array<ScaleBreak>
inherits: ScaleBreak
default: undefined
notUsedInTheme: 
---
---
##### shortDescription
Declares a custom scale break collection. Applies only if the axis' [type](/api-reference/10%20UI%20Components/dxChart/1%20Configuration/valueAxis/type.md '/Documentation/ApiReference/UI_Components/dxChart/Configuration/valueAxis/#type') is *"continuous"* or *"logarithmic"*.

---
A scale break allows breaking off a part of the axis to improve the readability of a chart with high amplitude values.

![DevExtreme HTML5 JavaScript Charts Scale Breaks](/images/ChartJS/visual_elements/scale-breaks_val-axis.png)

Each object in the **breaks** array configures a single scale break. Note that a scale break is visible only if its range exceeds the tick interval.

#####See Also#####
- [breakStyle](/api-reference/10%20UI%20Components/dxChart/1%20Configuration/commonAxisSettings/breakStyle '/Documentation/ApiReference/UI_Components/dxChart/Configuration/argumentAxis/breakStyle/')
- [autoBreaksEnabled](/api-reference/10%20UI%20Components/dxChart/1%20Configuration/valueAxis/autoBreaksEnabled.md '/Documentation/ApiReference/UI_Components/dxChart/Configuration/valueAxis/#autoBreaksEnabled')