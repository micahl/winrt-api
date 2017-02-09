---
-api-id: P:Windows.UI.Xaml.Controls.ListViewBase.IncrementalLoadingTrigger
-api-type: winrt property
---

<!-- Property syntax
public Windows.UI.Xaml.Controls.IncrementalLoadingTrigger IncrementalLoadingTrigger { get;  set; }
-->

# Windows.UI.Xaml.Controls.ListViewBase.IncrementalLoadingTrigger

## -description
Gets or sets a value that indicates the conditions for prefetch operations by the [ListViewBase](listviewbase.md) class.

## -xaml-syntax
```xaml
<listViewBase IncrementalLoadingTrigger="None" />
-or-
<listViewBase IncrementalLoadingTrigger="Edge" />
```


## -property-value
An enumeration value that indicates the conditions that trigger prefetch operations. The default is **Edge**.

## -remarks

## -examples

## -see-also
[DataFetchSize](listviewbase_datafetchsize.md), [IncrementalLoadingThreshold](listviewbase_incrementalloadingthreshold.md), [LoadMoreItemsAsync](listviewbase_loadmoreitemsasync.md), [Using virtualization with a list or grid](http://msdn.microsoft.com/library/c6f8727a-2a3a-4f0d-9a5a-82780994839f)