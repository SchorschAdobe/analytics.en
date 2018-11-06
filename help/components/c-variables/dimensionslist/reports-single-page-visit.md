---
description: Not to be mistaken with the Single Page Visits metric in Ad Hoc Analysis, the Single Page Visits report shows the pages your website visitors enter and exit, without taking steps to view any other pages.
seo-description: Not to be mistaken with the Single Page Visits metric in Ad Hoc Analysis, the Single Page Visits report shows the pages your website visitors enter and exit, without taking steps to view any other pages.
seo-title: Single Page Visit
solution: Analytics
title: Single Page Visit
topic: Reports
uuid: 5ca52be8-c7f5-464a-8a06-55e8271760b4
index: y
internal: n
snippet: y
---

# Single Page Visit

Not to be mistaken with the Single Page Visits metric in Ad Hoc Analysis, the Single Page Visits report shows the pages your website visitors enter and exit, without taking steps to view any other pages.

This report is most commonly used in the context of the [!UICONTROL Pages] report, however it can also be viewed in all traffic variables with [!UICONTROL pathing] enabled. You can use this report to identify entry pages that are least likely to compel a visitor to explore your site further, or to determine how many visits consist of a single page. This information lets you optimize content to reduce exits on those pages.

## Properties of Report {#section_2D30F939FE0648EF983DD7C1BAB1181B}

* An identical report can be retrieved by pulling a [!UICONTROL Pages] report, using [!UICONTROL Single Access] as a metric. 

* A single page visit is considered a visit containing one unique value, not a single image request.

    * In the context of a [pages report](../../../components/c-variables/dimensionslist/reports-pages.md#concept_0219136EA25745B58434D0C7E751D7D5), only one unique page can fire within the visit. 
    * In the context of a [site sections report](../../../components/c-variables/dimensionslist/reports-site-sections.md#concept_39E550D7A9E34C9580E81F5F9E12BDDD), a single unique site section fires within the visit. 
    * In the context of a [traffic variable](traffic_var.md#concept_E3D0FEC81E1F4987B39CC467F19FFCFF), a visit populates this report if a single unique value is fired.

* Single page visits can consist of many image requests, as long as the variable in context of the report contains a single unique value. As soon as a second unique value is populated, the visit is no longer considered a single page visit. 
* This is considered a type of pathing report. By default, the [!UICONTROL Pages] variable has pathing enabled. However, any traffic variable has this capability as well. Enabling pathing on additional traffic variables is dependent on your contract. Contact your organization's Account Manager for details. 
* This report can use a search filter to locate specific line items. 
* This report can be viewed in both [trended](reports_trended.md#concept_65FEA92704024232BB21A5952939711F) and [ranked](reports_ranked.md#concept_E1710FFFBB334F3D9DB63A1626DBCB01) formats. 

* No breakdowns are available in this report. 
* The only metric available within this report is [!UICONTROL Visits].
