<!-- default file list -->
*Files to look at*:

* [MainPage.xaml](./CS/DXPivotGrid_Localization/MainPage.xaml) (VB: [MainPage.xaml](./VB/DXPivotGrid_Localization/MainPage.xaml))
* [MainPage.xaml.cs](./CS/DXPivotGrid_Localization/MainPage.xaml.cs) (VB: [MainPage.xaml.vb](./VB/DXPivotGrid_Localization/MainPage.xaml.vb))
<!-- default file list end -->
# How to localize PivotGridControl via the PivotGridLocalizer class


<p>The following example shows how to localize PivotGridControl via the PivotGridLocalizer class.</p><p>In this example, grand total headers ('Grand Total' by default) are replaced with 'Aggregate Total' strings, automatic total headers' patterns ('{0} Total' by default) are replaced with 'Total for {0}' strings, and the text displayed within the Filter Header Area ('Drop Filter Fields Here' by default) is replaced with 'Filter Header Area is currently empty' string. To do this, a PivotGridLocalizer class descendant (CustomDXPivotGridLocalizer) has been created, and its GetLocalizedString method has been overridden to replace the default strings.</p><br />


<br/>


