### Hi there 👋

```php
<?php

namespace seandelaney

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Solspace',
                'position' => 'Full Stack Web Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Typescript::class,
            CraftCMS::class,
            Laravel::class,
            Vue::class,
            Angular::class,
            React::class,
            TailwindCss::class,
            Aws::class,
            Docker::class,
            MySQL::class,
            Java::class,
            UnifiNetworks:class
        ];
    }
}
```

Thanks for dropping by, hope you find some of my work interesting.
