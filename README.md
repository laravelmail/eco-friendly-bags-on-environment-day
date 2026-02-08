# Eco Friendly Bags On Environment Day

A professional email template announcing an Eco-friendly bag sale on Environment Day for both retail and educational sectors.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Retail, Education
- **Message Type:** Events
- **Tags:** promotion, ecofriendly, environmentday

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/eco-friendly-bags-on-environment-day.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/eco-friendly-bags-on-environment-day/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.eco-friendly-bags-on-environment-day',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
