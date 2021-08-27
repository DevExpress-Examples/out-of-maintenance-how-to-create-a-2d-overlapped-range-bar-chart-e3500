<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128569069/11.2.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E3500)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/2DOverlappedRangeBarChart/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/2DOverlappedRangeBarChart/MainWindow.xaml))
<!-- default file list end -->
# How to create a 2D Overlapped Range Bar chart

The following example demonstrates how to create a [2D Overlapped Range Bar](https://docs.devexpress.com/WPF/10633/controls-and-libraries/charts-suite/chart-control/fundamentals/series-fundamentals/2d-series-types/bar-series/overlapped-range-bar?p=netframework) chart.

### Description

To do this, it is necessary to assign the [ChartControl.Diagram](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.ChartControl.Diagram?p=netframework) property to [XYDiagram2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.XYDiagram2D?p=netframework), and then add two [RangeBarOverlappedSeries2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.RangeBarOverlappedSeries2D?p=netframework) with points to the diagram's [Series](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.Diagram.Series?p=netframework) collection. 

Also, this example shows how to add a [chart title](https://docs.devexpress.com/WPF/7844/controls-and-libraries/charts-suite/chart-control/chart-elements/chart-titles) and to hide markers and [labels](https://docs.devexpress.com/WPF/6341/controls-and-libraries/charts-suite/chart-control/chart-elements/series/series-point-labels) for both series to improve chart appearance.
