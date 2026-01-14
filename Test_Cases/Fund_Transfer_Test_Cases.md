TS-01: Verify fund transfer with sufficient balance

TC-01.1 Successful fund transfer

Precondition
1.User is logged in
2.Beneficiary is added
3.Account has sufficient balance

Steps
1.Navigate to Fund Transfer page
2.Select beneficiary
3.Enter valid amount

Click Transfer
1.Enter valid OTP
2.Confirm transaction

Expected Result
1.Transaction is successful
2.Success message displayed
3.Reference number generated

TS-02: Verify fund transfer with insufficient balance

TC-02.1 Insufficient balance validation

Steps
1.Select beneficiary
2.Enter amount greater than available balance
3.Click Transfer

Expected Result
1.Error message shown: “Insufficient balance”
2.Transfer is blocked

TS-03: Verify fund transfer exceeding daily limit

TC-03.1 Daily limit validation

Steps
1.Enter amount exceeding daily limit
2.Attempt fund transfer

Expected Result
1.Error message shown
2.Transfer not processed

TS-04: Verify fund transfer without selecting beneficiary

TC-04.1 Beneficiary mandatory validation

Steps
1.Navigate to fund transfer
2.Do not select beneficiary
3.Enter amount
4.Click Transfer

Expected Result
1.Validation message displayed
2.User cannot proceed

TS-07: Verify fund transfer with valid OTP

TC-07.1 OTP success

Steps
1.Perform fund transfer
2.Enter valid OTP

Expected Result
1.OTP accepted
2.Transaction successful

TS-08: Verify fund transfer with invalid OTP

TC-08.1 OTP failure

Steps
1.Perform fund transfer
2.Enter invalid OTP
3.Expected Result
4.Error message shown
5.Transaction failed

TS-12: Verify transaction reference number generation

TC-12.1 Reference number validation

Expected Result
1.Unique transaction reference number generated
2.Reference visible in confirmation screen

TS-13: Verify account balance update after successful transfer

TC-13.1 Balance update

Expected Result
1.Balance reduced by transferred amount
2.Updated balance visible on dashboard



