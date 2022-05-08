# www.phpfunc.com


## PHP version

Check PHP version

```bash
php -version
```

## PHP script

Show global variable

```php
class Fruit {
    public $name;
  
    function __construct($name) {
        $this->name = $name;
    }
    function __toString() {
        return $this->name;
    }
}

$apple = new Fruit("Apple");
echo (string ) $apple;
```
