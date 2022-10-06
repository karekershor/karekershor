```php
<?php

// NameSpace
namespace JohnMarson;

// AboutMe
class About extends Me {
    public function getDailyKnowledge(): array {
        return [
            Python::class,
            Php::class,
            Bash::class,
        ];
    }
    // FutureGoal
    public function getFutureGoal(): string {
        return "Heuta";
    }
}
```
