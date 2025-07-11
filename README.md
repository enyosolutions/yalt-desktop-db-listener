# desktop-db-listener

**desktop-db-listener** is a simple utility that enables fully local Point of Sale (POS) systems to securely connect and interact with the [Yalt Loyalty Platform](https://yalt.co). This bridge application brings digital customer engagement and loyalty tools to businesses whose POS environments are otherwise inaccessible over the cloud.

- **Supported POS Systems:**  
  - **XD**  
  - **Sage**  
- Additional POS integrations are in development.

---

## Key Features

- **Local–to–Cloud Loyalty Integration**  
  Sync sales and customer events from your local POS directly to Yalt’s cloud environment.
- **Plug-and-Play Installation**  
  Minimal configuration for fast setup with no technical expertise required.
- **Reliable & Secure**  
  Data is securely transmitted using standard encryption protocols.
- **Automatic Synchronization**  
  Seamlessly keeps customer actions, purchases, and loyalty details up to date.

---

## Use Cases

- Retailers and restaurants using on-premises POS systems who want to leverage powerful digital loyalty, referral, and marketing features from Yalt.
- Businesses restricted to offline/local POS setups due to security, connectivity, or legacy environment requirements.

---

## Installation

1. **Download** the latest version of desktop-db-listener for your operating system from our [release page](https://github.com/enyosolutions/yalt-desktop-db-listener/releases).
2. **Run the installer** and follow the prompts.
3. During setup, you will be prompted to select your POS type (XD or Sage) and specify the local database connection parameters.
4. Enter your Yalt API key (provided in your Yalt business dashboard).
5. Click **Start Listener**. The service runs continuously in the background.

---

## Configuration

Configuration is performed during installation, but you can update settings later via the app’s settings UI:

- **POS Database Connection:**  
  Input local database credentials (host, port, user, password) for XD or Sage.
- **Yalt Credentials:**  
  Enter your unique business API key/secret from the Yalt platform.
- **Synchronization Interval:**  
  Choose how often the listener checks for new data (default: 1 min).

---

## How It Works

- desktop-db-listener monitors your POS database for new loyalty-relevant transactions.
- Detected actions (sales, loyalty points awards, stamps, etc.) are securely pushed to the Yalt platform in real time or scheduled intervals.
- Your customers’ loyalty status, digital stamp cards, rewards, and referrals are instantly updated in Yalt.

---

## Compatibility

- **Supported POS:** XD, Sage  
- **Operating Systems:** Windows 10/11 (full UNIX/Linux support under development)
- **Yalt Compatibility:** All major loyalty features including Digital Stamp Cards, Review Booster, and Referral Programs.

---

## Troubleshooting

- **Connection Issues:** Ensure POS database is accessible locally and firewall/antivirus is not blocking the listener.
- **Yalt API Errors:** Double-check your API credentials in Yalt dashboard.
- **Sync Lag:** Increase the synchronization interval temporarily or review network bandwidth.

If you encounter persistent issues, refer to our [troubleshooting guide](#) or contact [Yalt Support](mailto:support@yalt.co).

---

## Contributing

Feature requests and bug reports are welcome! Please submit them via the [Issues](#) section of this repository.

---

## About Yalt

[Yalt](https://yalt.co) is the all-in-one cloud loyalty platform. Unlock digital rewards, referral schemes, direct marketing, and more, regardless of your current POS environment.

---

**Empower your local POS with the tools to create loyal, returning customers—powered by Yalt!**
