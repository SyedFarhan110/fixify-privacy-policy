# Privacy Policy — Fixify

**Last updated:** June 18, 2026

---

## Data We Collect

| Data | Purpose |
|---|---|
| **Name** | Account identification, display on job requests |
| **Email** | Account login, email verification, notifications |
| **Phone Number** | Contact between customers and technicians |
| **Password** | Account authentication (stored hashed by Firebase) |
| **Role** (User/Technician) | Determine app features and access |
| **City & Address** | Match customers with local technicians |
| **Specialization, Experience, Bio** | Technician profile (technicians only) |
| **Job Request Details** | Service description posted by customers |

## How We Collect Data

- **Directly from you:** Signup form, profile completion, job request form
- **Automatically:** Firestore offline persistence caches data locally on your device

## Third-Party Services

| Service | What It Does |
|---|---|
| **Firebase Authentication** | Secure login with email & password |
| **Cloud Firestore** | Stores all user profiles, job requests |
| **Firebase Storage** | Future profile image uploads |
| **Email OTP** | Sends verification code to your email |
| **Gmail SMTP** | Delivers OTP emails |

## How We Use Your Data

- Create and manage your account
- Connect customers with technicians
- Send service-related communications
- Prevent fraud (duplicate phone number check)

## Data Sharing

- **Phone number** is visible to technicians when you post a job request (so they can contact you)
- **We do NOT** sell your data
- **We do NOT** share data with advertisers
- **We do NOT** use analytics or tracking SDKs

## Data Retention

- Your data stays in Firestore until you request deletion
- Firebase Auth retains your email/UID until account deletion

## Your Rights

- **Access:** Contact us to request a copy of your data
- **Deletion:** Email us to delete your account and all associated data
- **Correction:** Update your profile anytime in the app

## Children

- This app is not intended for users under 13. We do not knowingly collect data from children.

## Security

- Passwords are hashed by Firebase Auth
- Firestore uses security rules to restrict access
- OTP verification protects account creation

## Changes

- We may update this policy. Changes will be posted here with an updated date.

## Contact

For privacy concerns or data deletion requests:
**Email:** [your-email@example.com]

---

## Play Store Bullet Points Summary

1. **Account Info:** Name, email, phone, password (for login & profile)
2. **Profile Data:** City, address, specialization, experience (to match users with technicians)
3. **Job Requests:** Service descriptions posted by customers (visible to technicians)
4. **No Location Tracking:** No GPS, no device ID, no analytics collected
5. **No Data Sold:** We never share or sell personal data to third parties
6. **Third-Party Services:** Firebase (Auth, Firestore, Storage), Email OTP via Gmail SMTP
7. **Data Deletion:** Email us to request full account deletion
