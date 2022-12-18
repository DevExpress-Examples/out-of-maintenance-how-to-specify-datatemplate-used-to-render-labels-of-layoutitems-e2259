<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128654379/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E2259)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/LabelTemplate_Ex/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/LabelTemplate_Ex/MainWindow.xaml))
<!-- default file list end -->
# How to: Specify DataTemplate used to render labels of LayoutItems


<p>The following code shows how to specify a DataTemplate used to render a label in a custom manner. In the example, the DataTemplate displays a colon after the label's text.</p>
<p>The DataTemplate is assigned to the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfLayoutControlLayoutItem_LabelTemplatetopic">LayoutItem.LabelTemplate</a> property. The template is provided via the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfLayoutControlLayoutGroup_ItemStyletopic">LayoutGroup.ItemStyle</a> property of the LayoutControl, so it's applied to all layout items.</p>

<br/>


