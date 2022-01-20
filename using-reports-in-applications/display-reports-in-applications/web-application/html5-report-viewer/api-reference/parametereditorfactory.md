---
title: parameterEditorFactory
page_title: parameterEditorFactory | for Telerik Reporting Documentation
description: parameterEditorFactory
slug: telerikreporting/using-reports-in-applications/display-reports-in-applications/web-application/html5-report-viewer/api-reference/parametereditorfactory
tags: parametereditorfactory
published: True
position: 5
---

# parameterEditorFactory

## parameterEditorFactory


| Parameter | Type | Description |
| ------ | ------ | ------ |
| __match(parameter)__ |boolean|determines whether the editor is suitable for the passed parameter<br/>* __parameter__ |
| __createEditor(placeholder, options)__ |parameterEditor|adds the root html element for the editor, holds the logic for calling the paramerChanged callback. Returns a parameterEditor object<ul><li>__placeholder__, this is the element which the parameter editor UI is appended to</li> <li>__options__ :<ul><li> __parameterChanged__ : function(parameter, value), a callback function which should be called when the parameter’s value has been changed</li> <li>parameter, the instance of the currently edited parameter</li> <li>value, the new parameter value</li></ul></li></ul>|
