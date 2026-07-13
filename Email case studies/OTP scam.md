# Case 1 – OTP Verification Phishing

# Objective

Analyse a phishing message attempting to steal a Google verification (OTP) code.

## Screenshot

<img width="1452" height="802" alt="Case1- OTP Scam" src="https://github.com/user-attachments/assets/dcbed29d-da89-49bf-b554-5c5f53ca0188" />

## Findings

* Message asks the user to share a verification code.
* Claims to be related to a password reset.
* Uses urgency to force quick action.
* Requests sensitive authentication information.

## Red Flags

* Unexpected password reset message.
* Requests an OTP/verification code.
* Uses urgency to pressure the user.
* Could lead to account takeover.

## Impact

If the OTP is shared, an attacker can gain unauthorised access to the user's account.

## Recommendation

* Never share OTP or verification codes.
* Verify any password reset request yourself.
* Ignore and report suspicious messages.
* Enable passkeys or MFA where available.

## Key Learning

* OTPs are private and should never be shared.
* Always verify unexpected password reset requests.
* Attackers commonly use urgency and social engineering to steal credentials.

---
