# Checkout-Invoice-PDF
This Repo contains code to produce an invoice for the Checkout Management App's Checkout Invoice record.  The Visualforce page will render the invoice as a PDF. The Visualforce email template will produce an email with attached PDF invoice that can be used in an email alert. 

Setup a custom button or link on the Checkout Invoice for the Visualforce page, and add it to Checkout Invoice page layout. Here is what the URL would look like.
```
/apex/CheckoutInvoicePDF?id={!sfcma__Invoice__c.Id}
```
