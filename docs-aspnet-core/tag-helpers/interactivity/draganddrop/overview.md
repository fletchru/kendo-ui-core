---
title: Overview
page_title: DragAndDrop Overview | Telerik UI for ASP.NET Core Tag Helpers
description: "Learn the basics when working with the Telerik UI Drag-and-Drop tag helper for ASP.NET Core (MVC 6 or ASP.NET Core MVC)."
previous_url: /aspnet-core/helpers/dragdrop, /aspnet-core/helpers/tag-helpers/dragdrop
slug: taghelpers_dragdrop_aspnetcore
position: 1
---

# DragAndDrop Tag Helper Overview

The Telerik UI DragAndDrop tag helper for ASP.NET Core is a server-side wrapper for the Kendo UI DragAndDrop widget.

The `kendoDraggable` and the `kendoDropTarget` combine together to enable the implementation of the drag-and-drop scenarios.

## Initializing the Drag-and-Drop

The following example demonstrates how to define the Drag and Drop by using the DragAndDrop tag helper.

      <div id="droptarget" class="k-header"
           kendo-droptarget="true"
           on-kendo-dragenter="droptargetOnDragEnter"
           on-kendo-dragleave="droptargetOnDragLeave"
           on-kendo-drop="droptargetOnDrop" >Drag the small circle here.</div>
      <div id="draggable"
           kendo-draggable="true"
           kendo-hint="draggableHint"
           on-kendo-dragstart="draggableOnDragStart"
           on-kendo-dragend="draggableOnDragEnd"></div>

## See Also

* [JavaScript API Reference of the Drag-and-Drop](https://docs.telerik.com/kendo-ui/api/javascript/ui/treeview/configuration/draganddrop)
