# Laravel, after the happy path - @tegos

I'm a Laravel/PHP backend engineer. I write about the gotchas, perf cliffs, and quiet design choices production teaches you. The stuff framework docs skip.

- Articles: [dev.to/tegos](https://dev.to/tegos)
- LinkedIn: [linkedin.com/in/tegos](https://www.linkedin.com/in/tegos)
- Personal GitHub: [github.com/tegos](https://github.com/tegos)

Each post is its own repo. Prose in `1-article.md`, runnable code when it helps, MIT.

## Featured

- [PHP 8.5 Pipe Operator (`|>`) - Is It Worth Using?](https://dev.to/tegos/php-85-pipe-operator-is-it-worth-using-4gig) - Benchmarked it inside a Laravel app. The verdict surprised me.
- [Why I Avoid PHP Traits (And What I Use Instead)](https://dev.to/tegos/why-i-avoid-php-traits-and-what-i-use-instead-1288) - Look like reuse, behave like inheritance, kill testability.
- [Don't Let Your Staging Server Die: Separate Task Scheduling in Laravel](https://dev.to/tegos/dont-let-your-staging-server-die-separate-task-scheduling-in-laravel-420o) - One config flag that stops staging from chewing through resources for nothing.
- [Battling Laravel's Sneaky DELETEs](https://dev.to/tegos/battling-laravels-sneaky-deletes-how-i-got-order-by-and-limit-to-play-nice-with-joins-ng9) - What happens when `ORDER BY` + `LIMIT` + joins hit Eloquent's DELETE.
- [Laravel Actions and Services](https://dev.to/tegos/laravel-actions-and-services-360d) - When to reach for an Action vs a Service. Plus the mental model that keeps them from collapsing into each other.
- [Reincarnating a Decade-Old jQuery Project](https://dev.to/tegos/reincarnating-a-decade-old-jquery-project-26ob) - Case study. Ported a client app from jQuery + sprite atlas to Vue 3 + TS + Pinia. Side-by-side GIFs.

## By topic

### Laravel performance
- [Laravel `whereDate()` Silently Kills Your Index](https://dev.to/tegos/laravel-wheredate-silently-kills-your-index-2lnf)
- [`whereHas()` vs `whereRelation()`: Readability Over Shortcuts](https://dev.to/tegos/wherehas-vs-whererelation-readability-over-shortcuts-1gk0)
- [Laravel Cache Tip: Avoid Redundant has/missing Calls](https://dev.to/tegos/laravel-cache-tip-avoid-redundant-hasmissing-calls-4hi1)
- [Why `telescope:clear` Is Slow and How to Reclaim Disk in Seconds](https://dev.to/tegos/why-telescopeclear-is-slow-and-how-to-reclaim-disk-in-seconds-26of)
- [Optimize Vendor Folder Size](https://dev.to/tegos/optimize-vendor-folder-size-1m01)
- [Don't Let Your Staging Server Die: Separate Task Scheduling](https://dev.to/tegos/dont-let-your-staging-server-die-separate-task-scheduling-in-laravel-420o)

### Testing
- [How to Test for Equal JSON Columns in Laravel Models](https://dev.to/tegos/how-to-test-for-equal-json-columns-in-laravel-models-24e)
- [Testing Temporary URLs in Laravel Storage](https://dev.to/tegos/testing-temporary-urls-in-laravel-storage-20p7)
- [Freezing Time: Testing Laravel Temporary Storage URLs](https://dev.to/tegos/freezing-time-testing-laravel-temporary-storage-urls-13n1)
- [Stop Flaky Tests: Freeze Time in Laravel](https://dev.to/tegos/stop-flaky-tests-freeze-time-in-laravel-testing-1cnj)
- [Using PHP Backed Enums in Laravel with Testing](https://dev.to/tegos/using-php-backed-enums-in-laravel-with-testing-1f6)
- [Why Laravel Can't Guess Your Factory Relationships](https://dev.to/tegos/why-laravel-cant-guess-your-factory-relationships-4keb)
- [Hidden Issue with `whereFulltext` and RefreshDatabase](https://dev.to/tegos/hidden-issue-with-wherefulltext-and-refreshdatabase-in-laravel-2p4f)
- [Detecting Forbidden Functions in Laravel with PHPUnit](https://dev.to/tegos/detecting-forbidden-functions-in-laravel-with-phpunit-4n6f)
- [Laravel Validation `after()` - After What, Exactly?](https://dev.to/tegos/laravel-validation-after-after-what-exactly-28fa)

### Security
- [`hash_equals('', '')` Is true: When an Empty Config Opens Basic Auth](https://dev.to/tegos/hashequals-is-true-when-an-empty-config-opens-basic-auth-34c6)
- [bcrypt and Laravel: 72 Bytes, Not 72 Characters](https://dev.to/tegos/bcrypt-and-laravel-72-bytes-not-72-characters-3jb1)
- [Composer Update Is Not Safe Anymore](https://dev.to/tegos/composer-update-is-not-safe-anymore-2bcf)

### Deployment / ops
- [From 20 to 24 LTS: Safe Way to Upgrade Ubuntu on DigitalOcean](https://dev.to/tegos/from-20-to-24-lts-safe-way-to-upgrade-ubuntu-on-digitalocean-4gb)
- [Seamless Nuxt 2 Deployment with GitLab CI/CD and DigitalOcean](https://dev.to/tegos/seamless-nuxt-2-deployment-a-step-by-step-guide-with-gitlab-cicd-and-digitalocean-441d)

### PHP language
- [PHP 8.5 Pipe Operator (`|>`) - Is It Worth Using?](https://dev.to/tegos/php-85-pipe-operator-is-it-worth-using-4gig)
- [PHP Generics Already Exist: They're Just Hidden in PHPDoc](https://dev.to/tegos/php-generics-already-exist-theyre-just-hidden-in-phpdoc-2l0c)
- [Why I Avoid PHP Traits (And What I Use Instead)](https://dev.to/tegos/why-i-avoid-php-traits-and-what-i-use-instead-1288)
- [PHP Enums Are Not Your Bottleneck (Here's Proof)](https://dev.to/tegos/php-enums-are-not-your-bottleneck-heres-proof-1887)

### Architecture / patterns
- [Laravel Actions and Services](https://dev.to/tegos/laravel-actions-and-services-360d)
- [Battling Laravel's Sneaky DELETEs](https://dev.to/tegos/battling-laravels-sneaky-deletes-how-i-got-order-by-and-limit-to-play-nice-with-joins-ng9)
- [`$fillable` Has No Context: Why Mass Assignment Breaks Down at Scale](https://dev.to/tegos/fillable-has-no-context-why-mass-assignment-breaks-down-at-scale-3lmj)
- [Detect Unused Classes in Laravel](https://dev.to/tegos/detect-unused-classes-in-laravel-2jjm)
- [Managing Hierarchical Data in Laravel](https://dev.to/tegos/managing-hierarchical-data-in-laravel-b9k)
- [Pessimistic & Optimistic Locking in Laravel](https://dev.to/tegos/pessimistic-optimistic-locking-in-laravel-23dk)
- [Should You Use Laravel Seeders/Factories in Production?](https://dev.to/tegos/should-you-use-laravel-seedersfactories-in-production-51ai)
- [Tip for Using `incrementEach` in Laravel](https://dev.to/tegos/tip-for-using-incrementeach-in-laravel-3mni)
- [Reincarnating a Decade-Old jQuery Project](https://dev.to/tegos/reincarnating-a-decade-old-jquery-project-26ob)
- [Hunting Elephants Again: Reviving a Dead Travian Bot with an AI Agent](https://dev.to/tegos/hunting-elephants-again-reviving-a-dead-travian-bot-with-an-ai-agent-4b4l)

### Packages
- [Efficiently Managing Telescope Entries with laravel-telescope-flusher](https://dev.to/tegos/efficiently-managing-telescope-entries-with-laravel-telescope-flusher-484a)
- [Managing Mailboxes in Laravel Using ImapEngine](https://dev.to/tegos/managing-mailboxes-in-laravel-using-imapengine-17c8)
- [wayback-video: Turn Any Site's History into a Video](https://dev.to/tegos/wayback-video-turn-any-sites-history-into-a-video-3542)

## All articles (by category, newest first)

<!-- BEGIN:all-articles -->
### Laravel performance

- 2026-04 - [Why `telescope:clear` Is Slow and How to Reclaim Disk in Seconds](https://dev.to/tegos/why-telescopeclear-is-slow-and-how-to-reclaim-disk-in-seconds-26of) - [source](https://github.com/tegos-blog/article-telescope-clear-slow-reclaim-disk)
- 2026-04 - [Laravel `whereDate()` Silently Kills Your Index](https://dev.to/tegos/laravel-wheredate-silently-kills-your-index-2lnf) - [source](https://github.com/tegos-blog/article-laravel-where-date-kills-your-index)
- 2026-01 - [`whereHas()` vs `whereRelation()`: Readability Over Shortcuts](https://dev.to/tegos/wherehas-vs-whererelation-readability-over-shortcuts-1gk0) - [source](https://github.com/tegos-blog/article-where-has-vs-where-relation-readability-over-shortcuts)
- 2025-11 - [Don't Let Your Staging Server Die: Separate Task Scheduling in Laravel](https://dev.to/tegos/dont-let-your-staging-server-die-separate-task-scheduling-in-laravel-420o) - [source](https://github.com/tegos-blog/article-dont-let-your-staging-server-die-separate-task-scheduling-in-laravel)
- 2025-09 - [Laravel Cache Tip: Avoid Redundant has/missing Calls](https://dev.to/tegos/laravel-cache-tip-avoid-redundant-hasmissing-calls-4hi1) - [source](https://github.com/tegos-blog/article-laravel-cache-tip-avoid-redundant-has-missing-calls)
- 2025-08 - [Optimize Vendor Folder Size](https://dev.to/tegos/optimize-vendor-folder-size-1m01) - [source](https://github.com/tegos-blog/article-optimize-vendor-folder-size)

### Testing

- 2026-01 - [Why Laravel Can't Guess Your Factory Relationships](https://dev.to/tegos/why-laravel-cant-guess-your-factory-relationships-4keb) - [source](https://github.com/tegos-blog/article-why-laravel-can-t-guess-your-factory-relationships)
- 2026-01 - [Stop Flaky Tests: Freeze Time in Laravel Testing](https://dev.to/tegos/stop-flaky-tests-freeze-time-in-laravel-testing-1cnj) - [source](https://github.com/tegos-blog/article-stop-flaky-tests-freeze-time-in-laravel-testing)
- 2025-11 - [Laravel Validation `after()` - After What, Exactly?](https://dev.to/tegos/laravel-validation-after-after-what-exactly-28fa) - [source](https://github.com/tegos-blog/article-laravel-validation-after-after-what-exactly)
- 2025-03 - [Detecting Forbidden Functions in Laravel with PHPUnit](https://dev.to/tegos/detecting-forbidden-functions-in-laravel-with-phpunit-4n6f) - [source](https://github.com/tegos-blog/article-detecting-forbidden-functions-in-laravel-with-phpunit)
- 2025-02 - [Using PHP Backed Enums in Laravel with Testing](https://dev.to/tegos/using-php-backed-enums-in-laravel-with-testing-1f6) - [source](https://github.com/tegos-blog/article-using-php-backed-enums-in-laravel-with-testing)
- 2025-02 - [Hidden Issue with `whereFulltext` and RefreshDatabase in Laravel](https://dev.to/tegos/hidden-issue-with-wherefulltext-and-refreshdatabase-in-laravel-2p4f) - [source](https://github.com/tegos-blog/article-hidden-issue-with-where-fulltext-and-refresh-database-in-laravel)
- 2025-01 - [Freezing Time: Testing Laravel Temporary Storage URLs](https://dev.to/tegos/freezing-time-testing-laravel-temporary-storage-urls-13n1) - [source](https://github.com/tegos-blog/article-freezing-time-testing-laravel-temporary-storage-urls)
- 2025-01 - [Testing Temporary URLs in Laravel Storage](https://dev.to/tegos/testing-temporary-urls-in-laravel-storage-20p7) - [source](https://github.com/tegos-blog/article-testing-temporary-urls-in-laravel-storage)
- 2025-01 - [How to Test for Equal JSON Columns in Laravel Models](https://dev.to/tegos/how-to-test-for-equal-json-columns-in-laravel-models-24e) - [source](https://github.com/tegos-blog/article-laravel-compare-json)

### Security

- 2026-08 - [`hash_equals('', '')` Is true: When an Empty Config Opens Basic Auth](https://dev.to/tegos/hashequals-is-true-when-an-empty-config-opens-basic-auth-34c6) - [source](https://github.com/tegos-blog/article-hash-equals-empty)
- 2026-06 - [bcrypt and Laravel: 72 Bytes, Not 72 Characters](https://dev.to/tegos/bcrypt-and-laravel-72-bytes-not-72-characters-3jb1) - [source](https://github.com/tegos-blog/article-bcrypt-laravel-password-bytes)
- 2026-06 - [Composer Update Is Not Safe Anymore](https://dev.to/tegos/composer-update-is-not-safe-anymore-2bcf) - [source](https://github.com/tegos-blog/article-safe-composer-update)

### Deployment / ops

- 2025-11 - [From 20 to 24 LTS: Safe Way to Upgrade Ubuntu on DigitalOcean](https://dev.to/tegos/from-20-to-24-lts-safe-way-to-upgrade-ubuntu-on-digitalocean-4gb) - [source](https://github.com/tegos-blog/article-from-20-to-24-lts-safe-way-to-upgrade-ubuntu-on-digital-ocean)
- 2024-12 - [Seamless Nuxt 2 Deployment: A Step-by-Step Guide with GitLab CI/CD and DigitalOcean](https://dev.to/tegos/seamless-nuxt-2-deployment-a-step-by-step-guide-with-gitlab-cicd-and-digitalocean-441d) - [source](https://github.com/tegos-blog/article-seamless-nuxt-2-deployment)

### PHP language

- 2026-06 - [PHP Generics Already Exist: They're Just Hidden in PHPDoc](https://dev.to/tegos/php-generics-already-exist-theyre-just-hidden-in-phpdoc-2l0c) - [source](https://github.com/tegos-blog/article-php-generics-rfc)
- 2026-03 - [PHP Enums Are Not Your Bottleneck (Here's Proof)](https://dev.to/tegos/php-enums-are-not-your-bottleneck-heres-proof-1887) - [source](https://github.com/tegos-blog/article-php-enums-are-not-your-bottleneck-here-s-proof)
- 2026-02 - [Why I Avoid PHP Traits (And What I Use Instead)](https://dev.to/tegos/why-i-avoid-php-traits-and-what-i-use-instead-1288) - [source](https://github.com/tegos-blog/article-why-i-avoid-php-traits)
- 2025-12 - [PHP 8.5 Pipe Operator (`|>`) - Is It Worth Using?](https://dev.to/tegos/php-85-pipe-operator-is-it-worth-using-4gig) - [source](https://github.com/tegos-blog/article-php-8-5-pipe-operator-is-it-worth-using)

### Architecture / patterns

- 2026-07 - [Hunting Elephants Again: Reviving a Dead Travian Bot with an AI Agent](https://dev.to/tegos/hunting-elephants-again-reviving-a-dead-travian-bot-with-an-ai-agent-4b4l) - [source](https://github.com/tegos-blog/article-hunting-elephants-again)
- 2026-05 - [Reincarnating a Decade-Old jQuery Project](https://dev.to/tegos/reincarnating-a-decade-old-jquery-project-26ob) - [source](https://github.com/tegos-blog/article-burger-reborn)
- 2026-04 - [`$fillable` Has No Context: Why Mass Assignment Breaks Down at Scale](https://dev.to/tegos/fillable-has-no-context-why-mass-assignment-breaks-down-at-scale-3lmj) - [source](https://github.com/tegos-blog/article-mass-assignment-problem-in-laravel)
- 2025-10 - [Battling Laravel's Sneaky DELETEs: How I Got ORDER BY and LIMIT to Play Nice with Joins](https://dev.to/tegos/battling-laravels-sneaky-deletes-how-i-got-order-by-and-limit-to-play-nice-with-joins-ng9) - [source](https://github.com/tegos-blog/article-battling-laravels-sneaky-deletes)
- 2025-08 - [Laravel Actions and Services](https://dev.to/tegos/laravel-actions-and-services-360d) - [source](https://github.com/tegos-blog/article-laravel-actions-and-services)
- 2025-06 - [Managing Hierarchical Data in Laravel](https://dev.to/tegos/managing-hierarchical-data-in-laravel-b9k) - [source](https://github.com/tegos-blog/article-laravel-managing-hierarchical-data)
- 2025-04 - [Pessimistic & Optimistic Locking in Laravel](https://dev.to/tegos/pessimistic-optimistic-locking-in-laravel-23dk) - [source](https://github.com/tegos-blog/article-pessimistic-optimistic-locking-in-laravel)
- 2025-04 - [Should You Use Laravel Seeders/Factories in Production?](https://dev.to/tegos/should-you-use-laravel-seedersfactories-in-production-51ai) - [source](https://github.com/tegos-blog/article-should-you-use-laravel-seeders-factories-in-production)
- 2025-02 - [Tip for Using `incrementEach` in Laravel](https://dev.to/tegos/tip-for-using-incrementeach-in-laravel-3mni) - [source](https://github.com/tegos-blog/article-tip-for-using-increment-each-in-laravel)
- 2025-02 - [Detect Unused Classes in Laravel](https://dev.to/tegos/detect-unused-classes-in-laravel-2jjm) - [source](https://github.com/tegos-blog/article-detect-unused-classes-in-laravel)

### Packages

- 2026-06 - [wayback-video: Turn Any Site's History into a Video](https://dev.to/tegos/wayback-video-turn-any-sites-history-into-a-video-3542) - [source](https://github.com/tegos-blog/article-wayback-video)
- 2025-03 - [Managing Mailboxes in Laravel Using ImapEngine](https://dev.to/tegos/managing-mailboxes-in-laravel-using-imapengine-17c8) - [source](https://github.com/tegos-blog/article-managing-mailboxes-in-laravel-using-imap-engine)
- 2025-03 - [Efficiently Managing Telescope Entries with Laravel-Telescope-Flusher](https://dev.to/tegos/efficiently-managing-telescope-entries-with-laravel-telescope-flusher-484a) - [source](https://github.com/tegos-blog/article-efficiently-managing-telescope-entries-with-laravel-telescope-flusher)
<!-- END:all-articles -->
