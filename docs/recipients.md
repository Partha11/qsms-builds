---
title: Recipient Management
layout: default
nav_order: 4
---

# Recipient Management (CSV Import) in QSMS

Effective SMS campaigns rely on well-managed recipient lists. QSMS simplifies this process by allowing you to easily import your contact numbers directly from CSV (Comma Separated Values) files. This page will guide you through preparing your CSV file and importing it into QSMS.

#### What is a CSV File?

A CSV file is a plain text file that uses commas to separate values. Each line in the file represents a record (e.g., one recipient), and each value within that line is a field (e.g., phone number, name). It's a universal format for tabular data.

## Preparing Your CSV File for Import

Before importing, it's crucial to ensure your CSV file is correctly formatted. This helps QSMS accurately read your data and associate it with your recipients.
Essential Data Fields:

Your CSV file must contain a column for the recipient's phone number. Fields other than phone number will be ignored.

{: .note }
Future updates may include additional fields for name, email, and other contact details.

## CSV Formatting Guidelines

- **Header Row:** Your CSV file must include a header row as the very first line, defining the names of each column. The column headers must be in snake case (e.g., "phone_number," "name," "email," etc.).
- **Delimiter:** Use a comma (,) as the field delimiter.
- **Encoding:** Ensure your CSV file is saved with UTF-8 encoding. This helps prevent issues with special characters or non-English names.
- **No Blank Rows:** Avoid including empty rows within your CSV file.

### Example CSV Structure:

| phone_number       | name               | email                    |
|:-------------------|:-------------------|:-------------------------|
| +8801712345678     | Rahat Hossain      | rahat.hossain@dhaka.com  |
| +8801911122233     | Farzana Akter      | farzana@chattogram.net   |
| +8801819988776     | Mehedi Hasan       | mehedi.khulna@mail.com   |
| +8801555123456     | Nusrat Jahan       | nusrat.sylhet@email.com  |

## Importing Your CSV File into QSMS

Once you've prepared your CSV file, it's time to import it into QSMS. You can simply upload the numbers during the [SMS Campaign](/campaigns.html#creating-your-first-sms-campaign) creation process. The future updates will include the feature to upload the csv file outside the campaign creation process, to provide better control over the customer management.

## Troubleshooting Common Import Issues

- **Invalid Phone Number:** Ensure all numbers include the correct country code and contain only digits (no spaces, hyphens, or parentheses).
- **Incorrect Delimiter:** Double-check that your file is indeed using commas (,) as separators.
- **Encoding Problems:** If you see strange characters after import, your CSV might not be saved in UTF-8 encoding. Re-save the file with UTF-8.
- **File Size Limits:** While rare for contact lists, be aware of any potential file size limits within the app if you have extremely large datasets.

By following these guidelines, you can efficiently manage your recipient lists in QSMS and ensure your messages reach the right audience.