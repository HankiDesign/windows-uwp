﻿---
Description: The Payout summary shows you details about the money you’ve earned with your apps and add-ons. It also lets you know when you’ll receive payments and how much you'll be paid.
title: Payout summary
ms.assetid: F0D070BE-8267-4CC9-B0D2-085EBA74AC98
ms.date: 10/31/2018
ms.topic: article
keywords: windows 10, uwp, payout summary, statement, payments, earnings, payouts, payment, proceeds
ms.localizationpriority: medium
---

# Payout summary

The **Payout summary** shows you details about the money you’ve earned with Microsoft. It also lets you know when you’ll receive payments and how much you'll be paid.

If you sell products in the Azure Marketplace, you’ll also see info on successful payouts in the **Payout summary**. For more details regarding Azure Marketplace payment, see the [Microsoft Azure Marketplace Participation Policies](https://go.microsoft.com/fwlink/p/?LinkId=722436) and the [Microsoft Azure Marketplace Publisher Agreement](https://go.microsoft.com/fwlink/p/?LinkID=699560 ).

> [!NOTE]
> To be eligible for payout, your proceeds must reach the [payment threshold](payment-thresholds-methods-and-timeframes.md) of $50. For details about the payment threshold see this page and review the app developer agreement.

## Access the payout summary pages

To open one of the payout summary pages:

1. Select the Money icon in the upper-right corner.
2. Select Payments, Transaction history, or Export data.

## Payments page

The totals on this page represent all of the programs you participate in. You can filter by Participant ID, Program, Payment ID, and Earning type. Amounts are given in US dollars. The paid value is also displayed in pay to currency.

| Area                   | Description                                                                                  |
|------------------------|----------------------------------------------------------------------------------------------|
| Total paid this year   | The combined total paid out to you this year, in US dollars, for all of your programs.       |
| Next estimated payment | The single next payment coming to you (even if there are others coming soon), in US dollars. |
| Last payment           | The amount (in US dollars), program name, and program of your most recent payment.           |
| Payments by source     | Amount of payments, in US dollars, represented by program over the last 12 months.           |
| Payments               | Select Paid or Pending and then sort as you like. For additional details of a specific payment select View. To download a copy of the payment remittance statement, select Download. Note that transaction history data may take up to 24 hours to appear, so you may not see associated earnings right away. |

To export any of the data on this page, select Export and then follow directions on the Export data page.

## Transaction history page

This page displays all of your individual earnings, including the date, type, and earning for each. You can select a time period to view, and you can also filter by Enrollment ID, Program, Payment ID, Earning type, Lever, and Status. Data is available for the current fiscal year (July 1 – June 30) and the previous two fiscal years.

To see more details about an earning, select the down arrow at the right-hand side of the page. This will display the lever, revenue amount, and product. If for some reason any of this data is unavailable, but you need access to it, contact [support](https://developer.microsoft.com/en-us/windows/support)]. If the earning is the result of an adjustment, and not a transaction, the product fields will not be displayed.

To export any of the transaction data on this page, select Export and then follow directions on the Export data page. Files exported from the Transaction History page show data in transaction currency, earnings in both transaction currency and US dollars,and the paid value in pay to currency.

## Payment status

| Earning status           | Reason                                                                                                                                      | Partner action required?                                   |
|--------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------|
| Unprocessed              | The earning is eligible for payment. It stays in this state for a cooling period as defined in the program guide for the Incentive program. | No                                                         |
| Upcoming                 | Payment order generated pending internal reviews before payment is processed.                                                               | No                                                         |
| Pending tax invoice      | Your tax invoice is incomplete or invalid.                                                                                                  | You need to update your tax invoice before you can be paid |
| Rejected during review   | The payment was rejected during review.                                                                                                     | Contact [Microsoft support](https://developer.microsoft.com/en-us/windows/support) for details                      |
| Failed                   | The payment failed due to a Microsoft system error.                                                                                         | Contact [Microsoft support](https://developer.microsoft.com/en-us/windows/support)  for details                      |
| In progress              | The payment is in progress.                                                                                                                 | No                                                         |
| Incorrect payment        | The payment recouping is in progress.                                                                                                       | No                                                         |
| Sent                     | The payment has been sent to your bank.                                                                                                     | No                                                         |
| Reprocessing             | The payment encountered a Microsoft system error and is being reprocessed.                                                                  | No                                                         |
| Reversed                 | The payment was reversed by your bank and will be sent again in the next payment cycle.                                                     | No                                                         |
| Tax invoice rejected     | Your tax invoice was rejected during review. All pending payments will be on hold until the tax invoice review is complete.                 | Contact [Microsoft support](https://developer.microsoft.com/en-us/windows/support)  for details                      |
| Tax invoice under review | Your tax invoice is being reviewed. Your payment will be released once the tax invoice has been approved.                                   | No                                                         |
| Rejected                 | The payment was rejected by your bank.                                                                                                      | Contact your bank for details.                             |

## Export data page

Follow the instructions on this page to export the data you want.

Notes:

- When you access this page from either the Payments or Transaction history page, your filters do not carry through. You’ll need to redo them on the Export data page.
- The Export data page does not refresh on its own. You may need to refresh the page manually to see the most recent data.
- Your filter may result in a No data available error. This probably means you’ve left the default time period selected at three months, and then selected a Payment ID from an earning that’s outside of that period. Expand your time period and try again.

## Payment download export

This option provides a download of the payments you received in your bank for a given program, the associated tax, and aggregated earning amount. This report is used for many Partner Center programs, so some columns may be inapplicable to your report. Those columns are marked below.

| Column name              | Description                                                                                                                             |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| participantID            | The primary identity of the partner earning under the program                                                                           |
| participantIDType        | Usually program id for Incentive programs and Seller ID for Store programs                                                              |
| participantName          | Name of the earning partner                                                                                                             |
| programName              | Incentive/store program name                                                                                                            |
| earned                   | Amount earned in the Pay To currency for that program/participantID                                                                     |
| earnedUSD                | Amount earned for the program/participant ID, in USD                                                                                    |
| withheldTax              | Amount of tax withheld in the Pay To currency for the program/participantID                                                             |
| salesTax                 | Total amount of sales tax in the Pay To currency for the program/participantID                                                          |
| totalPayment             | Total payment in local currency excluding the withholding tax and including the sales tax (if applicable) for the program/participantID |
| currencyCode             | Pay To currency code                                                                                                                    |
| paymentMethod            | The method used to pay the partner (electronic bank transfer, credit note)                                                              |
| paymentID                | Unique identifier for the payment. This number is usually visible in your bank statement.                                               |
| paymentStatus            | Payment status                                                                                                                          |
| paymentStatusDescription | Friendly description of payment status                                                                                                  |
| paymentDate              | Date payment was sent from Microsoft                                                                                                    |

## Transaction history download export

This option provides a download of each earning line item you see in the Transaction history page, earning type, date, associated transaction amount, customer, product, and other transactional details applicable to your programs.

| Column name                    | Description                                                                                                                              |
|--------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| earningId                      | Unique identifier for each earning                                                                                                       |
| participantId                  | The primary identity of the partner earning under the program                                                                            |
| participantIdType              | Seller ID                                                                                                                                |
| participantName                | Name of the earning partner                                                                                                              |
| partnerCountryCode             | Location/country of the earning partner                                                                                                  |
| programName                    | Incentive/store program name                                                                                                             |
| transactionId                  | Unique identifier for the transaction                                                                                                    |
| transactionCurrency            | Currency in which the original customer transaction occurred                                                                             |
| transactionDate                | Date of the transaction. Useful for programs where many transactions contribute to one earning                                           |
| transactionExchangeRate        | Exchange rate date used to show the corresponding USD amount                                                                             |
| transactionAmount              | Transaction amount in the original transaction currency based on which earning is generated                                              |
| transactionAmountUSD           | Transaction amount in USD                                                                                                                |
| lever                          | Indicates business rule for the earning                                                                                                  |
| earningRate                    | Incentive rate applied on transaction amount to generate an earning                                                                      |
| quantity                       | Varies based on program. Indicates billed quantity for transactional programs                                                            |
| earningType                    | Indicates if it is fee, rebate, coop, sell etc.                                                                                          |
| earningAmount                  | Earning Amount in the original transaction currency                                                                                      |
| earningAmountUSD               | Earning Amount in USD                                                                                                                    |
| earningDate                    | Date of the earning                                                                                                                      |
| calculationDate                | Date the earning was calculated in the system                                                                                            |
| earningExchangeRate            | Exchange rate used to show the corresponding USD amount                                                                                  |
| exchangeRateDate               | Exchange rate date used to calculate EarningAmount USD                                                                                   |
| claimId                        | Will always be blank                                                                                                                     |
| paymentId                      | Unique identifier for the payment. This number is usually visible in your bank statement                                                 |
| paymentStatus                  | Payment status                                                                                                                           |
| paymentStatusDescription       | Friendly description of payment status                                                                                                   |
| customerId                     | Will always be blank                                                                                                                     |
| customerName                   | Will always be blank                                                                                                                     |
| partNumber                     | Will always be blank                                                                                                                     |
| productName                    | Product name linked to transaction                                                                                                       |
| productId                      | Unique product identifier                                                                                                                |
| parentProductId                | Unique parent product identifier. Please note: if there isn’t a parent product for the transaction, then Parent Product ID = Product ID. |
| parentProductName              | Name of the parent product. Please note: if there isn’t a parent product for the transaction, then Parent Product Name = Product Name.   |
| productType                    | Type of product (such as App, Add-on, Game, etc.)                                                                                        |
| invoiceNumber                  | Will always be blank                                                                                                                     |
| subscriptionId                 | Will always be blank                                                                                                                     |
| subscriptionStartDate          | Will always be blank                                                                                                                     |
| subscriptionEndDate            | Will always be blank                                                                                                                     |
| resellerId                     | Will always be blank                                                                                                                     |
| resellerName                   | Will always be blank                                                                                                                     |
| distributorId                  | Will always be blank                                                                                                                     |
| distributorName                | Will always be blank                                                                                                                     |
| agreementNumber                | Will always be blank                                                                                                                     |
| agreementStartDate             | Will always be blank                                                                                                                     |
| agreementEndDate               | Will always be blank                                                                                                                     |
| workload                       | Will always be blank                                                                                                                     |
| transactionType                | Type of transaction (such as purchase, refund, reversal, chargeback, etc.)                                                               |
| localProviderSeller            | Local provider/seller of record                                                                                                          |
| taxRemitted                    | Amount of tax remitted (sales, use, or VAT/GST taxes).                                                                                   |
| taxRemitModel                  | Party responsible for remitting taxes (sales, use, or VAT/GST taxes).                                                                    |
| storeFee                       | The amount retained by Microsoft as a fee for making the app or add-on available in the Store.                                           |
| transactionPaymentMethod       | Customer payment instrument used for the transaction (such as Card, Mobile Carrier Billing, PayPal, etc.)                                |
| tpan                           | Indicates the third-party ad network                                                                                                     |
| purchaseTypeCode               | Will always be blank                                                                                                                     |
| purchaseOrderType              | Will always be blank                                                                                                                     |
| purchaseOrderCoverageStartDate | Will always be blank                                                                                                                     |
| purchaseOrderCoverageEndDate   | Will always be blank                                                                                                                     |
| externalReferenceId            | Will always be blank                                                                                                                     |
| externalReferenceIdLabel       | Will always be blank                                                                                                                     |

## Payout Statement download export (legacy)

For a limited time in the old payout summary page, payout statements will be available for download. That report contains the following fields.

> [!NOTE]
> Legacy transaction history has a column called "Reserved" which corresponds to the "Earnings" column in the modern history, except that it excludes all earnings with status = "Payment Sent".

| Field name              | Description                                                                                                                                                             |
|-------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Revenue Source          | The source of your revenue, based on where the transaction occurred (such as Microsoft Store, Windows Phone Store, Windows Store 8, advertising, etc.)                  |
| Order ID                | Unique order identifier. This ID allows you to identify purchase transactions with their respective non-purchase transactions (such as refunds, chargebacks, etc.). Both will have the same Order ID. Also, in the case of a split charge, where multiple payment methods were used for a single purchase, it will allow you to link the purchase transactions. |
| Transaction ID          | Unique transaction identifier.                                                                                                                                          |
| Transaction Date Time   | The date and time the transaction occurred (UTC).                                                                                                                       |
| Parent Product ID       | Unique parent product identifier. Please note: if there isn’t a parent product for the transaction, then Parent Product ID = Product ID.                                |
| Product ID              | Unique product identifier.                                                                                                                                              |
| Parent Product Name     | Name of the parent product. Please note: if there isn’t a parent product for the transaction, then Parent Product Name = Product Name.                                  |
| Product Name            | Name of the product.                                                                                                                                                    |
| Product Type            | Type of product (such as App, Add-on, Game, etc.)                                                                                                                       |
| Quantity                | When the Revenue Source is Microsoft Store for Business, the Quantity represents the number of licenses purchased. For all other Revenue Sources, the Quantity will always be 1. Note: even when a single transaction is split into two line items because two different payment methods were used, each line item will show a Quantity of 1. |
| Transaction Type        | Type of transaction (such as purchase, refund, reversal, chargeback, etc.)                                                                                              |
| Payment Method          | Customer payment instrument used for the transaction (such as Card, Mobile Carrier Billing, PayPal, etc.)                                                               |
| Country / Region        | Country/region where the transaction occurred.                                                                                                                          |
| Local Provider / Seller | Local provider/seller of record.                                                                                                                                        |
| Transaction Currency    | Currency of the transaction.                                                                                                                                            |
| Transaction Amount      | Amount of the transaction.                                                                                                                                              |
| Tax Remitted            | Amount of tax remitted (sales, use, or VAT/GST taxes).                                                                                                                  |
| Net Receipts            | Transaction amount less tax remitted.                                                                                                                                   |
| Store Fee               | The percentage of Net Receipts retained by Microsoft as a fee for making the app or add-on available in the Store.                                                      |
| App Proceeds            | Net receipts minus the Store Fee.                                                                                                                                       |
| Taxes Withheld          | Amount of income tax withheld. (Not included in **Reserved** .csv file.)                                                                                                |
| Payment                 | App Proceeds less any applicable income tax withholding (amount shown in Transaction Currency). (Not included in **Reserved** .csv file.)                               |
| FX Rate                 | Foreign exchange rate used to convert Transaction Currency to Payment Currency.                                                                                         |
| Payment Currency        | Currency your payment is made in.                                                                                                                                       |
| Converted Payment       | Payment amount converted to Payment Currency using the FX Rate.                                                                                                         |
| Tax Remit Model         | Party responsible for remitting taxes (sales, use, or VAT/GST taxes).                                                                                                   |
| Eligibility Date Time   | The date and time when transaction proceeds become eligible for payout (UTC). When a payout is created, it includes transaction proceeds which have an Eligibility Date Time prior to the payout creation date. (Only included in **Reserved** .csv file.) |
| Charges                 | Shows a breakdown of all the charge details aggregated in the Transaction Amount column. (Only included for Azure Marketplace; not included in **Reserved** .csv file.) |
