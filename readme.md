# Readme

This small module will help integrating patternlab with drupal backend. Instead of declaring a custom theme-hook ad including a patternlab-pattern into your custom template you can call

```php
$render_array = pattern('atoms', 'button', ['label' => 'hello world']);
```

## Installation

1. Install the module as usual
2. Copy the `patternlab-pattern.tpl.twig` into your twig-based theme.

## Usage

To render a pattern, just use the `pattern`-helper-function:

```php
$render_array = pattern('atoms', 'button', ['label' => 'hello world']);
```
Thank You.

