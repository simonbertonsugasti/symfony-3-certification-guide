# Symfony 3 certification guide

Collections of links based on the topics included in the Symfony 3.4 certification exam.

More info: https://sensiolabs.com/en/symfony/certification.html

Inspired by the Symfony 2.3 certification guide of [jmolivas] (https://github.com/jmolivas/symfony-certification-guide)


#### **PHP**
* Object Oriented Programming  
http://php.net/manual/en/language.oop5.php
* Namespaces  
http://www.php.net/manual/en/language.namespaces.php  
https://knpuniversity.com/screencast/php-namespaces-in-120-seconds/namespaces
* Interfaces  
http://www.php.net/manual/en/language.oop5.interfaces.php
* Anonymous functions and closures  
http://www.php.net/manual/en/functions.anonymous.php
* Abstract classes  
http://www.php.net/manual/en/language.oop5.abstract.php
* Exception and error handling  
https://secure.php.net/manual/en/class.exception.php  
http://php.net/manual/en/language.exceptions.php
* Traits  
http://php.net/manual/en/language.oop5.traits.php
* PHP extensions  
http://php.net/manual/en/extensions.php
* SPL  
http://php.net/manual/en/book.spl.php
* Web security (XSS, CSRF, etc.)  
http://php.net/manual/en/security.php

---

#### **HTTP**
* Client / Server interaction  
http://symfony.com/doc/3.4/book/http_fundamentals.html
* Status codes  
http://en.wikipedia.org/wiki/List_of_HTTP_status_codes
* HTTP request  
http://symfony.com/doc/3.4/components/http_foundation/introduction.html#request
* HTTP response  
http://symfony.com/doc/3.4/components/http_foundation/introduction.html#response
* HTTP methods
https://www.w3.org/Protocols/rfc2616/rfc2616-sec9.html
* Cookies  
https://en.wikipedia.org/wiki/HTTP_cookie  
http://symfony.com/doc/3.4/components/http_foundation/introduction.html#setting-cookies
* Caching  
http://symfony.com/doc/3.4/http_cache.html
* Content negotiation  
https://developer.mozilla.org/en-US/docs/Web/HTTP/Content_negotiation  
http://symfony.com/doc/3.4/components/http_foundation/introduction.html#accessing-accept-headers-data
* Language detection  

---

#### **Symfony Architecture**
* Symfony Standard Edition  
http://symfony.com/distributions  
https://github.com/symfony/symfony-standard
* License  
http://symfony.com/doc/3.4/contributing/code/license.html
* Components  
http://symfony.com/doc/3.4/components/index.html
* Bundles  
http://symfony.com/doc/bundles/  
http://symfony.com/doc/3.4/cookbook/bundles/best_practices.html  
http://symfony.com/doc/3.4/quick_tour/the_architecture.html#understanding-the-bundle-system
* Bridges  
http://stackoverflow.com/questions/11888522/what-are-symfony-bridges-bundles-and-vendor
* Configuration  
http://symfony.com/doc/3.4/quick_tour/the_architecture.html  
http://symfony.com/doc/3.4/cookbook/configuration/index.html  
http://symfony.com/doc/3.4/cookbook/bundles/best_practices.html#configuration  
http://symfony.com/doc/3.4/cookbook/bundles/extension.html
* Code organization  
http://symfony.com/doc/3.4/quick_tour/the_architecture.html#understanding-the-directory-structure
* Request handling  
http://symfony.com/doc/3.4/book/http_fundamentals.html#the-journey-from-the-request-to-the-response
* Exception handling  
http://symfony.com/doc/3.4/cookbook/controller/error_pages.html
* Event dispatcher and kernel events  
http://symfony.com/doc/3.4/components/event_dispatcher/introduction.html  
http://symfony.com/doc/3.4/components/http_kernel/introduction.html
* Official best practices  
http://symfony.com/doc/3.4/best_practices/index.html
* Release management  
http://symfony.com/doc/3.4/contributing/community/releases.html
* Backward compatibility promise  
http://symfony.com/doc/3.4/contributing/code/bc.html
* Deprecations best practices  
http://symfony.com/blog/paving-the-way-for-symfony-3-with-the-deprecation-detector-tool

---

#### **Standardization**
* Release management and roadmap schedule  
http://symfony.com/doc/3.4/contributing/community/releases.html
* Framework interoperability and PSRs  
http://www.php-fig.org/psr/
* Naming conventions  
http://symfony.com/doc/3.4/contributing/code/standards.html#naming-conventions
* Coding standards  
http://symfony.com/doc/3.4/contributing/code/standards.html
* Third-party libraries integration  
http://symfony.com/doc/3.4/cookbook/bundles/installation.html
* Composer packages handling  
https://getcomposer.org/doc/00-intro.md#introduction  
http://symfony.com/doc/3.4/cookbook/composer.html
* Development best practices  
http://symfony.com/doc/3.4/cookbook/deployment/tools.html
* Framework overloading  
http://symfony.com/doc/3.4/cookbook/configuration/override_dir_structure.html  
http://symfony.com/doc/3.4/cookbook/bundles/inheritance.html  
http://symfony.com/doc/3.4/cookbook/bundles/override.html
* Semantic versioning  
http://semver.org/

---

#### **Bundles**
* Naming conventions  
http://symfony.com/doc/3.4/cookbook/bundles/best_practices.html#bundle-name
* Code organization  
http://symfony.com/doc/3.4/cookbook/bundles/best_practices.html#directory-structure
* Controllers  
http://symfony.com/doc/3.4/book/controller.html  
http://symfony.com/doc/3.4/cookbook/bundles/best_practices.html#controllers
* The views  
http://symfony.com/doc/3.4/quick_tour/the_view.html
* The resources  
http://symfony.com/doc/3.4/best_practices/web-assets.html
* Overriding default error pages  
http://symfony.com/doc/3.4/cookbook/controller/error_pages.html
* Bundle inheritance  
http://symfony.com/doc/3.4/cookbook/bundles/inheritance.html
* Event dispatcher and kernel events  
http://symfony.com/doc/3.4/cookbook/event_dispatcher/event_listener.html
* Semantic configuration and compiler passes  
http://symfony.com/doc/3.4/cookbook/service_container/compiler_passes.html  
http://symfony.com/doc/3.4/components/dependency_injection/compilation.html

---

#### **Controllers**
* Naming conventions  
http://symfony.com/doc/3.4/book/routing.html#controller-string-syntax
* The base Controller class  
http://symfony.com/doc/3.4/book/controller.html#the-base-controller-class
* The request  
http://symfony.com/doc/3.4/components/http_foundation/introduction.html#request  
http://symfony.com/doc/3.4/book/controller.html#the-request-object
* The response  
http://symfony.com/doc/3.4/components/http_foundation/introduction.html#response  
http://symfony.com/doc/3.4/book/controller.html#the-response-object
* The cookies  
http://symfony.com/doc/3.4/components/http_foundation/introduction.html#setting-cookies
* The session  
http://symfony.com/doc/3.4/book/controller.html#managing-the-session  
http://symfony.com/doc/3.4/components/http_foundation/sessions.html
* The flash messages  
http://symfony.com/doc/3.4/book/controller.html#flash-messages  
http://symfony.com/doc/3.4/components/http_foundation/sessions.html#flash-messages
* HTTP redirects  
http://symfony.com/doc/3.4/book/controller.html#redirecting
* Internal redirects  
http://symfony.com/doc/3.4/book/controller.html#forwarding-to-another-controller
* Generate 404 pages  
http://symfony.com/doc/3.4/book/controller.html#managing-errors-and-404-pages  
http://symfony.com/doc/3.4/cookbook/controller/error_pages.html#customizing-the-404-page-and-other-error-pages
* File upload  
http://symfony.com/doc/3.4/cookbook/controller/upload_file.html
* Built-in internal controllers  
http://symfony.com/doc/3.4/book/controller.html#the-base-controller-class

---

#### **Routing**
* Configuration (YAML / XML / PHP & annotations)  
http://symfony.com/doc/3.4/book/routing.html#basic-route-configuration
* Restrict URL parameters  
http://symfony.com/doc/3.4/book/routing.html#routing-with-placeholders
* Set default values to URL parameters  
http://symfony.com/doc/3.4/book/routing.html#required-and-optional-placeholders
* Generate URL parameters  
http://symfony.com/doc/3.4/book/routing.html#generating-urls
* Trigger redirects  
http://symfony.com/doc/3.4/book/controller.html#redirecting  
http://symfony.com/doc/3.4/cookbook/routing/redirect_in_config.html
* Special internal routing attributes  
http://symfony.com/doc/3.4/cookbook/routing/extra_information.html
* Domain name matching  
http://symfony.com/doc/3.4/components/routing/hostname_pattern.html
* Conditional request matching  
http://symfony.com/doc/3.4/book/routing.html#completely-customized-route-matching-with-conditions
* HTTP methods matching  
http://symfony.com/doc/3.4/cookbook/routing/method_parameters.html
* User's locale guessing  
http://symfony.com/doc/3.4/reference/forms/types/locale.html
* Router debugging  
http://symfony.com/doc/3.4/book/routing.html#visualizing-debugging-routes

---

#### **Templating with Twig**
* Auto escaping  
http://twig.sensiolabs.org/doc/tags/autoescape.html  
http://symfony.com/doc/3.4/book/templating.html#output-escaping-in-twig
* Template inheritance  
http://twig.sensiolabs.org/doc/tags/extends.html  
http://twig.sensiolabs.org/doc/templates.html#template-inheritance  
http://symfony.com/doc/3.4/book/templating.html#template-inheritance-and-layouts
* Global variables  
http://symfony.com/doc/3.4/cookbook/templating/global_variables.html
* Filters and functions  
http://twig.sensiolabs.org/doc/filters/index.html  
http://symfony.com/doc/3.4/cookbook/templating/twig_extension.html
* Template includes  
http://twig.sensiolabs.org/doc/tags/include.html
* Loops and conditions  
http://twig.sensiolabs.org/doc/tags/for.html  
http://twig.sensiolabs.org/doc/tags/if.html
* Urls generation  
http://symfony.com/doc/3.4/book/routing.html#generating-urls-from-a-template  
http://symfony.com/doc/3.4/book/templating.html#linking-to-pages
* Controller rendering  
http://symfony.com/doc/3.4/book/templating.html#embedding-controllers
* Translations and pluralization  
http://symfony.com/doc/3.4/book/translation.html#translations-in-templates
* String interpolation  
http://twig.sensiolabs.org/doc/templates.html#string-interpolation
* Assets management  
http://symfony.com/doc/3.4/best_practices/web-assets.html
* Debugging variables  
http://twig.sensiolabs.org/doc/functions/dump.html

---

#### **Forms**
* Forms creation  
http://symfony.com/doc/3.4/book/forms.html#creating-a-simple-form
* Forms handling  
http://symfony.com/doc/3.4/book/forms.html#handling-form-submissions  
http://symfony.com/doc/3.4/best_practices/forms.html#handling-form-submits
* Form types  
http://symfony.com/doc/3.4/book/forms.html#creating-form-classes  
http://symfony.com/doc/3.4/book/forms.html#built-in-field-types
* Forms rendering with Twig  
http://symfony.com/doc/3.4/book/forms.html#rendering-a-form-in-a-template
* Forms theming  
http://symfony.com/doc/3.4/cookbook/form/form_customization.html#what-are-form-themes  
http://symfony.com/doc/3.4/book/forms.html#form-theming
* CSRF protection  
http://symfony.com/doc/3.4/book/forms.html#csrf-protection
* Handling file upload  
http://symfony.com/doc/3.4/cookbook/controller/upload_file.html  
http://symfony.com/doc/3.4/reference/forms/types/file.html
* Built-in form types  
http://symfony.com/doc/3.4/reference/forms/types.html
* Data transformers  
http://symfony.com/doc/3.4/cookbook/form/data_transformers.html
* Form events  
http://symfony.com/doc/3.4/components/form/form_events.html  
http://symfony.com/doc/3.4/cookbook/form/dynamic_form_modification.html
* Form type extensions  
http://symfony.com/doc/3.4/cookbook/form/create_form_type_extension.html

---

#### **Data Validation**
* PHP object validation  
http://symfony.com/doc/3.4/book/validation.html#the-basics-of-validation
* Built-in validation constraints  
http://symfony.com/doc/3.4/reference/constraints.html
* Validation scopes  
http://symfony.com/doc/3.4/cookbook/validation/custom_constraint.html#class-constraint-validator
* Validation groups  
http://symfony.com/doc/3.4/book/validation.html#validation-groups
* Group sequence  
http://symfony.com/doc/3.4/book/validation.html#group-sequence
* Custom callback validators  
http://symfony.com/doc/3.4/cookbook/validation/custom_constraint.html  
http://symfony.com/doc/3.4/reference/constraints/Callback.html  
https://knpuniversity.com/screencast/question-answer-day/custom-validation-property-path
* Violations builder  
http://symfony.com/doc/3.4/cookbook/validation/custom_constraint.html#creating-the-validator-itself

---

#### **Dependency Injection**
* Service container  
http://symfony.com/doc/3.4/book/service_container.html
* Built-in services  
http://symfony.com/doc/3.4/book/service_container.html#debugging-services
* Configuration parameters  
http://symfony.com/doc/3.4/components/dependency_injection/parameters.html  
http://symfony.com/doc/3.4/components/dependency_injection/introduction.html#setting-up-the-container-with-configuration-files
* Services registration  
http://symfony.com/doc/3.4/book/service_container.html#creating-configuring-services-in-the-container
* Tags  
http://symfony.com/doc/3.4/book/service_container.html#tags  
http://symfony.com/doc/3.4/reference/dic_tags.html
* Semantic configuration  
http://symfony.com/doc/3.4/cookbook/bundles/extension.html
* Factories  
http://symfony.com/doc/3.4/components/dependency_injection/factories.html
* Compiler passes  
http://symfony.com/doc/3.4/cookbook/service_container/compiler_passes.html  
http://symfony.com/doc/3.4/components/dependency_injection/compilation.html
* Services autowiring  
http://symfony.com/doc/3.4/components/dependency_injection/autowiring.html

---

#### **Security**
* Authentication  
http://symfony.com/doc/3.4/components/security/authentication.html  
http://symfony.com/doc/3.4/book/security.html#how-security-works-authentication-and-authorization
http://symfony.com/doc/3.4/cookbook/security/index.html#authentication-identifying-logging-in-the-user
* Authorization  
http://symfony.com/doc/3.4/components/security/authorization.html  
http://symfony.com/doc/3.4/book/security.html#authorization
http://symfony.com/doc/3.4/cookbook/security/index.html#authorization-denying-access
* Configuration  
http://symfony.com/doc/3.4/reference/configuration/security.html
* Providers  
http://symfony.com/doc/3.4/book/security.html#where-do-users-come-from-user-providers
* Firewalls  
http://symfony.com/doc/3.4/book/security.html#firewalls-authentication  
http://symfony.com/doc/3.4/components/security/firewall.html
* Users  
http://symfony.com/doc/3.4/book/security.html#users
* Passwords encoders  
http://symfony.com/doc/3.4/book/security.html#encoding-the-user-s-password
* Roles  
http://symfony.com/doc/3.4/components/security/authorization.html#roles  
http://symfony.com/doc/3.4/book/security.html#roles
* Access Control Rules  
http://symfony.com/doc/3.4/book/security.html#access-control-in-templates  
http://symfony.com/doc/3.4/book/security.html#access-control-in-controllers
* Guard authenticators  
http://symfony.com/doc/3.4/cookbook/security/guard-authentication.html  
https://knpuniversity.com/screencast/guard
* Voters and voting strategies  
http://symfony.com/doc/3.4/components/security/authorization.html  
http://symfony.com/doc/3.4/cookbook/security/voters.html

---

#### **HTTP Caching**
* Cache types (browser, proxies and reverse proxies)  
http://symfony.com/doc/3.4/book/http_cache.html#types-of-caches
* Expiration (Expires, Cache-control)  
http://symfony.com/doc/3.4/book/http_cache.html#expiration
* Validation (ETag, Last-Modified)  
http://symfony.com/doc/3.4/book/http_cache.html#validation
* Client side caching  
http://symfony.com/doc/3.4/book/http_cache.html#types-of-caches
* Server side caching  
http://symfony.com/doc/3.4/book/http_cache.html#gateway-caches
* Edge Side Includes  
http://symfony.com/doc/3.4/book/http_cache.html#using-edge-side-includes

---

#### **Console**
* Built-in commands  
http://symfony.com/doc/3.4/components/console/usage.html#built-in-commands
* Custom commands  
http://symfony.com/doc/3.4/components/console.html#creating-a-console-application
http://symfony.com/doc/3.4/console.html
* Configuration  
http://symfony.com/doc/3.4/console.html#configuring-the-command
* Options and arguments  
http://symfony.com/doc/3.4/console/input.html#using-command-arguments
http://symfony.com/doc/3.4/console/input.html#using-command-options
http://symfony.com/doc/3.4/components/console/console_arguments.html
* Input and Output objects  
http://symfony.com/doc/3.4/console.html#console-input
http://symfony.com/doc/3.4/console.html#executing-the-command
* Built-in helpers  
http://symfony.com/doc/3.4/components/console/helpers/index.html
* Console events  
http://symfony.com/doc/3.4/components/console/events.html
* Verbosity levels  
http://symfony.com/doc/3.4/console/verbosity.html

---

#### **Automated tests**
* Unit tests with PHPUnit  
http://symfony.com/doc/3.4/book/testing.html#the-phpunit-testing-framework
* Functional tests with PHPUnit  
http://symfony.com/doc/3.4/book/testing.html#functional-tests
* Client object  
http://symfony.com/doc/3.4/book/testing.html#working-with-the-test-client
* Crawler object  
http://symfony.com/doc/3.4/book/testing.html#the-crawler
* Profile object  
http://symfony.com/doc/3.4/book/testing.html#accessing-the-profiler-data  
http://symfony.com/doc/3.4/cookbook/testing/profiling.html
* Framework objects access  
http://symfony.com/doc/3.4/book/testing.html#accessing-internal-objects  
http://symfony.com/doc/3.4/book/testing.html#accessing-the-container
* Client configuration  
http://symfony.com/doc/3.4/book/testing.html#testing-configuration
* Request and response objects introspection  
http://symfony.com/doc/3.4/book/testing.html#accessing-internal-objects
* PHPUnit bridge  
http://symfony.com/doc/3.4/components/phpunit_bridge.html
* Handling legacy deprecated code  
http://symfony.com/doc/3.4/components/phpunit_bridge.html#mark-tests-as-legacy

---

#### **Miscellaneous**
* Error handling  
http://symfony.com/doc/3.4/cookbook/controller/error_pages.html
* Code debugging  
http://symfony.com/doc/3.4/cookbook/debugging.html
* Deployment best practices  
http://symfony.com/doc/3.4/cookbook/deployment/tools.html
* Process  
http://symfony.com/doc/3.4/components/process.html
* Serializer  
http://symfony.com/doc/3.4/serializer.html  
http://symfony.com/doc/3.4/components/serializer.html
* Data collectors  
http://symfony.com/doc/3.4/cookbook/profiler/data_collector.html
* Web Profiler and Web Debug Toolbar  
http://symfony.com/blog/new-in-symfony-2-8-redesigned-web-debug-toolbar  
http://symfony.com/doc/3.4/reference/configuration/web_profiler.html
* Internationalization and localization  
http://symfony.com/doc/3.4/translation.html  
http://symfony.com/doc/3.4/best_practices/i18n.html

