# How to build non-linear layout via LayoutControl 


<p>This example shows how to arrange items within a LayoutControl, forming a non-linear layout. To create a layout, items are combined into groups and the groups are combined into other groups.</p><p>Various group visual styles are demonstrated. Group 1 is rendered using the GroupBox visual style (the View property is set to GroupBox), which allows a header to be displayed. There is also a group that represents items as tabs (its View property is set to Tabs). Other groups are painted without a header and borders.</p><p>For Group 1, the collapsing feature is enabled via the LayoutGroup.IsCollapsible property, allowing an end-user to collapse the group's contents.</p><p>For the tabbed group and the group that displays Item 2 and Item 3, horizontal sizing is enabled via the LayoutControl.AllowHorizontalSizing attached property. Vertical sizing is enabled for Item 4 via the LayoutControl.AllowVerticalSizing attached property.</p><p>For items 1, 2, 3, 4 and 6, the VerticalAlignment property is set to Stretch. These items are stretched when the LayoutControl's height is changed. For Item 9 and Item 11, the HorizontalAlignment property is set to Left and Right, respectively. These items have a fixed width and are not stretched when the LayoutControl's width is changed.</p>

<br/>


