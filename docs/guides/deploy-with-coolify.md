# Deploy with Coolify

## How to configure Paymenter with Coolify

1. Create a new resource using the **Paymenter** service.
2. Start the resource.
3. Set the correct app URL via the terminal:

Select the Paymenter container and run the following command:
   ```bash
   php artisan app:init
   ```
4. Create the first admin user:
   ```bash
   php artisan app:user:create
   ```