# e-parts-Inventory-Checklist
*an excel spreadsheet for electronic components management using Octopart API*

# About
the excel spreadsheet `Inventory Checklist` in the repo provides an overview of the electronic components that user has created or bought. By enter the fields in the sheet, basically only the **MPN** of a part, the Excel Add-In provided by Octopart API (now part of the Nexar API) will automatically process the request and update the supply information. In this way, user can process a bulk of parts easily without accessing too many tabs in a web browser.

[<img src="https://img.youtube.com/vi/17uxyViao2s/maxresdefault.jpg" width="60%">](https://youtu.be/17uxyViao2s)

# How to use
1. First sign up on [Nexar Portal](https://octopart.com/business/api/v4/api-transition), and create an application afterwards with the scope of `Supply`.
2. Next to install the [Nexar Supply Excel Add-In](https://github.com/NexarDeveloper/nexar-supply-excel-cs).
3. Then fill the login-in fields in the sheet (`ClientId` and `ClientSecret`). This are provided with your Nexar application.
4. (Optional) edit the distributor in the corresponding field.
5. Enter the manufacturer part number of a component under **MPN** column, the table should update the supply information of the part.
6. (Optional) duplicate the sheet tab to extend the components. For example, you may have several slots where the parts are stored, you can fill up the sheet based on this. Another idea is to sort based on the category of a part.

# Disclaimer
This is more or less the needs from myself, to dig out more features, please take a look at the [Nexar documentation](https://support.nexar.com/support/solutions/101000241561).

