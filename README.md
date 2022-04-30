# php-vs-typescript

[![Software License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

This repository provides a Typescript cheat sheet for PHP developers.

## Classes

```php
class Person
{
    public string $name;
    public function __construct(string $name)
    {
        $this->name = $name;
    }
    public function sayName(): void
    {
        echo $this->name;
    }
}
```

```typescript
class Person {
  name: string;
  constructor(name: string) {
    this.name = name
  }
  sayName(): void {
    console.log(this.name);
  }
}
```
