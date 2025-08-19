# Plesk

## Configure Paymenter

Create a new server in the Paymenter admin panel and select Plesk as the server type. Fill in the following fields:
- Hostname: The hostname of your Plesk server (e.g. `plesk.example.com:8443`)
- Username: The username of the Plesk account 
- Password: The password of the Plesk account

![image](/assets/images/extensions/plesk/server_settings.png)

Press `Test Connection` to see if the connection is working.

## Configuring the product
Select the Plesk server you created in the previous step and type in the correct package.

![image](/assets/images/extensions/plesk/product.png)

### Sending the credentials via email

You can send the username and password to the customer via email. Fill in the email template in the product settings.

Here is a example of a email template:

```blade
Your domain {{ $domain }} is ready.
@isset($password)
- Username: {{ $username }}
- Password: {{ $password }}
@endisset
```