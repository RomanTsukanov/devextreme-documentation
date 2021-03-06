You can switch a point into the hover state by calling its [hover()](/api-reference/10%20UI%20Components/BaseChart/7%20Chart%20Elements/Point/3%20Methods/hover().md '/Documentation/ApiReference/UI_Components/dxChart/Chart_Elements/Point/Methods/#hover') method, and its [clearHover()](/api-reference/10%20UI%20Components/BaseChart/7%20Chart%20Elements/Point/3%20Methods/clearHover().md '/Documentation/ApiReference/UI_Components/dxChart/Chart_Elements/Point/Methods/#clearHover') method to switch it back to the normal state. The same API is available [for series](/concepts/05%20UI%20Components/Chart/10%20Series/10%20Hover/07%20API.md '/Documentation/Guide/UI_Components/Chart/Series/Hover/#API'). 

---
##### jQuery

    <!--JavaScript-->
    var togglePointHoverState = function (point) {
        !point.isHovered() ? point.hover() : point.clearHover();        
    }

##### Angular

    <!--TypeScript-->
    import { DxChartModule } from "devextreme-angular";
    // ...
    export class AppComponent {
        togglePointHoverState (point) {
            !point.isHovered() ? point.hover() : point.clearHover();
        }
    }
    @NgModule({
        imports: [
            // ...
            DxChartModule
        ],
        // ...
    })

##### Vue

    <!-- tab: App.vue -->
    <template> 
        <DxChart ... >
        </DxChart>
    </template>

    <script>
    import DxChart from 'devextreme-vue/chart';

    export default {
        components: {
            DxChart
        },
        methods: {
            togglePointHoverState (point) {
                !point.isHovered() ? point.hover() : point.clearHover();
            }
        }
    }
    </script>

##### React

    <!-- tab: App.js -->
    import React from 'react';
    import Chart from 'devextreme-react/chart';

    class App extends React.Component {
        render() {
            return (
                <Chart ... >
                </Chart>
            );
        }

        togglePointHoverState (point) {
            !point.isHovered() ? point.hover() : point.clearHover();
        }

    }

    export default App;

---

#####See Also#####
- [Access a Series Point Using the API](/concepts/05%20UI%20Components/Chart/14%20Series%20Points/25%20Access%20a%20Series%20Point%20Using%20the%20API.md '/Documentation/Guide/UI_Components/Chart/Series_Points/Access_a_Series_Point_Using_the_API/')
#include common-link-callmethods
