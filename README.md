# Get ready to ace your Symfony 7 certification exam!

This repository provides a comprehensive set of AI-generated multiple-choice questions, based on the official Symfony 7 documentation, to help you prepare.

## 🚀 Features

-   **🤖 AI-Generated Content**: Questions and answers are generated from the official Symfony 7 documentation to ensure accuracy and relevance.
-   **📚 Comprehensive Coverage**: We cover all categories of the Symfony 7 certification exam.
-   **✅ Certificationy Compatible**: The YAML format is fully compatible with the [Certificationy](https://github.com/certificationy/certificationy-cli) training platform.
-   **🔄 Regular Updates**: We release new question sets regularly to keep the content fresh.
-   **📅 Version-Controlled**: A date-based versioning system helps you track releases.

## 🏁 Getting Started

### Prerequisites

Before you begin, you need to have the [Certificationy CLI](https://github.com/certificationy/certificationy-cli) installed. Please follow the instructions in their repository to get it set up.

### Installing the Pack

You can easily get this pack by cloning the repository or downloading the latest release.
```bash
# Clone the repository
git clone https://github.com/fmatsos/symfony-pack.git
```
Alternatively, you can download a specific release:
```bash
# Download the latest release
curl -L https://github.com/fmatsos/symfony-pack/releases/latest/download/symfony-pack.zip -o symfony-pack.zip
```
## Usage

Once you have the Certificationy CLI and this pack, you can start practicing. Each YAML file corresponds to a specific exam category and is filled with multiple-choice questions and detailed explanations.

You can add this pack to your Certificationy environment in one of two ways:

1.  **Add to Composer requirements:**

    ```json
    "require": {
        "fmatsos/symfony-pack": "^v25.7.10"
    }
    ```

2.  **Add the path to your Certificationy configuration file:**

    ```yaml
    # config.yml
    paths:
      # Add the path to your local clone of the pack
      - "/path/to/your/certificationy/symfony-pack"
    ```

## Topics Covered

This pack includes questions from all major Symfony 7 certification topics:

### PHP (up to PHP 8.2)
- PHP API
- OOP: classes, interfaces, traits, abstract classes
- Namespaces, closures, error/exception handling
- SPL and extensions

### HTTP
- Requests/responses, methods, status codes, headers, cookies
- Symfony HttpClient component
- Caching, language detection, content negotiation

### Symfony Architecture
- Flex, Components, Bridges
- Request/response lifecycle, Kernel, EventDispatcher
- Exception handling, naming conventions, BC promise, PSR compatibility

### Controllers
- `AbstractController`, request/response handling, flash/session/cookies
- Built-in controllers, argument resolvers, redirects

### Routing
- YAML + PHP attributes configuration
- Constraints, defaults, domain-based routing
- Internal routes, locale guessing, method matching

### Templating (Twig)
- Syntax (up to Twig 3.8), escaping, filters, inheritance, includes
- Translations, interpolation, rendering controllers
- Asset management and debugging

### Forms
- Built-in and custom form types
- Creation, validation, theming
- CSRF, transformers, file uploads, events

### Data Validation
- Constraints (built-in and custom), groups, group sequences
- Validation scopes and callbacks

### Dependency Injection
- Service container and registration (YAML + attributes)
- Autowiring, decoration, service locators, compiler passes, tags

### Security
- Authentication/authorization, firewalls, providers
- Password hashing, roles, access control, voters

### HTTP Caching
- Cache types (browser, proxy), ESI, headers (Expires, Cache-Control, ETag)
- Client/server caching, Symfony reverse proxy support

### Console
- Built-in and custom commands
- Arguments/options, helpers, verbosity, console events

### Automated Testing
- PHPUnit tests (unit + functional), Client and Crawler, Profiler
- Introspection of request/response, deprecated handling

### Miscellaneous
- DotEnv, ExpressionLanguage, Debugging, Deployment
- Messenger, Serializer, Mailer, Finder, Lock, Runtime
- Intl, Web Profiler, Toolbar, Clock component

## Versioning System

We use a date-based versioning system with the format `YY.M.DD.X`:

-   **YY**: Two-digit year (e.g., `25` for 2025)
-   **M**: Month (1-12)
-   **DD**: Day (01-31)
-   **X**: An increment for multiple releases on the same day

**Examples:**
-   `25.1.15`: First release on January 15, 2025.
-   `25.1.15.1`: Second release on January 15, 2025.

This system makes it easy to see how recent the question sets are.

## 🤝 Contributing & Support

Your contributions are welcome! While the questions are AI-generated, you can help by:
- Suggesting improvements for clarity.
- Proposing new question categories.
- Improving the documentation.

Please open an issue for you suggestions.

**For legal reasons you cannot ask to add questions. No pull requests are accepted.**

## 📝 Quality Assurance and Disclaimer

All questions are generated based on the official Symfony 7 documentation. If you find any issues, please report them via the issue tracker.

This pack is a study aid and should be used alongside official study materials and hands-on practice.

**It is not officially affiliated with Symfony or SensioLabs.**

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
