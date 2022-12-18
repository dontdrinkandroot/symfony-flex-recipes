Symfony Flex Recipes
====================

Symfony Flex recipes for dontdrinkandroot/* packages.

## Configuration

```json
{
    ...
    "extra": {
        ...
        "symfony": {
            ...
            "endpoint": [
                "https://api.github.com/repos/dontdrinkandroot/symfony-flex-recipes/contents/index.json",
                "flex://defaults"
            ]
            ...
        },
        ...
    }
    ...
}
```

## Generate new ref value

``php -r "echo bin2hex(random_bytes(20));"``
