# How to programmatically expand the root nodes in WinForms TreeView

This session explains how to programmatically expand the root nodes in [WinForms TreeView](https://help.syncfusion.com/windowsforms/treeview/overview) (TreeViewAdv)?

You can expand the [Root](https://help.syncfusion.com/cr/windowsforms/Syncfusion.Windows.Forms.Tools.TreeViewAdv.html#Syncfusion_Windows_Forms_Tools_TreeViewAdv_Root) nodes of the [TreeViewAdv](https://help.syncfusion.com/cr/windowsforms/Syncfusion.Windows.Forms.Tools.TreeViewAdv.html) by using the [Expand](https://help.syncfusion.com/cr/windowsforms/Syncfusion.Windows.Forms.Tools.TreeNodeAdv.html#Syncfusion_Windows_Forms_Tools_TreeNodeAdv_Expand) method of the node.

``` csharp
TreeNodeAdv root = this.treeViewAdv1.Root;
foreach (TreeNodeAdv node in root.Nodes)
{
    // Call the Expand method on each root node.
    node.Expand();
}
root.Expand();
```

![How to programmatically expand the root nodes in WinForms TreeView](https://www.syncfusion.com/uploads/user/kb/wf/wf-28805/wf-28805_img1.png)