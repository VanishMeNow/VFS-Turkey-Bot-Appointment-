<div align="center">

# 🚀 VFS Appointment Bot  
### Automated Visa Appointment Booking System

🔐 **Fast • Smart • Reliable • Undetectable**

<a href="https://wa.me/201286016083" target="_blank">
  <img src="https://img.shields.io/badge/WhatsApp-Contact%20Support-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
</a>

📞 **Support:** +20 128 601 6083  

---

[![GitHub License](https://img.shields.io/github/license/VanishMeNow/VFS-Turkey-Bot-Appointment)](https://github.com/VanishMeNow/VFS-Turkey-Bot-Appointment/blob/main/LICENSE)
[![GitHub Release](https://img.shields.io/github/v/release/VanishMeNow/VFS-Turkey-Bot-Appointment?logo=GitHub)](https://github.com/VanishMeNow/VFS-Turkey-Bot-Appointment/releases)
[![PyPI - Version](https://img.shields.io/pypi/v/VFS-Turkey-Bot-Appointment?logo=pypi)](https://pypi.org/project/VFS-Turkey-Bot-Appointment)
[![Downloads](https://static.pepy.tech/badge/VFS-Turkey-Bot-Appointment)](https://pepy.tech/project/VFS-Turkey-Bot-Appointment)
[![Repo Views](https://hits.dwyl.com/VanishMeNow/VFS-Turkey-Bot-Appointment.svg)](https://github.com/VanishMeNow/VFS-Turkey-Bot-Appointment)

[![GitHub forks](https://img.shields.io/github/forks/VanishMeNow/VFS-Turkey-Bot-Appointment)](https://github.com/VanishMeNow/VFS-Turkey-Bot-Appointment/forks)
[![GitHub Repo stars](https://img.shields.io/github/stars/VanishMeNow/VFS-Turkey-Bot-Appointment)](https://github.com/VanishMeNow/VFS-Turkey-Bot-Appointment/stargazers)
[![GitHub Issues](https://img.shields.io/github/issues/VanishMeNow/VFS-Turkey-Bot-Appointment)](https://github.com/VanishMeNow/VFS-Turkey-Bot-Appointment/issues)

[![GitHub Actions](https://img.shields.io/github/actions/workflow/status/VanishMeNow/VFS-Turkey-Bot-Appointment/build.yml)](https://github.com/VanishMeNow/VFS-Turkey-Bot-Appointment/actions)
[![Codacy](https://app.codacy.com/project/badge/Grade/21f1ecd428ec4342980020a6ef383439)](https://app.codacy.com/gh/VanishMeNow/VFS-Turkey-Bot-Appointment/dashboard)
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/VanishMeNow/VFS-Turkey-Bot-Appointment/badge)](https://securityscorecards.dev/viewer/?uri=github.com/VanishMeNow/VFS-Turkey-Bot-Appointment)

</div>

---

## 🧠 About The Project

**VFS Appointment Bot** is a **high-performance automation system** designed to book visa appointments on **VFS Global** platforms with extreme precision.

Built for:
- ⚡ Speed
- 🕵️ Stealth (Anti-Bot Detection)
- 🎯 Accurate date targeting
- 🔄 Auto retry & smart waiting logic

This bot mimics **real human behavior** to bypass common protection mechanisms used by VFS systems.

---

## ✨ Key Features

- 🤖 Fully Automated Appointment Booking  
- 📅 Smart Calendar Navigation (Target specific dates)  
- 🧠 Human-like interaction (Mouse, timing, scrolling)  
- 🔁 Auto retry when slots are unavailable  
- 🧪 Tested on real VFS environments  
- 🔐 Secure & modular codebase  

---

## 🛠 Tech Stack

- **Python 3.10+**
- **Selenium**
- **Undetected Chromedriver**
- **Advanced Wait & Retry Logic**
- **Logging & Monitoring System**

---

## 📦 Project Structure

```bash
VFS-Appointment-Bot/
│
├─ core/               # Core automation logic
├─ utils/              # Helpers (waits, logging, validators)
├─ assets/             # Images & icons
├─ logs/               # Execution logs
├─ config.py           # Bot configuration
└─ main.py             # Entry point


This Python script(**VFS-Turkey-Bot-Appointment**) automates checking for appointments at VFS Global portal in a specified country.

## Installation

The `VFS-Turkey-Bot-Appointment` script can be installed using two methods:

### 1. Using pip

It is the preferred method for installing `VFS-Turkey-Bot-Appointment`. Here's how to do it:

1. **Create a virtual environment (Recommended):**

   ```bash
   python3 -m venv venv
   ```

   This creates a virtual environment named `venv` to isolate project dependencies from your system-wide Python installation (**recommended**).

2. **Activate the virtual environment:**

   **Linux/macOS:**

   ```bash
   source venv/bin/activate
   ```

   **Windows:**

   ```bash
   venv\Scripts\activate
   ```

3. **Install using pip:**

   ```bash
   pip install VFS-Turkey-Bot-Appointment
   ```

   This will download and install the `VFS-Turkey-Bot-Appointment` package and its dependencies into your Python environment.

### 2. Manual Installation

For an alternative installation method, clone the source code from the project repository and install it manually.

1. **Clone the repository:**

   ```bash
   git clone https://github.com/VanishMeNow/VFS-Turkey-Bot-Appointment
   ```

2. **Navigate to the project directory:**

   ```bash
   cd VFS-Turkey-Bot-Appointment
   ```

3. **Create a virtual environment (Recommended):**

   ```bash
   python3 -m venv venv
   ```

   This creates a virtual environment named `venv` to isolate project dependencies from your system-wide Python installation (**recommended**).

4. **Activate the virtual environment:**

   **Linux/macOS:**

   ```bash
   source venv/bin/activate
   ```

   **Windows:**

   ```bash
   venv\Scripts\activate
   ```

5. **Install dependencies:**

   ```bash
   pip install poetry
   poetry install
   ```

6. **Install playwright dependencies:**

   ```bash
   playwright install
   ```

## Configuration

1. Download the [`config/config.ini`](https://raw.githubusercontent.com/VanishMeNow/VFS-Turkey-Bot-Appointment/main/config/config.ini) template.

   ```bash
   curl -L https://raw.githubusercontent.com/VanishMeNow/VFS-Turkey-Bot-Appointment/main/config/config.ini -o config.ini
   ```

2. Update the vfs credentials and notification channel preferences. See the [Notification Channels](#notification-channels) section for details on configuring email, Twilio, and Telegram notifications.
3. Export the path of the config file to the environment variable `VFS_BOT_CONFIG_PATH`

   ```bash
   export VFS_BOT_CONFIG_PATH=<your-config-path>/config.ini
   ```

**If you installed the script by cloning the repository (manual installation)**, you can directly edit the values in `config/config.ini`.

## Usage

1. **Command-Line Argument:**

   The script requires the source and destination country code ([as per ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Officially_assigned_code_elements)) to be provided as a command-line argument using the `-sc` or `--source-country-code` and `-dc` or `--destination-country-code` option.

2. **Running the Script:**

   There are two ways to provide required appointment details:

   - **Responding to User Prompts (recommended):**

     ```bash
     VFS-Turkey-Bot-Appointment -sc IN -dc DE
     ```

     The script will prompt you to enter the required apponitment parameters for the specified country.

   - **Using `-ap` or `--appointment-params`:**

     Specify appointment details in a comma-separated (**not space-separated**) key-value format:

     ```bash
     VFS-Turkey-Bot-Appointment -sc IN -dc DE -ap visa_center=X,visa_category=Y,visa_sub_category=Z
     ```

   The script will then connect to the VFS Global website for the specified country, search for available appointments using the provided or entered parameters, and potentially send notifications (depending on your configuration).

## Notification Channels

It currently supports three notification channels to keep you informed about appointment availability:

- **Email:** Sends notifications via a Gmail account.
- **Twilio (SMS & Voice Call):** Enables alerts through text messages and phone calls using Twilio's services.
- **Telegram:** Sends notifications directly to your Telegram account through a bot.

**Configuring Notifications:**

**Email:**

1. **Email Account:** You'll need a **Gmail account** for sending notifications.
2. **App Password:** Generate an app password for your Gmail account instead of your regular password. Refer to Google's guide for generating app passwords: [https://support.google.com/accounts/answer/185833?hl=en](https://support.google.com/accounts/answer/185833?hl=en).
3. **Configuration File:** Update your application's configuration file (`config.ini`) with the following details:

   - **`email` (Required):** Your Gmail address.
   - **`password` (Required):** Your generated Gmail app password.

**Twilio:**

1. **Create a Twilio Account (if needed):** Sign up for a free Twilio account at [https://www.twilio.com/en-us](https://www.twilio.com/en-us) to obtain account credentials and phone numbers.
2. **Retrieve Credentials:** Locate your account SID, auth token, and phone numbers within your Twilio account dashboard.
3. **Configuration File:** Update your application's configuration file (`config.ini`) with:

   - `auth_token` (Required): Your Twilio auth token
   - `account_sid` (Required): Your Twilio account SID
   - `sms_enabled` (Optional): Enables SMS notifications (default: True)
   - `call_enabled` (Optional): Enables voice call notifications (default: False)
   - `url` (Optional): Twilio API URL (Only needed if call is enabled)
   - `to_num` (Required): Recipient phone number for notifications
   - `from_num` (Required): Twilio phone number you'll use for sending messages

**Telegram:**

1. **Create a Telegram Bot:** Visit [https://telegram.me/BotFather](https://telegram.me/BotFather) to create a Telegram bot. Follow the on-screen instructions to obtain your bot's token.
2. **Configuration File:** Update your application's configuration file (`config.ini`) with:

   - **`bot_token` (Required):** Your Telegram bot token obtained from BotFather.
   - **`chat_id` (Optional):** The specific Telegram chat ID where you want to receive notifications. If omitted, the bot will send notifications to the chat where it was messaged from. To find your chat ID, you can create a group chat with just yourself and then use the `/my_id` command within the bot.

## Supported Countries and Appointment Parameters

The following table lists currently supported countries and their corresponding appointment parameters:

| Country                    | Appointment Parameters                                      |
| -------------------------- | ----------------------------------------------------------- |
| India(IN) - Germany(DE)    | visa_category, visa_sub_category, visa_center               |
| Iraq(IQ) - Germany(DE)     | visa_category, visa_sub_category, visa_center               |
| Morocco(MA) - Italy(IT)    | visa_category, visa_sub_category, visa_center, payment_mode |
| Azerbaijan(AZ) - Italy(IT) | visa_category, visa_sub_category, visa_center               |

**Notes:**

- Appointment parameters might vary depending on the specific country and visa type. Always consult VFS Global's website for the latest information.

## Known Issues

**1. Login Failures After Frequent Requests:**  
If the bot makes login requests to the VFS website too frequently, the VFS system might temporarily block your access due to suspected automation. This can lead to login failures.

- **Workaround:**
  - **Reduce request frequency:** Consider increasing the delay between bot runs to avoid triggering VFS's blocking mechanisms. You can adjust the interval in the configuration or code.
  - **Retry after 2 hours:** If you encounter a login failure, wait for at least 2 hours before retrying. The VFS block should expire within this timeframe.

**2. Occasional Captcha Verification:**  
The VFS website requires a CAPTCHA verification step during login. Currently, the bot does not have a built-in CAPTCHA solver.

- **Workaround:**
  - **Wait and Retry:** Sometimes, CAPTCHAs appear due to temporary website issues. Wait for a while and try again later.
  - **Retry in another browser:** CAPTCHAs are often solved automatically in the Firefox browser. If it still fails, retry the login process in another browser by setting `browser_type` to `"chromium" or "webkit"` in your `config.ini` file.

**Note:** We are constantly working to improve the bot's functionality. Future updates might include integrated CAPTCHA solving capabilities.

## Extending Country Support

This script is currently designed to work with the VFS Global website for Germany. It might be possible to extend support for other countries by modifying the script to handle potential variations in website structure and parameter requirements across different VFS Global country pages.

## Contributing

We welcome contributions from the community to improve this project! Here's how you can get involved:

- **Report issues:** If you encounter any bugs or problems with the script, please create an issue on the project's repository.
- **Suggest improvements:** Do you have ideas for making the script more user-friendly or feature-rich? Feel free to create an issue or pull request on the repository.
- **Submit pull requests:** If you've made code changes that you think would benefit the project, create a pull request on the repository. Please follow any contribution guidelines outlined in a CONTRIBUTING.md file.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=VanishMeNow/VFS-Turkey-Bot-Appointment&type=Date)](https://star-history.com/#VanishMeNow/VFS-Turkey-Bot-Appointment&Date)

## Disclaimer

This script is provided as-is and is not affiliated with VFS Global. It's your responsibility to ensure you're complying with VFS Global's terms and conditions when using this script. Be aware that website structures and appointment availability mechanisms might change over time.
