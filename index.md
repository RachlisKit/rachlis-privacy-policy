# Privacy Policy for Orynt

**Last Updated: November 12, 2025**

## Introduction

This Privacy Policy describes how Orynt ("we", "our", or "the app") collects, uses, and protects your information when you use our mobile application.

## Information We Collect

### 1. Location Data
- **What we collect:** Your current GPS coordinates
- **How we use it:** To show nearby photo requests and send notifications about new requests in your area
- **How often:** Updated every ~5 minutes or when you move more than 500 meters
- **Storage:** Stored in Firebase Firestore with geohash precision level 6 (~1.2km × 0.6km accuracy)
- **Sharing:** Your exact location is only visible to you. Other users see approximate location (geohash area)

### 2. Account Information
- **Email address:** Used for authentication and account recovery (not visible to other users)
- **Display name:** Your chosen username (visible to request creators when you complete their requests)
- **Password:** Securely hashed and stored in Firebase Authentication

### 3. Photos
- **What we collect:** Photos you take when completing photo requests
- **Storage:** Uploaded to Firebase Storage
- **Visibility:** Only visible to the request creator
- **Deletion:** Automatically deleted when the request is deleted

### 4. Push Notification Tokens
- **What we collect:** FCM (Firebase Cloud Messaging) tokens
- **How we use it:** To send you notifications about new photo requests near you
- **Updates:** Automatically refreshed by the system

### 5. App Usage Data
- **Request history:** Records of requests you've created or completed
- **Coin balance:** Your in-app currency balance
- **Notification preferences:** Your chosen notification radius (20-2000 meters)

## How We Use Your Information

We use the collected information to:
- Show you photo requests near your current location
- Enable you to create photo requests at specific locations
- Send push notifications about new requests in your notification radius
- Process photo uploads when completing requests
- Maintain your account and coin balance
- Enable authentication and account recovery

## Data Security

We implement security measures to protect your information:
- ✅ All data transmitted over HTTPS
- ✅ Passwords are hashed and never stored in plain text
- ✅ Firebase Security Rules restrict unauthorized access
- ✅ Photos are only accessible to relevant users
- ✅ Email addresses are never shared with other users

## Data Retention

- **Location data:** Stored while your account is active; updated regularly
- **Photos:** Stored until the request is completed or deleted
- **Account data:** Retained until you delete your account
- **Request history:** Retained for historical records

## Your Rights and Choices

You have the right to:
- **Control notifications:** Adjust your notification radius or disable notifications in Settings
- **Hide requests:** Toggle visibility of other users' requests
- **Control location sharing:** Manage location permissions in iOS Settings
- **Delete your account:** Contact us to request account deletion

## Third-Party Services

We use the following third-party services:
- **Firebase (Google):** Authentication, database, storage, and push notifications
- **Apple Maps:** Location search and map display

These services have their own privacy policies:
- Firebase Privacy Policy: https://firebase.google.com/support/privacy
- Google Privacy Policy: https://policies.google.com/privacy

## Children's Privacy

Our app is not intended for users under 12 years of age. We do not knowingly collect information from children under 12. If you believe a child has provided us with personal information, please contact us.

## Data Sharing

We do NOT:
- ❌ Sell your data to third parties
- ❌ Use your data for advertising tracking
- ❌ Share your exact location with other users
- ❌ Share your email address with anyone

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by:
- Updating the "Last Updated" date at the top
- Sending an in-app notification for significant changes

## International Data Transfers

Your data may be transferred to and stored on servers located outside your country. By using the app, you consent to such transfers.

## Contact Us

If you have questions about this Privacy Policy or your data, please contact us:

**Email:** kit.rachlis@gmail.com  
**Developer:** Nikita Rachlis  
**App:** Orynt (Rachlis Project One)

---

## Legal Compliance

This app complies with:
- Apple App Store Guidelines
- Firebase Terms of Service
- Applicable data protection regulations

## Your Consent

By using Orynt, you consent to this Privacy Policy and agree to its terms.
