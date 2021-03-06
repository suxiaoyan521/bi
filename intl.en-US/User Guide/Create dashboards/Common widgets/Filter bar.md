# Filter bar {#concept_rtm_qwb_dhb .concept}

You can use a **filter bar** to search data in one or more charts.

1.  Click a **filter bar**.
2.  Select a dataset, and select the fields to be added to the filter bar, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/155833889947578_en-US.png)


Currently, a filter bar supports filter interactions between charts of the current dataset or charts of different datasets.

**Filter interaction example for the current dataset**

1.  Select **Current Dataset**. In the current dataset field list, select the charts by the field type.
2.  Click **Style** to edit the display name of the filter bar.
3.  Click **Search** to filter the associated charts.

**Filter interaction example for different datasets**

Filter bars can also filter data from different datasets. However, in the associated items, the data members must have the same fields. Otherwise, the interaction does not work.

1.  Select a chart, such as a table.
2.  Select the required fields, and then click **Update**.
3.  Click the **Style** tab, and then change the display name and layout of the table. For example, set the display name of the table to **overseas data**.
4.  Click the icon that switches datasets to change to another dataset.
5.  Select a chart, such as Table.
6.  Select the required fields, and then click **Update**.
7.  Click the Style tab, and then change the display name and layout of the table. For example, set the display name of the table to **domestic data**.
8.  Click the **Filter Bar** icon, and then select the dataset and add filter fields to the filter bar.
9.  Select **Other Dataset**. In the Other Dataset list, select the associated items based on the field type.
10. Click the **Style** tab to specify the display name of the widget.
11. Click **Search** to update the charts filtered by the fields.

**Cascade filter example**

The filter bar supports cascade filter, which simplifies the steps of setting multiple filters.

1.  Create line charts on the dashboard editing page, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/155833889947586_en-US.png)

2.  Click the **filter bar** widget and then select the dataset and the fields to be filtered. In this example, we select the **province** field as the filter, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/155833889947587_en-US.png)

3.  Click the cascade icon. On the **Configure Field Cascade** page, click **+ Add cascading relationship** to add the fields to be cascaded, and then click **OK**. In this example, we select the **city** field and the **product type** field.

    **Note:** 

    -   The cascade filter supports three-level cascades, with lines connected between the parent nodes and child nodes.
    -   The cascade filter supports renaming the cascade fields.
    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/155833889947588_en-US.png)

4.  Click **Set Filter** to set the filters and then click **OK**. In this example, we select Tile cascade display and Multiple Select, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/155833889947589_en-US.png)

    **Note:** The cascade display supports Tree cascade display and Tile cascade display. You can select Cognate inheritance.

5.  In the search widget, click **Search**. The result is shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/155833889947590_en-US.png)

    **Note:** To view the detailed information of the cascade, you can hover over the cascade icon in the upper-right corner.


**Filter data in a date range**

When you filter data in date type, you can select the date range of the filter, manually set default values, and customize shortcuts.

1.  In the Data tab, select the dataset and the fields to be filtered, such as order date \(month\).
2.  Select a chart that needs to be filtered, and then click **Set Time Range**.
3.  In the **Set Time Range** dialog box, enable Set Time Range, specify the time range, and then click **OK**
4.  Select **Manually set default values** or **Customize shortcuts** to select a date range, and then click **OK**.

    **Note:** The date currently supports types of month and day for you to customize the date range.

5.  Click **Search**. All the charts that are filtered by the widget are updated.

**Filter text data**

When you filter data in text type, you can set the enumeration range. as shown in the following figure:

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/155833889947594_en-US.png)

1.  In the Data tab, select the dataset and fields to be filtered, such as product package.
2.  Select a chart that needs to be used, and then click **Set Value Range**.
3.  In the **Set Value Range** dialog box, enable Set Enumeration Range, click Manually set values or add available values such as **Medium ox**, **Large Box**, **Small bag**, and **Small Box**, and then click **OK**, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/155833889947595_en-US.png)

4.  Select **Filter by Enumeration** and **Multiple Select**, and then click the drop-down menu. The system automatically adds the available values of this field to the filter bar, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/155833889947596_en-US.png)

    **Note:** If you select **Sort by fixed value**, the selected values of the filter field are displayed in default order in relevant charts.

5.  Manually specify the value or select the available values for the field to be filtered, and then click **OK** \> **OK**.
6.  Click **Search**. The charts that are filtered by the filter bar are updated.

**Numeric query**

1.  On the Data tab, select a dataset and a query field, for example, order\_amt.
2.  Select a chart that needs to be filtered, set filter conditions, and click **OK**, as shown in the following figure:

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/155833890047597_en-US.png)

3.  Click **Search**. The charts that are filtered by the filter bar are updated.

