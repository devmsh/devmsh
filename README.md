```php
class Devmsh extends Developer
{
    public String $name = "Mohammed Shurrab";
    public String $position = "CTO @ Extreme";

    public function knowledge()
    {
        return collect([
            "Laravel",
            "Flutter",
            "TDD",
            "Refactoring",
            "Serverless",
        ]);
    }

    public function contacts()
    {
        return collect([
            "twitter" => "https://twitter.com/devmsh",
            "github" => "https://github.com/devmsh",
        ]);
    }
    
    public function publications()
    {
        return collect([
            "medium" => "https://medium.com/@devmsh",
            "podcast" => "https://reds-talk-podcast.simplecast.com/",
            "youtube" => "https://www.youtube.com/channel/UCm4QTRXViHlmWV4egG7Z0WQ/",
        ]);
    }
}
```

![Devmsh's github stats](https://github-readme-stats.vercel.app/api?username=devmsh)

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=devmsh.devmsh)
