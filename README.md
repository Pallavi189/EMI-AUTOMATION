EMI Payment Reminder Automation using n8n
Project Overview

This project automates EMI payment reminders for students. The workflow reads student fee details from Google Sheets, checks whose EMI is due today, and sends a personalized reminder email using Gmail. The uploaded workflow uses Google Sheets, JavaScript Code Node, IF Node, Gmail Node, Manual Trigger, and Schedule Trigger.

Problem Statement

Manually checking EMI due dates and sending payment reminders to students is repetitive and time-consuming. It can also lead to missed reminders and payment delays. This project solves the problem by automating the complete reminder process.

Objective

The main objective is to automatically identify students whose EMI is due today and send them a payment reminder email without manual effort.

Tools Used
Tool	Purpose
n8n	Workflow automation
Google Sheets	Store student EMI details
JavaScript Code Node	Check due dates and filter students
IF Node	Verify if EMI records are found
Gmail Node	Send reminder emails
Schedule Trigger	Run workflow automatically every day
Workflow Process
Schedule / Manual Trigger
↓
Read student data from Google Sheets
↓
Check EMI due date using JavaScript
↓
Filter students whose due date is today
↓
If matching students exist
↓
Send EMI reminder email through Gmail
Email Reminder Includes

The email contains:

Student Name
Student ID
Due Amount
Due Date
Payment Reminder Message
Certisured Team Signature
Benefits

This workflow helps reduce manual work, avoid missed payment reminders, improve follow-up efficiency, and manage student EMI payments in a simple automated way.

Future Improvements

You can improve this project by adding payment status tracking, reminder logs, WhatsApp reminders, overdue alerts, and daily admin summary reports.

Conclusion

The EMI Payment Reminder Automation project is a practical n8n workflow that helps institutes automatically manage student EMI follow-ups using Google Sheets and Gmail.
