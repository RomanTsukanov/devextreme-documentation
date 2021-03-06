---
id: dxTreeMapNode.select(state)
---
---
##### shortDescription
Sets the selection state of a node.

##### param(state): Boolean
Pass **true** to select the node; **false** to deselect.

---
[note]If the [selectionMode](/api-reference/10%20UI%20Components/dxTreeMap/1%20Configuration/selectionMode.md '/Documentation/ApiReference/UI_Components/dxTreeMap/Configuration/#selectionMode') property is set to *"single"*, calling this method with **true** as the argument selects one node and deselects all the others.

To deselect all nodes at once, call the [clearSelection()](/api-reference/10%20UI%20Components/dxTreeMap/3%20Methods/clearSelection().md '/Documentation/ApiReference/UI_Components/dxTreeMap/Methods/#clearSelection') method.