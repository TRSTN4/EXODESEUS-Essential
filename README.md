# EXODESÉUS Essential

![EXODESÉUS Essential Banner](https://github.com/TRSTN4/EXODESEUS-Essential/blob/main/images/exodeseus-essential-banner.png?raw=true)

## What is included?
- What is EXODESÉUS Essential and how does it work?
- Differences compared to EXODESÉUS Version 1 (see [Version 1](https://github.com/TRSTN4/EXODESEUS) documentation)
- App Preview

---

## What is EXODESÉUS Essential?

**EXODESÉUS Essential** is the modern, streamlined successor to the original EXODESÉUS system  
(**see [Version 1](https://github.com/TRSTN4/EXODESEUS) for the original implementation and behavior**).

While EXODESÉUS Essential behaves fundamentally the same as [Version 1](https://github.com/TRSTN4/EXODESEUS), it has been fully redesigned and optimized with a clear focus on:

- Real-time news delivery  
- A reliable and accessible SOS emergency system  
- Plug-and-play deployment for households  
- Consistent cross-platform behavior  

The app is built entirely in **Flutter**, ensuring identical functionality and layout across all platforms, including iOS and Android.

---

## Core Direction Change

### From Custom Installations → Plug-and-Play Households

[EXODESÉUS Version 1](https://github.com/TRSTN4/EXODESEUS) was primarily designed around custom, per-household configurations.

**EXODESÉUS Essential** shifts the focus to:
- Immediate usability
- Minimal setup
- Easy adoption by any household

The app works out-of-the-box and can be enhanced with optional hardware integrations.

---

## System Architecture

### Firebase-Only Real-Time Architecture

In EXODESÉUS Essential:
- The traditional database and API layer have been removed
- All data is stored and synchronized using **Firebase**
- Clients fetch and react to updates directly in real time

This results in:
- Faster data retrieval  
- Reduced system complexity  
- Real-time synchronization across devices  
- Increased reliability during emergency situations  

---

## 1. News System (Primary Feature)

### 1.1 Data Collection

A server continuously gathers and processes news data from multiple sources, including:
- Sky News  
- LiveUaMap  
- Other monitored feeds  

The processed news data is written directly to **Firebase**, which serves as the central data source.

---

### 1.2 News Retrieval by Users

When users open or refresh the app:
- News articles are fetched directly from Firebase
- Updates appear in real time
- Behavior is identical across all supported platforms

---

## 2. Removed Feature: User-Generated Content

Unlike [EXODESÉUS Version 1](https://github.com/TRSTN4/EXODESEUS):
- **User-generated posts and messages have been fully removed**
- Users can no longer submit their own content

This change ensures:
- Higher data reliability  
- Reduced moderation requirements  
- A clear focus on verified information and safety  

---

## 3. SOS Emergency System (Primary Feature)

> *Available to all households. Hardware integration is optional.*

The SOS system remains one of the core pillars of **EXODESÉUS Essential** and has been refined for reliability and ease of use.

---

### 3.1 Plug-and-Play SOS

EXODESÉUS Essential includes:
- SOS activation directly from the app
- Immediate emergency notifications
- Automatic switch to **CODE RED ALERT** mode

No additional hardware is required for basic SOS functionality.

---

### 3.2 Optional Hardware Integration

If available, users can connect:
- **Philips Hue lights**
- **Sonos speakers**

These devices enhance emergency awareness by:
- Triggering visual alerts  
- Playing audio alarms or warnings  

All device states are managed via Firebase and monitored in real time by the server.

---

### 3.3 CODE RED Alert Behavior

When CODE RED is activated:
- All users receive an immediate notification
- The app interface switches to a **CODE RED ALERT** screen
- Non-essential features are disabled to maintain focus

This behavior matches the original system (**see [Version 1](https://github.com/TRSTN4/EXODESEUS)**).

---

### 3.4 Alert Deactivation Safety

To exit CODE RED:
- A **unanimous confirmation** from connected users is required
- This prevents accidental or malicious deactivation

---

## 4. Threat Monitoring & Automation

The server continuously performs:
- 24/7 threat monitoring
- DEFCON level tracking

If **DEFCON 1** is detected:
- CODE RED ALERT is triggered automatically
- No user interaction is required

### Monthly System Check
- Runs every first Monday of the month at 12:00 PM
- Lasts exactly 1 minute and 26 seconds
- Ensures system readiness

---

## 5. Notifications

- Uses **Firebase Cloud Messaging (FCM)**
- Tokens are registered automatically
- Notifications behave consistently across all platforms

---

## 6. Access & Security

EXODESÉUS Essential remains a closed-access application:
- Invite-key based onboarding
- Privacy-first design
- Suitable for families and trusted households

The simplified architecture allows for rapid scaling or wider release if needed.

---

## Summary

**EXODESÉUS Essential**:
- Retains the core behavior of EXODESÉUS Version 1 (see [Version 1](https://github.com/TRSTN4/EXODESEUS))
- Uses Flutter for full cross-platform consistency
- Removes user-generated content
- Focuses on News and Emergency Safety
- Introduces a plug-and-play model for households
- Supports optional Hue and Sonos integration for enhanced SOS functionality

> **EXODESÉUS Essential is the reliable, accessible, and modern foundation of the EXODESÉUS ecosystem.**

---

## App Preview (EXODESÉUS Essential)

Below are images and GIFs showcasing the **current UI and user experience** of  
**EXODESÉUS Essential**, the actively maintained and recommended version of the app.

These visuals reflect:
- The redesigned, modern layout
- Consistent behavior across all platforms (Flutter)
- The simplified News and SOS-focused experience
- Improved clarity and emergency usability

---

### Screenshots

<img src="https://github.com/TRSTN4/EXODESEUS-Essential/blob/main/images/layout.png?raw=true" width="200" height="auto"> <img src="https://github.com/TRSTN4/EXODESEUS-Essential/blob/main/images/sos.png?raw=true" width="200" height="auto"> <img src="https://github.com/TRSTN4/EXODESEUS-Essential/blob/main/images/system_logging.png?raw=true" width="200" height="auto"> 

---

### Animations / GIFs

<img src="https://github.com/TRSTN4/EXODESEUS-Essential/blob/main/images/full_system_test.gif?raw=true" width="200" height="auto"> <img src="https://github.com/TRSTN4/EXODESEUS-Essential/blob/main/images/red_alert.gif?raw=true" width="200" height="auto"> 

---

> ℹ️ **Note**  
> EXODESÉUS Essential replaces the legacy [Version 1](https://github.com/TRSTN4/EXODESEUS) system.  
> It offers a faster, more reliable architecture, a plug-and-play household model,
> and a refined SOS system designed for everyday safety and emergency readiness.

---

