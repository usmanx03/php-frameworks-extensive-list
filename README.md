# PHP Frameworks: A comprehensive list

A comprehensive list of PHP frameworks across all eras, from the earliest pre-MVC libraries to modern async and zero-boilerplate frameworks.

I put this list together to capture as many PHP frameworks, runtimes, and CMS ecosystems as I could find, from the early experiments to the tools people still build with today. The goal is not just to catalog names, but to learn from them, what worked, what failed, what the community embraced, what it rejected, and how ideas evolved over time. This is meant to be a living reference for anyone curious about the past, present, and possible future of PHP architecture. If you notice something missing (Very probable) or inaccurate, please open an issue or submit a pull request so I can keep the list as complete and useful as possible for everyone exploring the ecosystem.

---

## Modern & Active

| Framework | Description | Website |
|-----------|-------------|---------|
| **Laravel** | Full-stack MVC with elegant syntax, Blade templating, and Eloquent ORM (2011–present) | https://laravel.com |
| **Symfony** | Enterprise-grade component-based framework widely used for large applications (2005–present) | https://symfony.com |
| **CodeIgniter 4** | Lightweight modern MVC rebuilt from scratch for PHP 8+ (2020–present) | https://codeigniter.com |
| **CakePHP** | Convention-over-configuration MVC framework for rapid development (2005–present) | https://cakephp.org |
| **Yii** | High-performance component-based MVC with strong caching and Gii code generator (2008–present) | https://www.yiiframework.com |
| **Nette** | Secure, opinionated MVC framework with Latte templates and Tracy debugger (2004–present) | https://nette.org |
| **Phalcon** | High-performance framework delivered as a C extension (2012–present) | https://phalcon.io |
| **Slim** | Minimal PSR-based microframework for APIs and small services (2010–present) | https://www.slimframework.com |
| **Fat-Free Framework (F3)** | Ultra-light microframework with routing, ORM, and caching built in (2009–present) | https://fatfreeframework.com |
| **Laminas** | Modular enterprise framework, successor to Zend Framework (2019–present) | https://getlaminas.org |
| **Mezzio** | Middleware-centric PSR-15 pipeline framework, formerly Zend Expressive (2016–present) | https://docs.mezzio.dev |
| **Spiral** | High-performance framework with RoadRunner integration and CQRS support (2019–present) | https://spiral.dev |
| **Hyperf** | Coroutine-based high-performance framework built on Swoole (2019–present) | https://hyperf.io |
| **Leaf PHP** | Lightweight modern micro/full framework inspired by Laravel and Express (2019–present) | https://leafphp.dev |
| **ThinkPHP** | MVC framework popular in China with rapid development focus (2006–present) | https://www.thinkphp.cn |
| **Workerman** | Event-driven socket framework for real-time applications (2013–present) | https://www.workerman.net |

---

## Async / Runtime / Server

| Framework | Description | Website |
|-----------|-------------|---------|
| **Swoole** | Coroutine-based async PHP runtime enabling WebSockets and high concurrency (2013–present) | https://www.swoole.co.uk |
| **RoadRunner** | High-performance PHP application server and process manager (2019–present) | https://roadrunner.dev |
| **ReactPHP** | Event-driven async framework using an event loop (stable 2019–present) | https://reactphp.org |
| **Amp** | Non-blocking concurrency framework using fibers and promises (2016–present) | https://amphp.org |

---

## Active but Smaller / Niche / Regional

| Framework | Description | Website |
|-----------|-------------|---------|
| **Aphiria** | DDD-focused modular framework emphasizing clean architecture (2017–present) | https://aphiria.com |
| **Ubiquity** | Performance-focused MVC framework with automatic code generation (2018–present) | https://ubiquity.kobject.net |
| **Tempest** | Modern zero-boilerplate framework with auto-discovery features (2023–present) | https://tempestphp.com |
| **Trongate** | Productivity-focused MVC framework with minimal dependencies, no bloat (2021–present) | https://trongate.io |
| **Tina4** | Lightweight agile PHP framework with rapid scaffolding (2019–present) | https://tina4.com |
| **Pop PHP** | Modular MVC framework with many standalone components (2012–present) | https://www.popphp.org |
| **Aura** | Decoupled, framework-agnostic PHP library collection (2010–present) | https://auraphp.com |
| **Flight PHP** | Minimal routing-focused microframework (2010–low activity) | https://flightphp.com |
| **Windwalker** | RAD framework from the Joomla ecosystem (2015–present, niche) | https://windwalker.io |
| **UserFrosting** | Slim-based framework focused on user management (2014–present, niche) | https://userfrosting.com |
| **Opulence** | Modular MVC framework with emphasis on clean architecture (2016–low activity) | https://github.com/aphiria/aphiria |
| **PSX** | API-first framework with OpenAPI and SDK generation | https://phpsx.org |
| **BEAR.Sunday** | REST-centric framework built around resource-oriented architecture | https://bearsunday.github.io |
| **Yaf** | High-performance MVC framework implemented as a PHP extension | https://www.php.net/manual/en/book.yaf.php |
| **PHP Smart.Framework** | Full-stack framework combining PHP and JS architecture | https://smart-framework.net |
| **Innomatic** | Platform for building multi-tenant SaaS applications | https://innomatic.io |
| **QCubed** | RAD framework emphasizing code generation and database-driven apps | https://qcubed.com |
| **Wolff** | Extremely small microframework for simple applications | https://github.com/usmanhalalit/wolff |
| **Bullet** | Resource-oriented microframework for RESTful APIs | https://bulletphp.github.io |
| **ShortPHP** | Ultra-light (~4KB) minimal MVC framework | https://github.com/shortphp/shortphp |
| **Konstrukt** | Minimal framework focused on HTTP and hierarchical controllers | https://konstrukt.github.io |
| **League of Extraordinary Packages** | High-quality framework-agnostic package ecosystem (2013–present) | https://thephpleague.com |

---

## Maintenance Mode / Low Activity

| Framework | Description | Website |
|-----------|-------------|---------|
| **CodeIgniter** (original) | Lightweight MVC framework, original version predating CI4 (2006–maintenance) | https://codeigniter.com |
| **Lumen** | Lightweight Laravel microframework (2015–2021) | https://lumen.laravel.com/docs/11.x |
| **FuelPHP** | Modular HMVC framework with strong security features (2010–mostly inactive) | https://fuelphp.com |
| **PHPixie** | HMVC framework with modular components and ORM (2012–low activity) | https://phpixie.com |
| **SilverStripe Framework** | MVC framework powering SilverStripe CMS (2006–present) | https://www.silverstripe.org |
| **PRADO** | Event-driven component-based RAD framework (2004–maintenance) | https://pradoframework.net |
| **Contao Framework** | Accessible CMS framework with MVC foundation (2006–present) | https://contao.org |
| **TYPO3 Flow / Neos Flow** | Enterprise application framework extracted from TYPO3 (2005–present) | https://flow.neos.io |
| **ezComponents / Zeta Components** | Collection of high-quality reusable PHP components (2005–maintenance) | https://github.com/zetacomponents |
| **PEAR** | Foundational PHP package ecosystem predating Composer (2000–legacy) | https://pear.php.net |
| **Horde Framework** | Groupware-oriented framework and component library collection (2000–legacy) | https://www.horde.org |
| **Joomla Framework** | Decoupled MVC framework extracted from Joomla CMS (2013–present) | https://framework.joomla.org |
| **Webasyst** | PHP CMS and application platform (2003–legacy) | https://www.webasyst.com |
| **Zikula** | Modular application framework evolving into CMS (2001–legacy) | https://ziku.la |

---

## Legacy / Discontinued / EOL

| Framework | Description | Website |
|-----------|-------------|---------|
| **Zend Framework** | Enterprise MVC framework, now succeeded by Laminas (2006–EOL) | https://framework.zend.com |
| **Silex** | Symfony-based microframework (2011–EOL 2018) | https://silex.symfony.com |
| **Kohana / Koseven** | HMVC framework forked from CodeIgniter; Koseven is the community continuation (2007–discontinued) | https://kohanaframework.org |
| **Lithium (li₃)** | Flexible MVC framework inspired by CakePHP (2010–discontinued) | http://li3.me |
| **Agavi** | Enterprise MVC framework inspired by Java frameworks (2006–inactive) | http://www.agavi.org |
| **Solar** | Framework that later evolved into the Aura libraries (2005–discontinued) | http://solarphp.com |
| **Seagull** | Early OOP PHP framework for web applications (2003–discontinued) | http://seagullproject.org |
| **Mojavi** | Java-inspired MVC framework (2003–inactive) | http://mojavi.org |
| **Phrame** | Academic MVC PHP framework for teaching concepts (2002–discontinued) | — |
| **TinyMVC** | Extremely small educational MVC framework (2005–discontinued) | https://github.com/bcit-ci/TinyMVC |
| **WACT** | Component-based web application toolkit framework (2004–discontinued) | http://wact.sourceforge.net |
| **QCodo** | ORM-centric RAD framework, predecessor to QCubed (2005–discontinued) | http://www.qcodo.com |
| **Recess** | REST-first MVC framework (2009–discontinued) | http://www.recessframework.org |
| **Limonade** | Sinatra-inspired PHP microframework (2009–discontinued) | http://limonade-php.github.io |
| **Gyroscope** | Backend/admin-focused framework (2009–discontinued) | https://github.com/gyroscope/gyroscope |
| **PAT (PHP Application Tools)** | Early enterprise PHP framework (2001–discontinued) | http://www.php-tools.net |
| **PHPLib** | Pre-MVC PHP application library (pre-2000, obsolete) | http://phplib.sourceforge.net |
| **BlueShoes** | Early PHP application framework and library set (early 2000s–discontinued) | http://www.blueshoes.org |
| **Zoop** | Early PHP framework for rapid development (early 2000s–discontinued) | — |
| **PHPDevShell** | RAD framework for admin systems (early 2000s–discontinued) | http://phpdevshell.org |
| **Banshee** | Security-focused PHP framework/CMS (2003–discontinued) | https://www.banshee-php.org |
| **Packfire** | Rapid development framework for scaffolding apps | https://github.com/packfire/framework |

---

## CMS Frameworks

> CMS platforms that also serve as or expose a meaningful framework layer.

| CMS | Description | Website |
|-----|-------------|---------|
| **Drupal** | Enterprise CMS with strong modular architecture built on Symfony components (2001–present) | https://www.drupal.org |
| **TYPO3** | Enterprise CMS widely used in Europe (1998–present) | https://typo3.org |
| **Joomla** | Popular CMS with extensible MVC structure (2005–present) | https://www.joomla.org |
| **Concrete CMS** | User-friendly CMS with MVC foundation (2008–present) | https://www.concretecms.com |
| **ProcessWire** | Developer-friendly CMS with a powerful API | https://processwire.com |
| **OctoberCMS** | Laravel-based CMS focused on simplicity | https://octobercms.com |
| **PyroCMS** | Laravel-powered modular CMS platform | https://pyrocms.com |
| **Statamic** | Modern flat-file/Laravel CMS for developers | https://statamic.com |
| **Bolt CMS** | Simple Symfony-based CMS | https://boltcms.io |
| **Sulu** | Enterprise CMS built on Symfony | https://sulu.io |
| **SilverStripe CMS** | CMS built on SilverStripe Framework | https://www.silverstripe.org |
| **Contao** | Open-source CMS focused on accessibility | https://contao.org |

---

*Contributions welcome. If a framework is missing or a link is outdated, please open a PR.*
