A single-action FAB represents the primary action of a screen. According to the [guidelines](https://material.io/design/components/buttons-floating-action-button.html#usage), this action should be constructive, such as, create, share, explore, or edit, as in the following example:

<div class="simulator-desktop-container" style="height:362px" data-view="/Content/Applications/20_2/GettingStartedWith/FloatingActionButton/SingleAction/index.html, /Content/Applications/20_2/GettingStartedWith/FloatingActionButton/SingleAction/index.js, /Content/Applications/20_2/GettingStartedWith/FloatingActionButton/SingleAction/index.css"></div>

To create a single-action FAB, add one [SpeedDialAction](/api-reference/10%20UI%20Widgets/dxSpeedDialAction '/Documentation/ApiReference/UI_Components/dxSpeedDialAction/') to your page and specify its [onClick](/api-reference/10%20UI%20Widgets/dxSpeedDialAction/1%20Configuration/onClick.md '/Documentation/ApiReference/UI_Components/dxSpeedDialAction/Configuration/#onClick') and [icon](/api-reference/10%20UI%20Widgets/dxSpeedDialAction/1%20Configuration/icon.md '/Documentation/ApiReference/UI_Components/dxSpeedDialAction/Configuration/#icon') properties. Other properties are optional, but we also specify a [hint](/api-reference/10%20UI%20Widgets/Widget/1%20Configuration/hint.md '/Documentation/ApiReference/UI_Components/dxSpeedDialAction/Configuration/#hint').

To position the FAB, use the [floatingActionButtonConfig](/api-reference/50%20Common/Object%20Structures/globalConfig/floatingActionButtonConfig '/Documentation/ApiReference/Common/Object_Structures/globalConfig/floatingActionButtonConfig/').[position](/api-reference/50%20Common/Object%20Structures/globalConfig/floatingActionButtonConfig/position.md '/Documentation/ApiReference/Common/Object_Structures/globalConfig/floatingActionButtonConfig/#position') property in the [globalConfig](/api-reference/50%20Common/Object%20Structures/globalConfig '/Documentation/ApiReference/Common/Object_Structures/globalConfig/') object.

Refer to the following GitHub repository for the code that configures the example above and illustrates the described techniques: <a href="https://github.com/DevExpress-Examples/getting-started-with-floating-action-button/tree/main/single-action" target="_blank">getting-started-with-floating-action-button/single-action</a>.