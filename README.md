# Microsoft Entra ID - Multi-Factor Authentication (MFA) Lab Walkthrough

This guide provides step-by-step visual documentation for configuring Per-user Multi-Factor Authentication (MFA) and handling first-time user sign-in flows within the Microsoft Entra admin center.

---

## 📋 Table of Contents
1. [User Directory & Per-User MFA Status](#1-user-directory--per-user-mfa-status)
2. [Enabling Multi-Factor Authentication](#2-enabling-multi-factor-authentication)
3. [First-Time Sign-In & Password Entry](#3-first-time-sign-in--password-entry)
4. [Authenticator App Setup & Verification](#4-authenticator-app-setup--verification)
5. [Portal Sign-In & Copilot Access](#5-portal-sign-in--copilot-access)

---

## 1. User Directory & Per-User MFA Status
Administrators review user accounts and manage authentication states from the Entra admin center.

* **User Directory Overview:** Viewing active accounts within the Contoso tenant, including **Adele Vance** (`AdeleV@WWLx313810.onmicrosoft.com`)[cite: 4].
  
  ![Users Directory](1.jpg)

* **Per-User MFA Management:** Navigating to the **Per-user multifactor authentication** blade to inspect and update individual user states[cite: 5].
  
  ![Per-User MFA Settings](2.jpg)

---

## 2. Enabling Multi-Factor Authentication
Enforcing MFA requirements for specific directory users.

* **Enable MFA Prompt:** Selecting Adele Vance and triggering the **Enable** action, which provides registration links for modern authentication setups[cite: 6].
  
  ![Enable MFA Prompt](3.jpg)

---

## 3. First-Time Sign-In & Password Entry
New or freshly provisioned users authenticate using their assigned credentials.

* **Password Authentication:** Adele signs into the Contoso demo portal using her temporary password and verifies credentials[cite: 7].
  
  ![Enter Password](4.jpg)

---

## 4. Authenticator App Setup & Verification
Guiding users through setting up secure second factors for authentication.

* **Authenticator Installation Prompt:** Prompting the user to install the **Microsoft Authenticator** app on their mobile device via Google Play or the App Store[cite: 1].
  
  ![Install Microsoft Authenticator](5.jpg)

* **Configuration Success:** Confirmation screen indicating that the **Authenticator Added** status is successful and set as the default sign-in method[cite: 2].
  
  ![Authenticator Added](6.jpg)

---

## 5. Portal Sign-In & Copilot Access
Post-authentication verification and access to tenant services.

* **Copilot & Account Dashboard:** Adele successfully logs into the tenant environment, displaying an active session with Microsoft Copilot and account management options[cite: 3].
  
  ![Copilot Sign-In View](7.jpg)

---

## Repository Structure
```text
├── README.md
└── Screenshots/
    ├── 1.jpg
    ├── 2.jpg
    ├── 3.jpg
    ├── 4.jpg
    ├── 5.jpg
    ├── 6.jpg
    └── 7.jpg
