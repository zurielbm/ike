# Dev

```bash
install yarn
```

````bash
yarn build
````

## Docker

only works in windows (IDK why)

```
docker build -t zurielbax/ike:latest -t zurielbax/ike:v0.1.9 . 
```

Docker Build Files

[DockerFiles](DockerFiles)

only works in windows (IDK why)

cmd
```bash
docker build -t zurielbax/ike:latest -t zurielbax/ike:v0.1.10 ./DockerFiles/

```

# Edit color and theme

## Main Theme
[themes.scss](resources/sass/themes.scss)

````ccs
    -
    -color-primary-50: 241, 255, 254;
    --color-primary-100: 229, 255, 253;
    --color-primary-200: 174, 240, 229;
    --color-primary-300: 106, 217, 206;
    --color-primary-400: 62, 204, 189;
    --color-primary-500: 76, 173, 164;
    --color-primary-600: 33, 163, 150;
    --color-primary-700: 18, 155, 141;
    --color-primary-800: 46, 146, 136;
    --color-primary-900: 46, 122, 114;
    --color-primary-950: 34, 84, 79;
````

## Edit logo
[MainLogo.vue](resources/scripts/components/icons/MainLogo.vue)

## Edit mail footer
"Power by"
[send](resources/views/emails/send)


## Edit Mail Button
[default.css](resources/views/vendor/mail/html/themes/default.css)

```ccs
a {
    color: #3ECCBD;
}

.footer-link {
    text-decoration: none;
    color: #4CADA4;
}

.button-primary {
    background-color: #4CADA4;
    border-top: 10px solid #4CADA4;
    border-right: 18px solid #4CADA4;
    border-bottom: 10px solid #4CADA4;
    border-left: 18px solid #4CADA4;
}
```

## Other Files with color

New Default: 4CADA4
look that up to replace with new theme colors

[app.blade.php](resources/views/app.blade.php)

[table.blade.php](resources/views/app/pdf/invoice/partials/table.blade.php)

[tax-summary.blade.php](resources/views/app/pdf/reports/tax-summary.blade.php)

[CustomerChartPlaceholder.vue](resources/scripts/admin/views/customers/partials/CustomerChartPlaceholder.vue)

[expenses.blade.php](resources/views/app/pdf/reports/expenses.blade.php)

[sales-customers.blade.php](resources/views/app/pdf/reports/sales-customers.blade.php)

[payment.blade.php](resources/views/app/pdf/payment/payment.blade.php)

[profit-loss.blade.php](resources/views/app/pdf/reports/profit-loss.blade.php)

[sales-items.blade.php](resources/views/app/pdf/reports/sales-items.blade.php)

[pace-loader.scss](resources/sass/components/pace-loader.scss)

## Edit Headers Colors for PDF files
new default: 3ECCBD

[invoice2.blade.php](resources/views/app/pdf/invoice/invoice2.blade.php)

[invoice2.blade.php](resources/views/app/pdf/invoice/invoice2.blade.php)

[payment.blade.php](resources/views/app/pdf/payment/payment.blade.php)

Default: E5FFFC

[browserconfig.xml](public/favicons/browserconfig.xml)

Default: 3ECCBD

[estimate1.blade.php](resources/views/app/pdf/estimate/estimate1.blade.php)

[estimate2.blade.php](resources/views/app/pdf/estimate/estimate2.blade.php)

[estimate3.blade.php](resources/views/app/pdf/estimate/estimate3.blade.php)

[invoice3.blade.php](resources/views/app/pdf/invoice/invoice3.blade.php)

Default: 2E7A72

[invoice1.blade.php](resources/views/app/pdf/invoice/invoice1.blade.php)

[invoice2.blade.php](resources/views/app/pdf/invoice/invoice2.blade.php)

[invoice3.blade.php](resources/views/app/pdf/invoice/invoice3.blade.php)

[estimate1.blade.php](resources/views/app/pdf/estimate/estimate1.blade.php)

[estimate2.blade.php](resources/views/app/pdf/estimate/estimate2.blade.php)

[estimate3.blade.php](resources/views/app/pdf/estimate/estimate3.blade.php)

[payment.blade.php](resources/views/app/pdf/payment/payment.blade.php)

# My Colors
2E7A72
3ECCBD
E5FFFC
4CADA4

PDF:
78BBB7
