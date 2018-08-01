# Utilities

A set of helper functions for use in Genesis child themes.

## Minify CSS

```php
use SEOThemes\Core\Utilities\MinifyCSS;

$css = '
    body {
        color: red;
    }
';

MinifyCSS::minify( $css );
```

Outputs:

```php
body{color:red}
```
