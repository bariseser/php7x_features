# PHP 7.x All New Features
This List just listed new features for PHP 7.x version.

## PHP 7.0
##### [Scalar type declarations](http://php.net/manual/tr/migration70.new-features.php#migration70.new-features.scalar-type-declarations)
```php
    // Coercive Mode: Defaul mode
    
    function sumOfInts(int ...$ints)
    {
        return array_sum($ints);
    }
    
    // Strict Mode: 
    
    declare(strict_types=1);
    function sum(int ...$ints) {
        return array_sum($ints);
    }
```

##### [Return type declarations](http://php.net/manual/tr/migration70.new-features.php#migration70.new-features.return-type-declarations)
```php
    function sum($a, $b) : int 
    {
        return $a + $b;
    }
```

##### [Null coalescing operator](http://php.net/manual/tr/migration70.new-features.php#migration70.new-features.null-coalesce-op)
```php
    $rememberMe = $_POST['remember'] ?? '0';
```

##### [Spaceship operator](http://php.net/manual/tr/migration70.new-features.php#migration70.new-features.spaceship-op)
##### [Constant arrays using define()](http://php.net/manual/tr/migration70.new-features.php#migration70.new-features.define-array)
##### [Anonymous classes](http://php.net/manual/tr/migration70.new-features.php#migration70.new-features.anonymous-classes)
##### [Group use declarations](http://php.net/manual/tr/migration70.new-features.php#migration70.new-features.group-use-declarations)
##### [Generator Return Expressions](http://php.net/manual/tr/migration70.new-features.php#migration70.new-features.generator-return-expressions)
##### [Generator delegation](http://php.net/manual/tr/migration70.new-features.php#migration70.new-features.generator-delegation)

## PHP 7.1
##### [Nullable types](http://php.net/manual/tr/migration71.new-features.php#migration71.new-features.nullable-types)
##### [Void functions](http://php.net/manual/tr/migration71.new-features.php#migration71.new-features.void-functions)
##### [Class constant visibility](http://php.net/manual/tr/migration71.new-features.php#migration71.new-features.class-constant-visibility)
##### [Multi catch exception handling](http://php.net/manual/tr/migration71.new-features.php#migration71.new-features.mulit-catch-exception-handling)

## PHP 7.2
##### [New object type](http://php.net/manual/tr/migration72.new-features.php#migration72.new-features.object-type)
##### [Abstract method overriding](http://php.net/manual/tr/migration72.new-features.php#migration72.new-features.abstract-method-overriding)
##### [Password hashing with Argon2](http://php.net/manual/tr/migration72.new-features.php#migration72.new-features.pws-hashing-with-argon2)

## PHP 7.3
##### [Flexible Heredoc and Nowdoc](http://php.net/manual/tr/migration73.new-features.php#migration73.new-features.core.heredoc)
##### [Array Destructuring supports Reference Assignments](http://php.net/manual/tr/migration73.new-features.php#migration73.new-features.core.destruct-reference)
##### [Argon2id Support](http://php.net/manual/tr/migration73.new-features.php#migration73.new-features.core.argon2id)