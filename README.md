## Fork (redcuillin)

PEAR [Validate](https://pear.php.net/package/Validate) fork for continued use with current PHP versions and Composer.

### Using this fork with Composer

Add the following to your `composer.json` `repositories` and `require` sections (merge with existing entries as needed):

```json
"repositories": [
    {
        "type": "vcs",
        "url": "https://github.com/redcuillin/Validate"
    }
],
"require": {
    "pear/validate": "dev-master as 2.999.0"
}
```

-----

## Upstream readme:

This package is [Validate](http://pear.php.net/package/Validate) from PEAR.

**Summary:** Validation class.

**Description:** Package to validate various datas. It includes:

- numbers (min/max, decimal or not)
- email (syntax, domain check, rfc822)
- string (predifined type alpha upper and/or lowercase, numeric,...)
- date (min, max, rfc822 compliant)
- uri (RFC2396)
- possibility valid multiple data with a single method call (`::multiple`)

Please report upstream issues via the [PEAR bug tracker](http://pear.php.net/bugs/search.php?cmd=display&package_name[]=Validate).
