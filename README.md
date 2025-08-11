# Bohudur Easy Digital Downloads
<img src="https://bohudur.one/bohudurlogo.png" alt="Bohudur Logo" width="328"/>

Bohudur EDD is a WordPress plugin that integrates the **Bohudur** payment gateway with Easy Digital Downloads (EDD), enabling merchants to accept payments through Bohudur.

## Features

- Seamless integration with Easy Digital Downloads
- Customizable gateway display name
- Supports payment initiation and verification with Bohudur
- Currency converter inbuilt
- Easy setup and configuration

## Download & Installation

### Download

Download plugin by clicking [Bohudur.zip](https://github.com/BohudurOne/EasyDigitalDownloads/blob/main/edd-bohudur.zip)

### Installation

1. **Upload the Plugin**  
   Upload the downloaded plugin zip file in the WordPress:  
   - Go to `Plugins` > `Add New`  
   - Click `Upload Plugin`  
   - Choose the downloaded zip file and click `Install Now`

2. **Activate the Plugin**  
   After installation, click the **Activate** button to activate the plugin.

## Configuration

1. **Access Settings**  
   Go to `Downloads` > `Settings` > `Payment Gateways` > `Bohudur` to configure the plugin settings.

2. **Configure Bohudur Gateway**  
   - **Gateway Display Name** – The name that will be shown on the checkout page  
   - **API KEY** – Your Bohudur API key  
   - **Webhook Success URL** – If you want to get webhook response after payment success (Optional)
   - **Webhook Cancelled URL** – If you want to get webhook response after payment cancel (Optional)  
   - **Exchange Rate** – Set the exchange rate for your used currency. If you give 0 then it will use Bohudur Inbuilt Currency Converter.

3. **Save Changes**  
   Click **Save Changes** to apply your settings.

## Usage

1. **Checkout with Bohudur**  
   When a customer selects Bohudur as the payment method during checkout, they will be redirected to the Bohudur payment page to complete the transaction.

2. **Payment Verification**  
   The plugin automatically handles payment verification and updates the order status accordingly.

## License

This plugin is licensed under the [GPL v2 or later](https://www.gnu.org/licenses/gpl-2.0.html).
