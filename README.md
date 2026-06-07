# W11 THM Phishing Email in Action
## Task 2: Cancel Your Order
### (i) Who is listed as the Merchant in the email body?

The email body was examined to identify transaction details. The merchant information was clearly displayed within the email content, showing the name "Amazing Stuff".

```bash
Amazing Stuff
```
<img width="570" height="202" alt="image" src="https://github.com/user-attachments/assets/8c171715-8295-4ec5-999c-45f9060f4202" />


## Task 3: Track Your Package
<img width="1212" height="470" alt="image" src="https://github.com/user-attachments/assets/796c09fd-350f-46af-809a-d59d140dee43" />

### (i) What root domain does the hyperlink in the above example point to?
### Be sure to defang the URL.

The HTML source code was inspected and the hyperlink destination was identified from the URL specified within the anchor (<a>) tag. The URL pointed to devret.xyz, which was extracted as the root domain and then defanged to devret[.]xyz.

```bash
devret[.]xyz
```
<img width="940" height="612" alt="image" src="https://github.com/user-attachments/assets/f6e7e760-8d0e-4615-a230-ef3a2142c185" />

## Task 4: Download Document Here
### (i) The attacker deployed a fake portal to capture and exfiltrate user credentials.
### What is this type of attack called?

The email scenario was analyzed to determine the attacker's objective. Since the fake portal was designed to collect user credentials, the attack was identified as Credential Harvesting.

```bash
Credential Harvesting
```

## Task 5: Your Account is on Hold
### (i) What is the actual sender email address hidden behind the Netllx billing display name?

The sender details were inspected to reveal the actual email address behind the display name. The hidden sender address was identified as z99@musacombi.online.

```bash
z99@musacombi.online
```
<img width="1656" height="472" alt="image" src="https://github.com/user-attachments/assets/d6c89d2e-5562-432d-8c1f-15fdb965002b" />

## Task 6: Your Recent Purchase 
### (i) What does the acronym BCC stand for?

The email terminology discussed in the lesson was reviewed. BCC was identified as Blind Carbon Copy, a feature that allows recipients to receive a copy of an email without other recipients seeing their address.

``` bash
Blind Carbon Copy
```

### (ii) What is the file extension of the attachment?

The attachment name was inspected and the file extension was examined. The attachment was identified as a Microsoft Word template file with the .dot extension.

```bash
.dot
```
<img width="267" height="197" alt="image" src="https://github.com/user-attachments/assets/4251e0d6-3c91-4b47-afa0-3bd2dc4d70f0" />

## Task 7: 
### (i) What is the name of the executable that the Excel attachment attempts to run?

The malicious Excel attachment was analyzed to determine its behavior. Examination of the embedded macro revealed that it attempted to execute the file regasms.exe.

```bash
regasms.exe
```
<img width="555" height="270" alt="image" src="https://github.com/user-attachments/assets/0014c855-8684-4740-8d35-eaec46486e20" />



