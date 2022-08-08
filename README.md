# Excel-Determining-Potential-Outcomes-Using-Data-Table
Create a one-variable data table to calculate the projected change in sales.
  Verify that the Sales worksheet is selected and that cell B5 is selected.
  Enter the formula =B3+(B3*B4)
  This formula determines the projected sales for the next year.
  The B3*B4 portion of the formula multiplies the previous year's sales (B3, or $1,560,000) by the projected increase in sales (B4, or 1.50%) to determine the projected increase in sales for the next year.
  The previous year's sales (B3) is added to the projected increase in sales to obtain the next year's total projected sales.
  Select cell C8 and enter the formula =B5
  This essentially copies the projected sales for the next year down to the Projected Change data table, where it can provide the basis for performing what-if analysis.
  Select the range B8:C17 and select Data→What-If Analysis→Data Table.
  In the Data Table dialog box, select the Column input cell field. Then, in the worksheet, select cell B4.
  Note: Excel automatically treats cell B4 as an absolute reference.
  Select OK, and verify the data table replaced the percentages in the formula creating the projected change of percentage rate.
Create a two-variable data table to calculate the projected change in sales and expenses.
  Select the Expenses worksheet.
  Verify that cell B6 is selected and enter the formula =B3+(B3*B4)-(B3*B5)
  To calculate the projected income for the next year, the previous year's sales are added to the projected increase in sales, and the projected expenses are subtracted.
  The projected increase in sales for the next year is calculated by multiplying the previous year's sales (B3, or $1,560,000) by the projected increase (B4, or 1.50%)
  The next year's projected expenses are calculated by multiplying the previous year's sales (B3, or $1,560,000) by the projected expense rate for the next year (B5, or 10%).
  Select cell B9 and enter the formula =B6
  Select the range B9:G18 and select Data→What-If Analysis→Data Table.
  In the Data Table dialog box, select the Row input cell field and select cell B5.
  In the Column input cell field, select cell B4.
  Select OK and verify that the data table replaced the percentages in the formula for both projected increase and projected expenses.
