<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/2DOverlappedRangeBarChart/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/2DOverlappedRangeBarChart/MainWindow.xaml))
<!-- default file list end -->
# How to create a 2D Overlapped Range Bar chart

The following example demonstrates how to create a [2D Overlapped Range Bar](https://docs.devexpress.com/WPF/10633/controls-and-libraries/charts-suite/chart-control/fundamentals/series-fundamentals/2d-series-types/bar-series/overlapped-range-bar?p=netframework) chart.

### Description

To do this, it is necessary to assign the [ChartControl.Diagram](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.ChartControl.Diagram?p=netframework) property to [XYDiagram2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.XYDiagram2D?p=netframework), and then add two [RangeBarOverlappedSeries2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.RangeBarOverlappedSeries2D?p=netframework) with points to the diagram's [Series](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.Diagram.Series?p=netframework) collection. 

Also, this example shows how to add a [chart title](https://docs.devexpress.com/WPF/7844/controls-and-libraries/charts-suite/chart-control/chart-elements/chart-titles) and to hide markers and [labels](https://docs.devexpress.com/WPF/6341/controls-and-libraries/charts-suite/chart-control/chart-elements/series/series-point-labels) for both series to improve chart appearance.
