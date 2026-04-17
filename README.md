pt### Hi there 👋

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
                'position' => 'Full Stack Software Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Html::class,
            Css::class,
            Javascript::class,
            Typescript::class,
            CraftCms::class,
            Laravel::class,
            ExpressionEngine::class,
            BigCommerce::class,
            Salesforce::class,
            NodeJs::class,
            Vue::class,
            Angular::class,
            React::class,
            NextJs::class,
            TailwindCss::class,
            Aws::class,
            Docker::class,
            MySql::class,
            PostgresQl::class,
            Java::class,
            UnifiNetworks::class
            AiClaude::class,
            AiChatGpt::class,
        ];
    }
}
```

Thanks for dropping by, hope you find some of my work interesting.
