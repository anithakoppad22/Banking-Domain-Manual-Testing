📄 Software Requirement Specification (SRS)
Banking Application – Fund Transfer Module
1. Introduction
1.1 Purpose

This document defines the software requirements for the Fund Transfer module of a Banking Application.
It serves as the primary reference for test planning, test scenario creation, test case design, and defect validation.

1.2 Intended Audience

Manual Test Engineers

QA Analysts

Business Analysts

Project Stakeholders

2. Scope

The Fund Transfer module enables customers to securely transfer funds from their bank account to another account using registered beneficiaries and OTP authentication.

This document covers:

Beneficiary management

Fund transfer flow

System validations

Transaction confirmation

3. System Overview

The Banking Application is a web-based system that allows customers to perform banking operations online.
The Fund Transfer module ensures secure, reliable, and accurate transfer of funds between accounts.

4. Definitions, Acronyms, and Abbreviations
Term	Description
OTP	One Time Password
IFSC	Indian Financial System Code
Beneficiary	Recipient of funds
Transaction ID	Unique reference number
5. User Roles
Role	Description
Customer	User who performs fund transfer
System	Banking application
6. Functional Requirements
FR-1: User Login

The user must log in with valid credentials

The system shall display an error message for invalid login

The account shall be locked after multiple failed attempts

FR-2: Add Beneficiary

The user shall be able to add a beneficiary using:

Beneficiary Name

Account Number

IFSC Code

The system shall validate beneficiary details

OTP verification is mandatory for beneficiary addition

FR-3: View Beneficiary List

The system shall display all registered beneficiaries

Only approved beneficiaries shall be available for fund transfer

FR-4: Fund Transfer

The user shall be able to transfer funds to a registered beneficiary

The user shall enter:

Transfer amount

Optional remarks

The system shall validate:

Available balance

Daily transaction limit

OTP verification is mandatory to complete the transfer

FR-5: Transaction Confirmation

The system shall display a success message for successful transactions

The system shall display an appropriate error message for failed transactions

A unique transaction reference number shall be generated

FR-6: Transaction History

The system shall allow users to view past transactions

Transaction details shall include:

Date

Amount

Status

Reference number

7. Non-Functional Requirements
ID	Requirement
NFR-1	System response time shall be less than 3 seconds
NFR-2	Data shall be encrypted during transmission
NFR-3	OTP shall expire within 2 minutes
NFR-4	System shall be available 24/7
NFR-5	System shall support concurrent users
8. Business Rules

Fund transfer is allowed only to registered beneficiaries

OTP authentication is mandatory for all transactions

Transfers exceeding available balance shall be rejected

Daily transaction limits are defined by the bank

9. Assumptions and Constraints
Assumptions

User has an active bank account

Mobile number is registered for OTP

Internet connection is available

Constraints

OTP delivery depends on telecom network

Transaction limits are configured by the bank

10. Out of Scope

International fund transfers

Loan payments

Credit card payments

Account opening functionality

11. Approval

This SRS document serves as the baseline for test case creation and execution for the Fund Transfer module of the Banking Application.