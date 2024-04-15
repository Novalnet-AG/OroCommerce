# NOVALNET PAYMENT INTEGRATION FOR OROCOMMERCE
Novalnet’s free payment bundle for <a href="https://www.novalnet.com/integration/orocommerce/">OroCommerce</a> ensures simple and secure integration of payments and payment services for OroCommerce shops, allowing shop owners to automate the entire payment process from checkout till collection. 

## Integration requirements 
Novalnet merchant account is required for using this Novalnet Payment Gateway for OroCommerce. The Bundle is available for the 5.0.0 - 5.1.2 version in the following languages: EN & DE. 

## Advanced functions of OroCommerce payment bundle
- Easy configuration for all payment methods
- One platform for all relevant payment types and related services
- Complete automation of all payment processes
- Secure SSL-encoded gateways
- More than 50 fraud prevention modules integrated to prevent risk in real-time
- Effortless configuration of risk management with fraud prevention
- Comprehensive affiliate system with automated split conversion of transactions on revenue sharing
- Dynamic subscription and member management for recurring payments
- No PCI DSS certification is required when using our payment module
- Real-time monitoring of the transaction flow from the checkout to the receivables
- Multilevel claims management with integrated handover to the collection and various export functions for the accounting
- Automated e-mail notification function concerning payment status reports
- Clear real-time overview and monitoring of payment status
- Automated bookkeeping report in XML, SOAP, CSV, MT940
- Simple, seamless integration of the payment module
- Secure SSL-encoded gateways
- Credit/Debit Card iframe integration 
- Custom CSS configuration for Credit/Debit Card iframe
- One-click shopping supported for Credit/Debit Cards, Direct Debit SEPA, Direct Debit SEPA with payment guarantee, Instalment by Direct Debit SEPA & PayPal
- Easy confirmation/cancellation of on-hold transactions for Direct Debit SEPA, Direct Debit SEPA with payment guarantee, Instalment payment for Direct Debit SEPA, Credit/Debit Card, Invoice, Invoice with payment guarantee, Instalment payment for Invoice, Prepayment & PayPal
- Refund option for Credit/Debit Cards, Direct Debit SEPA, Direct Debit SEPA with payment guarantee, Instalment by Direct Debit SEPA, Invoice, Invoice with payment guarantee, Instalment by Invoice, Prepayment, Barzahlen/viacash, Sofort, iDEAL, eps, giropay, PayPal, Przelewy24, PostFinance Card, PostFinance E-Finance, Bancontact, Online bank transfer, Alipay, WeChat pay & Trustly
- Responsive templates

For detailed documentation and other technical inquiries, please send us an email at <a href="mailto:technic@novalnet.de"> technic@novalnet.de </a>

## Integrated payment methods for OroCommerce payment bundle

-	Direct Debit SEPA
-	Credit/Debit Cards
-	Invoice
-	Prepayment
-	Invoice with payment guarantee
-	Direct Debit SEPA with payment guarantee
-	Instalment by Invoice
-	Instalment by Direct Debit SEPA
-	iDEAL
-	Sofort
-	giropay
-	Barzahlen/viacash
-	Przelewy24
- eps
-	PayPal
-	PostFinance Card
- PostFinance E-Finance
- Bancontact
- Multibanco
- Online bank transfer
- Alipay
- WeChat pay
- Trustly

## Downloads
Download of Novalnet Payment Bundle for OroCommerce will be done through the following steps:
1. **Download** the payment bundle from <a href="https://extensions.oroinc.com/orocommerce/extension/novalnet-payment-extension/"> here</a> or <a href="https://www.novalnet.de/kontakt/sales"> contact us</a>.
2. Install the Novalnet Payment Bundle to your OroCommerce shop via composer
3. Include Merchant Details in the shop admin panel 
4. Activate & configure the preferred payment types in your shop admin panel

## Installation 
Easy installation of Novalnet Payment Bundle for OroCommerce will be done through the following steps:

### Installation via Composer
Follow the below steps and run each command in your terminal from the shop root directory
 ##### 1. Start with upgrading Composer to the latest version and make sure that the composer.json file supports all the latest versions.
 ```
 composer self-update
 ```
 ##### 2. Then, install the composer package using the Composer require command:
 ```
 composer require novalnet/commerce-novalnet --prefer-dist --update-no-dev
 ```
 ##### 3. Next, clear the cache:
 ```
 sudo rm -rf var/cache/prod
 ```
 ##### 4. When you are done adding the package, use the oro:platform:update command line for platform update
 ```
 php bin/console oro:platform:update --env=prod --force
 ```
 ##### 5: Finally, ensure you clean the cache.
 ```
  php bin/console cache:clear --env=prod
 ```
### Upgrading the Novalnet Payment Bundle

 ##### 1. It's strongly advised to back up the existing Novalnet payment bundle prior to uninstallation for disaster recovery purposes.<br>

 ##### 2. To install the Novalnet payment bundle, run the following command in your terminal from the shop root directory.
 ```
 composer require novalnet/commerce-novalnet --prefer-dist --update-no-dev
 ```
 ##### 3. Next, clear the cache:
 ```
 sudo rm -rf var/cache/prod
 ```
 ##### 4. When you are done adding the package, use the oro:platform:update command line for platform update
 ```
 php bin/console oro:platform:update --env=prod --force
 ```
 ##### 5: Finally, ensure you clean the cache.
 ```
 php bin/console cache:clear --env=prod
 ```
## Licenses
As a European Payment institution, Novalnet holds all necessary payment licenses to accept and process payments worldwide. We also comply with European data protection regulations to guarantee advanced data protection worldwide.  
See here for [Freeware License Agreement](https://www.novalnet.com/payment-plugins-free-license/).

## Documentation & Support
For more information about the OroCommerce Payment Bundle Integration by Novalnet, please get in touch with us: <a href="mailto:sales@novalnet.de"> sales@novalnet.de </a> or +49 89 9230683-20<br>

Novalnet AG<br>
Zahlungsinstitut (ZAG)<br>
Gutenbergstraße 7<br>
D-85748 Garching<br>
Deutschland<br>
E-mail: sales@novalnet.de<br>
Tel: +49 89 9230683-20<br>
Web: www.novalnet.de

## Who is Novalnet AG?
<p>Novalnet AG is a <a href="https://www.novalnet.de/zahlungsinstitut"> leading financial service institution </a> offering payment gateways for processing online payments. Operating in the market as a full payment service provider, Novalnet AG provides online merchants with user-friendly payment integration with all major shop systems and self-programmed sites.</p> 
<p>Accept, manage and monitor payments all-in-one platform with one single contract!</p>
<p>Our SaaS engine is <a href="https://www.novalnet.de/pci-dss-zertifizierung"> PCI DSS </a> certified, empowers businesses with real-time risk management mechanisms, secure escrow account payments, streamlined receivables management, dynamic member and subscription administration, and customized payment solutions tailored to diverse business models, including marketplaces and affiliate programs..</p>
