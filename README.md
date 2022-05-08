- 👋 Hi, I’m @EA-Prosche
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
EA-Prosche/EA-Prosche is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=EA-Prosche&count_private=true&show_icons=true&theme=radical)](https://github.com/EA-Prosche/github-readme-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&theme=radical)](https://github.com/anuraghazra/github-readme-stats)



namespace EA-Prosche;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Qquicker',
                'position' => 'Founder'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Angular::class,
            ReactNative::class,
            TailwindCss::class,
            Aws::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
