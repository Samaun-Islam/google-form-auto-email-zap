# Technical Workflow Description

## 1️⃣ Google Form Fields

- Name (Short Text)
- Email (Email Field)
- Message (Paragraph Text)

## 2️⃣ Trigger Configuration

App: Google Forms  
Event: New Form Response  

The workflow is triggered every time a new response is submitted.

## 3️⃣ Action Configuration

App: Gmail  
Event: Send Email  

To: Email field from the form (dynamic mapping)  
Subject: Thank you for your submission  
Body: Personalized confirmation message

## 4️⃣ Email Template Example

Subject:
Hi {{Name}}, Thanks for Submitting!

Body:
Hello {{Name}},

Thank you for submitting the form. We have received your response successfully.

Best Regards,  
Samaun

## 5️⃣ Testing Result

The workflow was tested successfully.
Each new form submission triggers an automatic email instantly.

## 6️⃣ Limitations

- No conditional logic
- No delay feature
- No database storage
