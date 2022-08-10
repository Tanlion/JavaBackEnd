### Table of Contents

| No. | Questions |
|---- | ---------
|  | [Core Java](#Core-Java)|
|1 | [Java Package Levels](#Package-Levels)|
|2 | [Types for Inner classes](#Types-for-Inner-classes)|
|3 | [Encapsulation, Polymorphism, Inheritance, Abstraction](#Encapsulation-Polymorphism-Inheritance-Abstraction)|
|4 | [Abstract Class](#Abstract-Class)|
|5 | [Interface](#Interface)|
|6 | [Difference between Interface and Abstract class](#Difference between Interface and Abstract class)|
|7 | [Constructor](#Constructor)|
|8 | [Serialization](#Serialization)|
|9 | [Sub-class and Super-class](#Sub-class and Super-class)|
|10| [Overloading and Overriding](#Overloading and Overriding)|
|11| [Functional Interface](#Functional Interface)|
|12| [Predicate](#Predicate)|
|13| [Lambda Expressions](#Lambda Expressions)|
|14| [Collections](#Collections)|
|15| [OOP](#OOP)|
|16| [SOLID Principle of OOD](#SOLID Principle of OOD)|
|17| [MVC](#MVC)|
|18| [Annotation](#Annotation)|
|19| [Comparable vs Comparator](#Comparable vs Comparator)|
|20| [ClassLoader](#ClassLoader)|
|21| [Reflection](#Reflection)|
|  | [Data Structure in Java](Data-Structure-in-Java)|
|22| [JVM Memory](#JVM Memory)|
|23| [JVM Runtime Memory Structure](#JVM Runtime Memory Structure)|
|24| [Metaspace in JVM](#Metaspace in JVM)|
|25| [Garbage Collection](#Garbage Collection)|
|26| [Eight primitive data type](#Eight primitive data type)|
|27| [How to create immutable class?](#How to create immutable class)|
|28| [How immutable clone (deep copy)?](#How immutable clone (deep copy))|
|29| [How to create/design singleton class](#How to create/design singleton class)|
|30| [HashCode() vs equals()](#HashCode() vs equals())|
|31| [List vs Set](#List vs Set)|
|32| [Difference between HashSet and TreeSet](#Difference between HashSet and TreeSet)|
|33| [ArrayList vs LinkedList](#ArrayList vs LinkedList)|
|34| [String Buffer vs String Builder](#String Buffer vs String Builder)|
|35| [Binary Tree](#Binary Tree)|
|36| [HashMap, HashTable, ConcurrentHashMap and Hash Collision](#HashMap, HashTable, ConcurrentHashMap and Hash Collision)|
|37| [HashMap, TreeMap, LinkedHashMap](#HashMap, TreeMap, LinkedHashMap)|
|38| [Collections](#Collections)|
|39| [Final, finally and finalize()](#final, finally and finalize())|
|40| [Volatile: keyword to ensure thread-safe](#volatile: keyword to ensure thread-safe)|
|41| [What is generics? Customized own generic type?](#What is generics? Customized own generic type?)|
|42| [Exception Handling](#Exception-Handling)|
|43| [Exception and Error](#Exception and Error)|
|44| [Ways to handle exceptions](#Ways to handle exceptions)|
|45| [Throws and Throw](#Throws and Throw)|
|46| [Java 8 new features](#java 8 new features)|
|47| [Stream in Java 8](#Stream in Java 8)|
|48| [Future Interface, Promise Class and CompletableFuture Class (non-blocking)](#Future Interface, Promise Class and CompletableFuture Class (non-blocking))|

|49| [What are observable creation functions?](#what-are-observable-creation-functions)|
|50| [What will happen if you do not supply handler for observer?](#what-will-happen-if-you-do-not-supply-handler-for-observer)|
|51| [What are angular elements?](#what-are-angular-elements)|
|52| [What is the browser support of Angular Elements?](#what-is-the-browser-support-of-angular-elements)|
|53| [What are custom elements?](#what-are-custom-elements)|
|54| [Do I need to bootstrap custom elements?](#do-i-need-to-bootstrap-custom-elements)|
|55| [Explain how custom elements works internally?](#explain-how-custom-elements-works-internally)|
|56| [How to transfer components to custom elements?](#how-to-transfer-components-to-custom-elements)|
|57| [What are the mapping rules between Angular component and custom element?](#what-are-the-mapping-rules-between-angular-component-and-custom-element)|
|58| [How do you define typings for custom elements?](#how-do-you-define-typings-for-custom-elements)|
|59| [What are dynamic components?](#what-are-dynamic-components)|
|60| [What are the various kinds of directives?](#what-are-the-various-kinds-of-directives)|
|61| [How do you create directives using CLI?](#how-do-you-create-directives-using-cli)|
|62| [Give an example for attribute directives?](#give-an-example-for-attribute-directives)|
|63| [What is Angular Router?](#what-is-angular-router)|
|64| [What is the purpose of base href tag?](#what-is-the-purpose-of-base-href-tag)|
|65| [What are the router imports?](#what-are-the-router-imports)|
|66| [What is router outlet?](#what-is-router-outlet)|
|67| [What are router links?](#what-are-router-links)|
|68| [What are active router links?](#what-are-active-router-links)|
|69| [What is router state?](#what-is-router-state)|
|70| [What are router events?](#what-are-router-events)|
|71| [What is activated route?](#what-is-activated-route)|
|72| [How do you define routes?](#how-do-you-define-routes)|
|73| [What is the purpose of Wildcard route?](#what-is-the-purpose-of-wildcard-route)|
|74| [Do I need a Routing Module always?](#do-i-need-a-routing-module-always)|
|75| [What is Angular Universal?](#what-is-angular-universal)|
|76| [What are different types of compilation in Angular?](#what-are-different-types-of-compilation-in-angular)|
|77| [What is JIT?](#what-is-jit)|
|78| [What is AOT?](#what-is-aot)|
|79| [Why do we need compilation process?](#why-do-we-need-compilation-process)|
|80| [What are the advantages with AOT?](#what-are-the-advantages-with-aot)|
|81| [What are the ways to control AOT compilation?](#what-are-the-ways-to-control-aot-compilation)|
|82| [What are the restrictions of metadata?](#what-are-the-restrictions-of-metadata)|
|83| [What are the three phases of AOT?](#what-are-the-three-phases-of-aot)|
|84| [Can I use arrow functions in AOT?](#can-i-use-arrow-functions-in-aot)|
|85| [What is the purpose of metadata json files?](#what-is-the-purpose-of-metadata-json-files)|
|86| [Can I use any javascript feature for expression syntax in AOT?](#can-i-use-any-javascript-feature-for-expression-syntax-in-aot)|
|87| [What is folding?](#what-is-folding)|
|88| [What are macros?](#what-are-macros)|
|89| [Give an example of few metadata errors?](#give-an-example-of-few-metadata-errors)|
|90| [What is metadata rewriting?](#what-is-metadata-rewriting)|
|91| [How do you provide configuration inheritance?](#how-do-you-provide-configuration-inheritance)|
|92| [How do you specify angular template compiler options?](#how-do-you-specify-angular-template-compiler-options)|
|93| [How do you enable binding expression validation?](#how-do-you-enable-binding-expression-validation)|
|94| [What is the purpose of any type cast function?](#what-is-the-purpose-of-any-type-cast-function)|
|95| [What is Non null type assertion operator?](#what-is-non-null-type-assertion-operator)|
|96| [What is type narrowing?](#what-is-type-narrowing)|
|97| [How do you describe various dependencies in angular application?](#how-do-you-describe-various-dependencies-in-angular-application)|
|98| [What is zone?](#what-is-zone)|
|99| [What is the purpose of common module?](#what-is-the-purpose-of-common-module)|
|100| [What is codelyzer?](#what-is-codelyzer)|
|101| [What is angular animation?](#what-is-angular-animation)|
|102| [What are the steps to use animation module?](#what-are-the-steps-to-use-animation-module)|
|103| [What is State function?](#what-is-state-function)|
|104| [What is Style function?](#what-is-style-function)|
|105| [What is the purpose of animate function?](#what-is-the-purpose-of-animate-function)|
|106| [What is transition function?](#what-is-transition-function)|
|107| [How to inject the dynamic script in angular?](#how-to-inject-the-dynamic-script-in-angular)|
|108| [What is a service worker and its role in Angular?](#what-is-a-service-worker-and-its-role-in-angular)|
|109| [What are the design goals of service workers?](#what-are-the-design-goals-of-service-workers)|
|110| [What are the differences between AngularJS and Angular with respect to dependency injection?](#what-are-the-differences-between-angularjs-and-angular-with-respect-to-dependency-injection)|
|111| [What is Angular Ivy?](#what-is-angular-ivy)|
|112| [What are the features included in ivy preview?](#what-are-the-features-included-in-ivy-preview)|
|113| [Can I use AOT compilation with Ivy?](#can-i-use-aot-compilation-with-ivy)|
|114| [What is Angular Language Service?](#what-is-angular-language-service)|
|115| [How do you install angular language service in the project?](#how-do-you-install-angular-language-service-in-the-project)|
|116| [Is there any editor support for Angular Language Service?](#is-there-any-editor-support-for-angular-language-service)|
|117| [Explain the features provided by Angular Language Service?](#explain-the-features-provided-by-angular-language-service)|
|118| [How do you add web workers in your application?](#how-do-you-add-web-workers-in-your-application)|
|119| [What are the limitations with web workers?](#what-are-the-limitations-with-web-workers)|
|120| [What is Angular CLI Builder?](#what-is-angular-cli-builder)|
|121| [What is a builder?](#what-is-a-builder)|
|122| [How do you invoke a builder?](#how-do-you-invoke-a-builder)|
|123| [How do you create app shell in Angular?](#how-do-you-create-app-shell-in-angular)|
|124| [What are the case types in Angular?](#what-are-the-case-types-in-angular)|
|125| [What are the class decorators in Angular?](#what-are-the-class-decorators-in-angular)|
|126| [What are class field decorators?](#what-are-class-field-decorators)|
|127| [What is declarable in Angular?](#what-is-declarable-in-angular)|
|128| [What are the restrictions on declarable classes?](#what-are-the-restrictions-on-declarable-classes)|
|129| [What is a DI token?](#what-is-a-di-token)|
|130| [What is Angular DSL?](#what-is-angular-dsl)|
|131| [What is an rxjs Subject?](#what-is-an-rxjs-Subject)|
|132| [What is Bazel tool?](#what-is-bazel-tool)|
|133| [What are the advantages of Bazel tool?](#what-are-the-advantages-of-bazel-tool)|
|134| [How do you use Bazel with Angular CLI?](#how-do-you-use-bazel-with-angular-cli)|
|135| [How do you run Bazel directly?](#how-do-you-run-bazel-directly)|
|136| [What is platform in Angular?](#what-is-platform-in-angular)|
|137| [What happens if I import the same module twice?](#what-happens-if-i-import-the-same-module-twice)|
|138| [How do you select an element with in a component template?](#how-do-you-select-an-element-with-in-a-component-template)|
|139| [How do you detect route change in Angular?](#how-do-you-detect-route-change-in-angular)|
|140| [How do you pass headers for HTTP client?](#how-do-you-pass-headers-for-http-client)|
|141| [What is the purpose of differential loading in CLI?](#what-is-the-purpose-of-differential-loading-in-cli)|
|142| [Is Angular supports dynamic imports?](#is-angular-supports-dynamic-imports)|
|143| [What is lazy loading?](#what-is-lazy-loading)|
|144| [What are workspace APIs?](#what-are-workspace-apis)|
|145| [How do you upgrade angular version?](#how-do-you-upgrade-angular-version)|
|146| [What is Angular Material?](#what-is-angular-material)|
|147| [How do you upgrade location service of angularjs?](#how-do-you-upgrade-location-service-of-angularjs)|
|148| [What is NgUpgrade?](#what-is-ngupgrade)|
|149| [How do you test Angular application using CLI?](#how-do-you-test-angular-application-using-cli)|
|150| [How to use polyfills in Angular application?](#how-to-use-polyfills-in-angular-application)|
|151| [What are the ways to trigger change detection in Angular?](#what-are-the-ways-to-trigger-change-detection-in-angular)|
|152| [What are the differences of various versions of Angular?](#what-are-the-differences-of-various-versions-of-angular)|
|153| [What are the security principles in angular?](#what-are-the-security-principles-in-angular)|
|154| [What is the reason to deprecate Web Tracing Framework?](#what-is-the-reason-to-deprecate-web-tracing-framework)|
|155| [What is the reason to deprecate web worker packages?](#what-is-the-reason-to-deprecate-web-worker-packages)|
|156| [How do you find angular CLI version?](#how-do-you-find-angular-cli-version)|
|157| [What is the browser support for Angular?](#what-is-the-browser-support-for-angular)|
|158| [What is schematic](#what-is-schematic)|
|159| [What is rule in Schematics?](#what-is-rule-in-schematics)|
|160| [What is Schematics CLI?](#what-is-schematics-cli)|
|161| [What are the best practices for security in angular?](#what-are-the-best-practices-for-security-in-angular)|
|162| [What is Angular security model for preventing XSS attacks?](#what-is-angular-security-model-for-preventing-xss-attacks)|
|163| [What is the role of template compiler for prevention of XSS attacks?](#what-is-the-role-of-template-compiler-for-prevention-of-xss-attacks)|
|164| [What are the various security contexts in Angular?](#what-are-the-various-security-contexts-in-Angular)|
|165| [What is Sanitization? Is angular supports it?](#what-is-sanitization?Is-angular-supports-it)|
|166| [What is the purpose of innerHTML?](#what-is-the-purpose-of-innerhtml)|
|167| [What is the difference between interpolated content and innerHTML?](#what-is-the-difference-between-interpolated-content-and-innerhtml)|
|168| [How do you prevent automatic sanitization?](#how-do-you-prevent-automatic-sanitization)|
|169| [Is safe to use direct DOM API methods in terms of security?](#is-safe-to-use-direct-dom-api-methods-in-terms-of-security)|
|170| [What is DOM sanitizer?](#what-is-dom-sanitizer)|
|171| [How do you support server side XSS protection in Angular application?](#how-do-you-support-server-side-xss-protection-in-angular-application)
|172| [Is angular prevents http level vulnerabilities?](#is-angular-prevents-http-level-vulnerabilities)|
|173| [What are Http Interceptors?](#what-are-http-interceptors)|
|174| [What are the applications of HTTP interceptors?](#what-are-the-applications-of-http-interceptors)|
|175| [Is multiple interceptors supported in Angular?](#is-multiple-interceptors-supported-in-angular)|
|176| [How can I use interceptor for an entire application?](#how-can-i-use-interceptor-for-an-entire-application)|
|177| [How does Angular simplifies Internationalization?](#how-does-angular-simplifies-internationalization)|
|178| [How do you manually register locale data?](#how-do-you-manually-register-locale-data)|
|179| [What are the four phases of template translation?](#what-are-the-four-phases-of-template-translation)|
|180| [What is the purpose of i18n attribute?](#what-is-the-purpose-of-i18n-attribute)|
|181| [What is the purpose of custom id?](#what-is-the-purpose-of-custom-id)|
|182| [What happens if the custom id is not unique?](#what-happens-if-the-custom-id-is-not-unique)|
|183| [Can I translate text without creating an element?](#can-i-translate-text-without-creating-an-element)|
|184| [How can I translate attribute?](#how-can-i-translate-attribute)|
|185| [List down the pluralization categories?](#list-down-the-pluralization-categories)|
|186| [What is select ICU expression?](#what-is-select-icu-expression)|
|187| [How do you report missing translations?](#how-do-you-report-missing-translations)|
|188| [How do you provide build configuration for multiple locales?](#how-do-you-provide-build-configuration-for-multiple-locales)|
|189| [What is an angular library?](#what-is-an-angular-library)|
|190| [What is AOT compiler?](#what-is-aot-compiler)|
|191| [How do you select an element in component template?](#how-do-you-select-an-element-in-component-template)|
|192| [What is TestBed?](#what-is-testbed)|
|193| [What is protractor?](#what-is-protractor)|
|194| [What is collection?](#what-is-collection)|
|195| [How do you create schematics for libraries?](#how-do-you-create-schematics-for-libraries)|
|196| [How do you use jquery in Angular?](#how-do-you-use-jquery-in-angular)|
|197| [What is the reason for No provider for HTTP exception?](#what-is-the-reason-for-no-provider-for-http-exception)|
|198| [What is router state?](#what-is-router-state)|
|199| [How can I use SASS in angular project?](#how-can-i-use-sass-in-angular-project)|
|200| [What is the purpose of hidden property?](#what-is-the-purpose-of-hidden-property)|
|201| [What is the difference between ngIf and hidden property?](#what-is-the-difference-between-ngif-and-hidden-property)|
|202| [What is slice pipe?](#what-is-slice-pipe)|
|203| [What is index property in ngFor directive?](#what-is-index-property-in-ngfor-directive)|
|204| [What is the purpose of ngFor trackBy?](#what-is-the-purpose-of-ngfor-trackby)|
|205| [What is the purpose of ngSwitch directive?](#what-is-the-purpose-of-ngswitch-directive)|
|206| [Is it possible to do aliasing for inputs and outputs?](#is-it-possible-to-do-aliasing-for-inputs-and-outputs)|
|207| [What is safe navigation operator?](#what-is-safe-navigation-operator)|
|208| [Is any special configuration required for Angular9?](#is-any-special-configuration-required-for-angular9)|
|209| [What are type safe TestBed API changes in Angular9?](#what-are-type-safe-testbed-api-changes-in-angular9)|
|210| [Is mandatory to pass static flag for ViewChild?](#is-mandatory-to-pass-static-flag-for-viewchild)|
|211| [What are the list of template expression operators?](#what-are-the-list-of-template-expression-operators)
|212| [What is the precedence between pipe and ternary operators?](#what-is-the-precedence-between-pipe-and-ternary-operators)
|213| [What is an entry component?](#what-is-an-entry-component)|
|214| [What is a bootstrapped component?](#what-is-a-bootstrapped-component)|
|215| [How do you manually bootstrap an application?](#how-do-you-manually-bootstrap-an-application)|
|216| [Is it necessary for bootstrapped component to be entry component?](#is-it-necessary-for-bootstrapped-component-to-be-entry-component)|
|217| [What is a routed entry component?](#what-is-a-routed-entry-component#)|
|218| [Why is not necessary to use entryComponents array every time?](#why-is-not-necessary-to-use-entrycomponents-array-every-time)|
|219| [Do I still need to use entryComponents array in Angular9?](do-i-still-need-to-use-entrycomponents-array-in-angular9#)|
|220| [Is it all components generated in production build?](#is-it-all-components-generated-in-production-build)|
|221| [What is Angular compiler?](#what-is-angular-compiler)|
|222| [What is the role of ngModule metadata in compilation process?](#what-is-the-role-of-ngmodule-metadata-in-compilation-process)|
|223| [How does angular finds components, directives and pipes?](#how-does-angular-finds-components-directives-and-pipes)|
|224| [Give few examples for NgModules?](#give-few-examples-for-ngmodules)|
|225| [What are feature modules?](#what-are-feature-modules)|
|226| [What are the imported modules in CLI generated feature modules?](#what-are-the-imported-modules-in-cli-generated-feature-modules)|
|227| [What are the differences between ngmodule and javascript module?](#what-are-the-differences-between-ngmodule-and-javascript-module)|
|228| [What are the possible errors with declarations?](#what-are-the-possible-errors-with-declarations)|
|229| [What are the steps to use declaration elements?](#what-are-the-steps-to-use-declaration-elements)|
|230| [What happens if browserModule used in feature module?](#what-happens-if-browsermodule-used-in-feature-module)|
|231| [What are the types of feature modules?](#what-are-the-types-of-feature-modules)|
|232| [What is a provider?](#what-is-a-provider)|
|233| [What is the recommendation for provider scope?](#what-is-the-recommendation-for-provider-scope#)|
|234| [How do you restrict provider scope to a module?](#how-do-you-restrict-provider-scope-to-a-module)|
|235| [How do you provide a singleton service?](#how-do-you-provide-a-singleton-service)|
|236| [What are the different ways to remove duplicate service registration?](#what-are-the-different-ways-to-remove-duplicate-service-registration)|
|237| [How does forRoot method helpful to avoid duplicate router instances?](#how-does-forroot-method-helpful-to-avoid-duplicate-router-instances)|
|238| [What is a shared module?](#what-is-a-shared-module)|
|239| [Can I share services using modules?](#can-i-share-services-using-modules)|
|240| [How do you get current direction for locales??](#how-do-you-get-current-direction-for-locales)|
|241| [What is ngcc?](#what-is-ngcc)|
|242| [What classes should not be added to declarations?](#what-classes-should-not-be-added-to-declarations)|
|243| [Wat is ngzone?](#what-is-ngzone)|
|244| [What is NoopZone?](#what-is-noopzone)|
|245| [How do you create displayBlock components?](#how-do-you-create-displayblock-components)|
|246| [What are the possible data change scenarios for change detection?](#what-are-the-possible-data-change-scenarios-for-change-detection)|
|247| [What is a zone context?](#what-is-a-zone-context)|
|248| [What are the lifecycle hooks of a zone?](#what-are-the-lifecycle-hooks-of-a-zone)|
|249| [Which are the methods of NgZone used to control change detection?](#which-are-the-methods-of-ngzone-used-to-control-change-detection)|
|250| [How do you change the settings of zonejs?](#how-do-you-change-the-settings-of-zonejs)|
|251| [How do you trigger an animation?](#how-do-you-trigger-an-animation)|
|252| [How do you configure injectors with providers at different levels?](#how-do-you-configure-injectors-with-providers-at-different-levels)|
|253| [Is it mandatory to use injectable on every service class?](#is-it-mandatory-to-use-injectable-on-every-service-class)|
|254| [What is an optional dependency?](#what-is-an-optional-dependency)|
|255| [What are the types of injector hierarchies?](#what-are-the-types-of-injector-hierarchies)|
|256| [What are reactive forms?](#what-are-reactive-forms)|
|257| [What are dynamic forms?](#what-are-dynamic-forms)|
|258| [What are template driven forms?](#what-are-template-driven-forms)|
|259| [What are the differences between reactive forms and template driven forms?](#what-are-the-differences-between-reactive-forms-and-template-driven-forms)|
|260| [What are the different ways to group form controls?](#what-are-the-different-ways-to-group-form-controls)|
|261| [How do you update specific properties of a form model?](#how-do-you-update-specific-properties-of-a-form-model)|
|262| [What is the purpose of FormBuilder?](#what-is-the-purpose-of-formbuilder)|
|263| [How do you verify the model changes in forms?](#how-do-you-verify-the-model-changes-in-forms)|
|264| [What are the state CSS classes provided by ngModel?](#what-are-the-state-css-classes-provided-by-ngmodel)|
|265| [How do you reset the form?](#how-do-you-reset-the-form)|
|266| [What are the types of validator functions?](#what-are-the-types-of-validator-functions)|
|267| [Can you give an example of built-in validators?](#can-you-give-an-example-of-built-in-validators)|
|268| [How do you optimize the performance of async validators?](#how-do-you-optimize-the-performance-of-async-validators)|
|269| [How to set ngFor and ngIf on the same element?](#how-to-set-ngfor-and-ngif-on-the-same-element)|
|270| [What is host property in css?](#what-is-host-property-in-css)|
|271| [How do you get the current route?](#how-do-you-get-the-current-route)|
|272| [What is Component Test Harnesses?](#what-is-component-test-harnesses)|
|273| [What is the benefit of Automatic Inlining of Fonts?](#what-is-the-benefit-of-automatic-inlining-of-fonts)|
|274| [What is content projection?](#what-is-content-projection)|
|275| [What is ng-content and its purpose?](#what-is-ng-content-and-its-purpose)|
|276| [](#)|



# Core Java
## Java Concepts

### Package Levels
package level: all other classes in the same package can visit this class
"Access Modifiers:" <br />
**public:** visible in the same package as well as the outside packages. <br />
**private:** Only those Classes who have defined these variables and methods can visit. It is the import way to realize Encapsulation. <br />
**protected:**  Besides the Classes who have defined these variables and methods, protected classes can also be visited by thire subclass. <br />
**default:** JAVA 8. The default access modifier is also called package-private, which means that all members are visible within the same package but arenot accessible from other packages.

 **[⬆ Back to Top](#table-of-contents)**

### Types for Inner classes
Inner class or nested class is a class declared entirely within the body of another class or interface. Types of nested classes in Java are:

**static class**: the keyword static indicates that the particular member belongs to a type itself, rather than to an instance of that type. This means that only one instance of that static member is created which is shared across all instances of the class.

**local class**: They are declared in the body of a function. They can only be referred to in the rest of the function. They can use local variables and parameters of the function, but only one that are declared "final". Can be very helpful for creation a class with generic type fields, where the type variables are defined in the method.

**anonymous class:** Anonymous classes enable you to make your code more concise. They enable you to declare and instantiate a class at the same time. They are like local classes except that they do not have a name. Use them if you need to use a local class only once.

**member class:** They are declared outside a function (hence a "member") and not declared "static".

JVM: Java Virtual Machine is a process virtual machine that can execute Java bytecode.

 **[⬆ Back to Top](#table-of-contents)**

### Encapsulation, Polymorphism, Inheritance, Abstraction
**Encapsulation:** provides objects with ablity to hide their internal characteristics and behavior. Each object provides a number of methods, which can be accessed by other objects and change its internal data. There are four modifiers: public, private, protected and default.

**Polymorphism** 多态: is the ability to present the same interface for different underlying data types. Override and OverLoad. Inheritance. List<> = ArrayList<>();

**Inheritance:** provides an object with the ability to acquire the methods of its super-class, It provides re-usability of code and can be used to add additional features to an existing class, without modifying it. 

**Abstraction:** is the process of separating ideas from 'specific instances', and develop classes of their own functionality, instead of their implementation details. 

 **[⬆ Back to Top](#table-of-contents)**

### Abstract Class
Abstract class is a class which cannot be instantiated, meaning you cannot create new instances of an abstract class, but they can be subclassed. The purpose of an abstract class is to function as a base for subclasses. 
- It may or may not include abstract methods.
- If a class includes abstract methods, then the class itself must be declared abstract.

"Abstract method": is a method that is declared without an implementation.
Example of Abstract class: AbstractList, AbstractSet, AbstractMap, AbstractQueue, AbstractCollection. 

 **[⬆ Back to Top](#table-of-contents)**

### Interface
Interface is a template which has only method declarations and not the method implementation. A class implements the interface must implement all the methods declared in it. 
(Cause multiple inheritances cannot be achieved in java. To overcome this problem the Interface concept is introduced.)  

 **[⬆ Back to Top](#table-of-contents)**

### Difference between Interface and Abstract class
Abstract Class:
- Abstract classes have a default constructor and it is called whenever the concrete subclass is instantiated.
- It contains Abstract methods as well as Non-Abstract methods.
- Abstract class allows you to Implement the functionality for the methods.
- The class which extends the Abstract class shouldn’t require the implementation of all the methods, only Abstract methods need to be implemented in the concrete sub-class.
- Abstract class may contain instance variables.
- You can only extends one abstract class at a time.

Interface:
- It doesn’t have any constructor and can’t be instantiated.
- Interface only allows you to declare methods but not implement them. 
- Classes that implement the interface should provide the implementation for all the methods.
- The interface contains only constants.
- You can implement multiple interfaces as long as required.


### Constructor
Constructor: a block of codes similar to methods, and gets invoked when a new object is created. Usually it’s how we want to instantiate an object.

### Serialization:
This Java process converts items into byte streams that transport objects to JVM.

### Sub-class and Super-class
In Java, it is possible to inherit attributes and methods from one class to another. So the "inheritance concept" can be devided into two categories: <br />
sub-class (child) - the class that inherits from another class.  <br />
super-class (parent) - the class being inherited from.  <br />
To inherit from a class, use the extends keyword. If you don't want other classes to inherit from a class, use the final keyword

"Upper casting and down-casting" <br /> 
Upcasting is casting to a super-type, while downcasting is casting to a sub-type. 


### Overloading and Overriding
Overloading occurs when two or more methods in the same class have exact the **same name, but different parameters, or diff return type**. Happens at compile-time. 

Overriding is when a child class redefines the same method of its parent class. Overriden methods must have the **same name, argument list, and return type**. Happens at runtime.


### Functional Interface
**Any interface with a Single Abstract Method (SAM) is a functional interface**, and its implementation may be treated as lambda expressions. Functional interface can have multiple default methods and static methods. Types: Function, Supplier, Consumer, Predicate, Comparator, Operator...<br />
https://www.baeldung.com/java-8-functional-interfaces


### Predicate
Predicate is a functional interface, which accepts an argument and return a boolean value. Usually, it used to apply in a filter for a collection of objects.


### Lambda Expressions
A lambda expression is a short block of code which takes in parameters and returns a value. Similar to methods, but they do not need a name and they can be implemented right in the body of a method.  <br />
Lambda expressions are Java's first step into **functional programming**, which can be created without belonging to any class. It is introduced from Java 8 to implify the creation of objects from funcitonal interfaces. <br />

() -> {}: (parameters) -> {body of the abstract method}.
```
// Comparator
(a, b) -> {a - b};
(o1, o2) -> (map.get(o1) - map.get(o2));
(o1, o2) -> o1.getAge() - o2.getAge();

//Runnable
Runnable run = () -> {code block to execute in a new thread}
```

### Collections
Java Collections Framework provides a well designed set of 'interfaces and classes' that support operations on a collections of objects. 
The most basic interface in Collections Framework are: Collection, Set, List, Map.


### OOP
Object-Oriented Programming. Object -> Class -> Inheritance -> Polymorphism -> Abstraction -> Encapsulation. 
- OOPs makes development and maintenance easier, whereas, in a procedure-oriented programming language, it is not easy to manage if code grows as project size increases.
- OOPs provides data hiding, whereas, in a procedure-oriented programming language, global data can be accessed from anywhere.
- OOPs provides the ability to simulate real-world event much more effectively. We can provide the solution of real word problem if we are using the Object-Oriented Programming language.


### SOLID Principle of OOD
- Single Responsibility: a class should only have one responsibility. Furthermore, it should only have one reason to change.
- Open/Closed: classes should be open for extension but closed for modification. In doing so, we stop ourselves from modifying existing code and causing potential new bugs.
- Liskov Substitution: if class A is a subtype of class B (A < B), we should be able to replace B with A without disrupting the behavior of our program.
- Interface Segregation: larger interfaces should be split into smaller ones. By doing so, we can ensure that implementing classes only need to be concerned about the methods that are of interest to them. "Many client-specific interfaces are better than one general-purpose interface."
- Dependency Inversion: instead of high-level modules depending on low-level modules, both will depend on abstractions. Refers to the decoupling of software modules. "depend upon abstractions, not concretions."


### MVC
The Model, View and Controller, is an architectural pattern that separates an application into three main logical components. Each of these components are built to handle specific development aspects of an application. 
- The Model component corresponds to all the data-related logic that the user works with. 
- The View component is used for all the UI logic of the application. 
- Controllers act as an interface between Model and View components. They process all the business logic and incoming requests, manipulate data using the Model component, and interact with the Views to render the final output.


### Annotation
Annotation, a form of metadata 注释, provide data about a program that is not part of the program itself. Annotations have no direct effect on the operation of the code they annotate.
- Annotations can be used by the compiler to detect errors or suppress 阻止 warnings. Provide information for the compiler. 
- Software tools can process annotation information to generate code, XML files. At Compile-time and deployment-time processing. 
- Some annotations are available to be examined at runtime. - Runtime processing.


### Comparable vs Comparator
Comparable and Comparator both are interfaces and can be used to sort collection elements.

"Comparable"
- Comparable provides a **single sorting sequence**. We can sort the collection on the basis of a single element.
- Comparable **affects the original class**.
- Comparable provides **compareTo()** method to sort elements.
- Comparable is present in java.lang package.
- We can sort the list elements of Comparable type by **Collections.sort(List)** method.

"Comparator"
- The Comparator provides **multiple sorting sequences**. We can sort the collection on the basis of multiple elements. 
- Comparator does **not affect the original class**.
- Comparator provides **compare()** method to sort elements.
- A Comparator is present in the java.util package.
- We can sort the list elements of Comparator type by **Collections.sort(List, Comparator)** method.


### ClassLoader
The Java Class Loader is a part of the Java Runtime Environment that dynamically loads Java classes into the JVM. Usually classes are only loaded on demand. The Java run time system does not need to know about files and file systems as this is delegated to the classloader.


### Reflection
Reflection API gives us information about the class to which an object belongs and also the methods of that class which can be executed by using the object. Through reflection we can invoke methods at runtime irrespective of the access specifier used with them. <br />
Reflection can be used to get information of an object by – getClass(), getConstructors(), getMethods(). <br />
Combine with annotations, using reflection api can achieve lots of framework jobs. 






## Data structures in JAVA

### JVM Memory

**Method** area: In the method area, all class level information like class name, immediate parent class name, methods and variables information etc. are stored, including static variables. There is only one method area per JVM, and it is a shared resource.
**Heap area**: Information of all objects is stored in the heap area. There is also one Heap Area per JVM. It is also a shared resource.
**Stack area**: For every thread, JVM creates one run-time stack which is stored here. Every block of this stack is called activation record/stack frame which stores methods calls. All local variables of that method are stored in their corresponding frame. After a thread terminates, its run-time stack will be destroyed by JVM. It is not a shared resource.
**PC Registers**: Store address of current execution instruction of a thread. Obviously, each thread has separate PC Registers.
**Native method stacks**: For every thread, a separate native stack is created. It stores native method information. 
![pic](https://media.geeksforgeeks.org/wp-content/uploads/jvm-3.jpg)


### JVM Runtime Memory Structure
Stack: static memory allocation and the execution of a thread. It contains "primitive values" that are specific to a method and "references" to objects that are in a heap, referred from the method. 
    Access to this memory is in Last-In-First-Out (LIFO) order. Whenever a new method is called, a new block is created on top of the stack which contains values specific to that method, like primitive variables and references to objects.
    faster access than Heap.
    each thread has its own stack. 

Heap: space in Java is used for dynamic memory allocation for Java objects and JRE classes at the runtime. New objects are always created in heap space and the references to this objects are stored in stack memory.
Objects in heap have global access and can be accessed from anywhere in the application.
not thread-safe.


### Metaspace in JVM
Metaspace is a new memory space – starting from the Java 8 version; it has replaced the older PermGen memory space. The most significant difference is how it handles memory allocation.
this native memory region grows automatically by default.
It also has new flags to tune the memory:
Additionally,The garbage collector now automatically triggers the cleaning of the dead classes once the class metadata usage reaches its maximum metaspace size.
with this improvement, JVM reduces the chance to get the OutOfMemory error.

### Garbage Collection
Automatic garbage collection is the process of looking at 'heap' memory, identifying which objects are in use and which are not, and deleting the unused objects. An unused object, or unreferenced object, is no longer referenced by any part of your program.

Minor GC: cleaning Young generation.
Major GC: cleaning up the Old generation.
Full GC: cleaning the entire Heap – both Young and Old spaces.

**Call System.gc()/Runtime.getRuntime().gc() to force invoke Java GC.**


### Eight primitive data type
byte, int, short, long, float, double, char, boolean(default false). <br />
They are not considered objects and represent raw values. They are stored directly on the stack. <br />
Auto-boxing: converting a primitive value into its corresponding wrapper class. <br />
Unboxing: converting an object of a wrapper type to its corresponding primitive value. <br />


### How to create immutable class
1. Declare the class as **final** so it can’t be extended.
2. Make all fields **private** so that direct access is not allowed.
3. **Don’t provide setter** methods for variables.
4. Make all mutable fields **final** so that its value can be assigned only once.
5. Initialize all the fields via a **constructor performing deep copy**.
6. Perform cloning of objects in the **getter** methods to **return a copy rather than the object reference.**


### How immutable clone (deep copy)
If you want to change an immutable object, you must clone it and change the clone while you are creating it. Use another constructor to clone your object.


### How to create/design singleton class
A singleton class is a class that can have only one instance.
1. Make a constructor private. Ensure that only one instance of the class exists.
2. Provide global access to that instance by
    + Declaring all constructors of the class to be private.
    + Providing a static method that returns a reference to the instance. The lazy initialization concept is used to write the static methods.
    + The instance is stored as a private static variable.



### HashCode() vs equals()
Basically, the same function to compare whether objects are the same objects.
hashCode() faster and equals() is much more accurate.
hashCode() is less reliable due to hash collision and equals() is more reliable because equals usually directly compare the address.


### List vs Set
List is an ordered sequecne, it allows duplicate elements, elements can be accessed by their position, multiple null elements can be sorted. List implementations are ArrayList, LinkedList, Stack, Vector. <br />
Set is an unordered sequence, it doesnot allow duplicated elements, position access to element is not allowed, Null element can store only once. Set implementations are Hash Set, Linked Hash Set, Tree Set.

### Difference between HashSet and TreeSet
HashSet: Inserte elements are in random order; Be able to store null objects; Performance is fast.
TreeSet: Maintains the elements in the inserted order; Cannot store null objects; Performance is slow.


### ArrayList vs LinkedList
ArrayList and LinkedList both implement List interface and maintains insertion order. Both are non synchronized classes.

"Array": <br />
1) An array is a container object that holds a fixed number of values of a single type. <br />
2) The length of an array is established when the array is created. <br />
3) The elements in an array can be accessed by their positions. <br />

"ArrayList":<br />
1) ArrayList internally uses a dynamic array to store the elements. <br />
2) Manipulation(insert, delete) with ArrayList is slow because it internally uses an array. If any element is removed from the array, all the bits are shifted in memory. <br />
3) An ArrayList class implements a List interface. Therefore, it acts as a list. <br />
4) ArrayList is better for storing and accessing data. <br />

"LinkedList": <br />
1) LinkedList internally uses a doubly linked list to store the elements.<br />
2) Manipulation with LinkedList is faster than ArrayList because it uses a doubly linked list, so no bit shifting is required in memory.<br />
3) LinkedList class implements both the List interface and the Deque interface. Therefore, it can act as a list and a deque.<br />
4) LinkedList is better for manipulating data.<br />

|          | Search | Deletion | Insert |
|----------|----------|--------|--------|
| ArrayList | 1| n | n |
| LinkedList | n | 1 | 1 |



### String Buffer vs String Builder
Java provides three classes to represent a sequence of characters: String(immutable), StringBuffer, and StringBuilder. (Both are mutable sequence of characters.)

StringBuffer: It is synchronized, thread safe. It means two threads cannot call the methods of StringBuffer simultaneously. It is less efficient than StringBuilder.

StringBuilder: the same as StringBuffer except it is non-synchronized i.e. not thread safe. It is more efficient. 


### Binary Tree
A binary tree is a tree data structure in which each node has up to two children, which are referred to as the left child and the right child.

"Binary Search Tree" <br />
A binary search tree is a binary tree in which every node fits a specific ordering property: all left descendents <= their root < all right descendents.


### HashMap, HashTable, ConcurrentHashMap and Hash Collision
All implement the Map interface, store key-value pairs, implement hashCode() and equals() methods to determine the index of the key-value pairs and to detect duplicates. They make no guarantees to the order of the map. 

"HashTable": inherits from Dictionary class. Any **non-null object** can be used as a key or a value. HashTable is Synchronize(thread-safe). Enumerator is used to iterate the elements. 

"HashMap": is a Hash Table based implementation of the Map interface. 
- It provides all Map operations, and **permits null values and null key**. It permits duplicate values, but not duplicate keys. 
- The HashMap class is asynchronized(not thread-safe), it is with higher performance. 
- Iterator is used to iterate the elements.

"ConcurrentHashMap"
Hashtable is thread safe, but not very efficient. Collections.synchronizedMap, fully synchronized Map, but not great efficiency either. **If we want thread-safety with high throughput under high concurrency, we should use ConcurrentMap.** <br />
The ConcurrentHashMap class implements ConcurrentMap as well as Serializable interface. <br />ConcurrentHashMap is an enhancement of HashMap, it is thread-safe with high efficient. <br />

"Hash Collision": is a situation where two or more key objects produce the same final hash value and hence point to the same bucket location or array index. This scenario can occur because according to the equals and hashCode methods, two unequal objects can have the same hash code.


### HashMap, TreeMap, LinkedHashMap
All offer a key-value mapping and a way to iterate through the keys. All three classes implements Map interface.

Implementation Details:
- A HashMap is implemented as a Hash Table, 
- A TreeMap is implemented as a Red-Black Tree, 
- A LinkedHashMap is implemented as a double-linked list. 

Null values/keys:
-HashMap and LinkedHashMap permits null values and null key, whereas TreeMap usually permits only null values. 

Iteration Order: 
- HashMap makes no guarantees on the iteration order of the map. Also, the addition and removal of any element might change its iteration order. 
- TreeMap is iterated according to the natural ordering of its keys. 
- LinkedHashMap maintains a doubly-linked list through all of its entries. This linked list defines the iteration order, (which is the order in which keys were inserted into the map.) 

Performance:
- HashMap and LinkedHashMap offers O(1) time performance for the basic CRUD operations.
- TreeMap guarantees O(log(n)) time cost for these operations. 
- And due to the added expense of maintaining the doubly-linked list, LinkedHashMap‘s performance is slightly lower than that of HashMap. 

Space Complexity:
- HashMap requires less memory than another two since it uses a hash table to store the mappings. 
- LinkedHashMap has the extra overhead of a doubly-linked list.
- TreeMap is implemented as a Red-Black tree, which takes more memory.


### Collections
List: Ordered, may have duplicate elements, has index.
- ArrayList: array based, fast search, low add/delete
- LinkedList: linkedlist based, low search, fast add/delete
- Vector: array based, thread safe, low efficiency

Set: No ordered, no duplicate allowed
- Treeset: Reb-Black based, stored order defined by Comparator, not allow null and throw NullPointerException, use compareTo();
- HashSet: HashTable based, not ordered, allow null obj, use equals() to compare;

ThreadSafe Version: Vector, CopyOnWriteArrayList, CopyOnWriteArraySet, Stack.

Map: key-value pair
- HashTable: inherits from Dictionary class, allow non-null obj, is thread-safe. 
- HashMap: hashtable based, allow null obj for key & value, only allow duplicate values, random iteration order, not thread-safe.
- TreeMap: RB tree based, only permits null value, stored order defined by Comparator,
- LinkedHashMap: double-linked list based, permits null key & value, order difined by the linked list.

ThreadSafe Version:
- ConcurrentHashMap: No need to synchronize the whole map. Very **fast** reads while write is done with a lock. No locking at the object level. Uses a multitude of locks.
- SynchronizedHashMap: Object level synchronization. Both read and writes acquire a lock. Locking the collection has a performance drawback. Not great efficient.



### final, finally and finalize()
"final" is a keyword used to apply restrictions on class, method and variable. Final class cannot be inherited. Final method cannot be overridden. Final variable cannot be reassigned. Final fields can be either constants or write-once fields. <br/>
If we have a final reference variable, we can’t reassign it either. But this doesn’t mean that the object it refers to is immutable. We can change the properties of this object freely.
```
final int[] array = new int[]{0, 1, 2, 3};
array[2] = 5;
Output: 0, 1, 5, 3

array[4] = 5;
ArrayIndexOutOfBoundsException;

The final keyword does not mean you cannot change the state of the object, but only that the reference marked as final will remain constant.
final only allows you to prevent the reference from being changed to another array Object.
```


"finally" is a block used to place important code, it will be executed whether exception is handled or not. Even in the case where the catch statement is missing and an exception is thrown, the finally block will still be executed. The Finally block is used to release resources like I/O buffers, database connections. 　

"finallize()" is a protected method of the Object class, which is called by the JVM (Java Virtual Machine)just before an object is garbage collected. 



### volatile: to ensure thread-safe
Volatile: keyword use with "variables" to ensure thread safe, is used to modify the value of a variable by different threads. All writes and reads operations will be directly on the main memory insted of cache. It also guarantees visibility and ordering. It prevents the compiler from reordering of code.


### What is generics? Customized own generic type?
A generic type is a generic class or interface whose parameter is type. <br />
Generics enable types to be parameters when defining classes, interfaces and methods. Type parameters provide a way to re-use the same code with different input types.  <br />
Code that uses generics has many benefits over non-generic code:
- Stronger type checks at compile time.
    A Java compiler applies strong type checking to generic code and issues errors if the code violates type safety. Fixing compile-time errors is easier than fixing runtime errors, which can be difficult to find.
- Elimination of casts.
- Enabling programmers to implement generic algorithms.



### Exception Handling
The Exception Handling is used to handle the runtime errors so that normal flow of the application can be maintained. It is devided into checked and unchecked Exception.

"Checked Exception":
- It is either be caught or thrown in the method. How it’s handled is defined in a method.
- It is checked at compile-time.
- Classes that extend Throwable class except Runtime Exception and Error are called checked Exception.    e.g. IOException, SQLException, ClassNotFoundException.

"Unchecked Exception":
- It is exception that was not caught or defined beforehand, such as runtimeException or Error.
- It is checked at runtime.
- The classes which inherit RuntimeException are known as unchecked exceptions （e.g. ArithmeticException, NullPointerException, ArrayIndexOutOfBoundsException etc.）


### Exception and Error
Exception and Error classes are both subclasses of the Throwable class. <br />
Exception class is used for exceptional conditions that a program should catch. <br />
Error class defines exceptions that are not expected to be caught by program. <br />

### Ways to handle exceptions?
- Using try/catch.
- By declaring throws keyword.

### Throws and Throw
Throws: keyword is used to declare exceptions. <br />
Throw: keyword is used to throw an exception instance.


### java 8 new features
- Interfaces can have **static and default methods** that, despite being declared in an interface, have a defined behavior/implementation.

- Method References: can be used as a shorter and more readable alternative for a lambda expression which only calls an existing method. ":: / ->"

- Optional<T>: can help to handle situations where there is a possibility of getting the NullPointerException (NPE). It works as a container for the object of type T. It can return a value of this object if this value is not a null. When the value inside this container is null it allows doing some predefined actions instead of throwing NPE.

- Stream API: intermediate and terminal operations.

- Lambda expression:

- Functional interfaces,

- Default methods: which allow the interfaces to have methods with implementation, without affecting the classes that implement the interface. (The default methods belongs to the Interface).

- Base64 Encode Decode,

- Collectors class,

- ForEach() method,

- Nashorn JavaScript Engine,
- Parallel Array Sorting,
- Type and Repating Annotations,
- IO Enhancements,
- Concurrency API Enhancements,
- JDBC Enhancements etc.




### Stream in Java
Stream is a new API in Java 8. It provides an efficient and easy way to deal with data.
A stream represents a sequence of elements and supports different kind of computations, stream operations are composed into a stream pipeline. <br />
- Stream **does not store elements**. It simply conveys elements from a source through a **pipeline of computational operations**.
- Stream is functional in nature. Operations performed on **a stream does not modify its source**.
- The elements of a stream are only visited once during the life of a stream. Like an Iterator, a new stream must be generated to revisit the same elements of the source.
- **Intermediate** Operations: **filter, collect, map, reduce, flatmap, sorted, reduce**.
- **Terminal** Operation: produces a result: **foreach, collection, count**.
- Streams are lazy; computation on the source data is only performed when the terminal operation is initiated, and source elements are consumed only as needed.

[Stream Impl:](https://www.baeldung.com/java-8-streams)

```
Stream<String> emptuStream = Stream.empty();

Collection<String> collection = Arrays.asList("a", "b", "c");
Stream<String> streamOfCollection = collection.stream();

// breaks a String into sub-strings according to specified RegEx:
IntStream streamOfChars = "abc".chars();
Stream<String> streamOfString = Pattern.compile(", ").splitAsStream("a, b, c");

```

#### filter()
It always returns the boolean value. If it returns true, the item is added to list else it is filtered out (ignored). Returns a stream consisting of the elements of this stream that match the given predicate.
```
List<String>strings = Arrays.asList("abc", "", "bc", "efg", "abcd","", "jkl");

//get count of empty string
int count = strings.stream().filter(string -> string.isEmpty()).count();

// result: 2

List names = Arrays.asList("Reflection","Collection","Stream");
List result = names.stream().filter(s->s.startsWith("S")).collect(Collectors.toList());
```

#### map()
To map each element to its corresponding result.
```
List<Integer> numbers = Arrays.asList(3, 2, 2, 3, 7, 3, 5);

//get list of unique squares
List<Integer> squaresList = numbers.stream().map( i -> i*i).distinct().collect(Collectors.toList());

//result: [9, 4, 4, 9, 49, 9, 25]
```

#### flatmap()
flatmap():Returns a stream consisting of the results of replacing each element of this stream with the contents of a mapped stream produced by applying the provided mapping function to each element.
The flatMap() method first flattens the input Stream of Streams to a Stream of Strings. Thereafter, it works similarly to the map() method.
```
before flattening: [[5, 7, 11, 13], [1, 3, 5], [2, 4, 6, 8]]
after flattening: [5, 7, 11, 13, 1, 3, 5, 2, 4, 6, 8]

List<List<Integer>> listOfListofInts = Arrays.asList(PrimeNumbers, OddNumbers, EvenNumbers);

List<Integer> listofInts  = listOfListofInts.stream()
                                    .flatMap(list -> list.stream())
                                    .collect(Collectors.toList());
```

**"differenc between map and flatmap in Java Stream"** <br />
map() takes a Stream and transform it to another Stream. It applies a function on each element of Stream and store return value into new Stream. It does not flatten the stream. But flatMap() is the combination of a map and a flat operation, use for both transformation and flattening.


#### sorted
```
List names = Arrays.asList("Reflection","Collection","Stream");
List result = names.stream().sorted().collect(Collectors.toList());

```

#### reduce() = sum up the data in the stream
**identity** – the initial value for an accumulator, or a default value if a stream is empty and there is nothing to accumulate.
```
OptionalInt reduced = IntStream.range(1, 4).reduce((a, b) -> a + b);
// reduced = 1 + 2 + 3 = 6
```

**accumulator** – a function which specifies the logic of the aggregation of elements. As the accumulator creates a new value for every step of reducing, the quantity of new values equals the stream's size and only the last value is useful. This is not very good for the performance.
```
int reducedTwoParams = IntStream.range(1, 4).reduce(10, (a, b) -> a + b);
// reducedTwoParams = 10 + 1 + 2 + 3 = 16
```

**combiner**– a function which aggregates the results of the accumulator. We only call combiner in a parallel mode to reduce the results of accumulators from different threads.
```
int reducedParallel = Arrays.asList(1, 2, 3).parallelStream()
    .reduce(10, (a, b) -> a + b, (a, b) -> {
       log.info("combiner was called");
       return a + b;
    });
// 11 + 12 + 13 = 36.
```

#### collect()
collect(Collector<> ): Performs a mutable reduction operation on the elements of this stream using a Collector.
```
List<Product> productList = Arrays.asList(new Product(23, "potatoes"),
  new Product(14, "orange"), new Product(13, "lemon"),
  new Product(23, "bread"), new Product(13, "sugar"));

// Converting a stream to the Collection (Collection, List or Set):
List<String> collectorCollection = 
  productList.stream().map(Product::getName).collect(Collectors.toList());

// Reducing to String:
String listToString = productList.stream().map(Product::getName)
  .collect(Collectors.joining(", ", "[", "]"));   //joining(delimiter, prefix, suffix)

// Processing the average value of all numeric elements of the stream:
double averagePrice = productList.stream()
  .collect(Collectors.averagingInt(Product::getPrice));

// Processing the sum of all numeric elements of the stream:
int summingPrice = productList.stream()
  .collect(Collectors.summingInt(Product::getPrice));


// Collecting statistical information about stream’s elements:
IntSummaryStatistics statistics = productList.stream()
  .collect(Collectors.summarizingInt(Product::getPrice));

// Grouping of stream’s elements according to the specified function:
Map<Integer, List<Product>> collectorMapOfLists = productList.stream()
  .collect(Collectors.groupingBy(Product::getPrice));


```


#### forEach()
 to iterate each element of the stream.
```
.forEach(System.out::println);
```

#### Statistics
With Java 8, statistics collectors are introduced to calculate all statistics when stream processing is being done.
```
List numbers = Arrays.asList(3, 2, 2, 3, 7, 3, 5);

IntSummaryStatistics stats = numbers.stream().mapToInt((x) -> x).summaryStatistics();

System.out.println("Highest number in List : " + stats.getMax());
System.out.println("Lowest number in List : " + stats.getMin());
System.out.println("Sum of all numbers : " + stats.getSum());
System.out.println("Average of all numbers : " + stats.getAverage());

```



### Future Interface, Promise Class and CompletableFuture Class (non-blocking)
A **Future Interface** represents the result of an asynchronous computation. Methods are provided to check if the computation is complete, to wait for its completion, and to retrieve the result of the computation, blocking if necessary until result is ready. Future is a read-only container of its result. It does not have any method to combine these computations or handle possible errors. 

For example, an operation can be a Runnable or Callable instance that is submitted to an ExecutorService. The submitter of the operation can use the Future object to check whether the operation isDone(), or wait for it to finish using the blocking get() method.
[Future DOC](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/Future.html) 
```
cancle(), get(), get(timeout, timeunit) isCancelled(), isDone();

// A task that sleeps for a second, then returns 1
public static class MyCallable implements Callable<Integer> {

    @Override
    public Integer call() throws Exception {
        Thread.sleep(1000);
        return 1;
    }
}

public static void main(String[] args) throws Exception{
    ExecutorService exec = Executors.newSingleThreadExecutor();
    Future<Integer> f = exec.submit(new MyCallable());

    System.out.println(f.isDone()); //False

    System.out.println(f.get()); //Waits until the task is done, then prints 1
}

```

Promise ~ CompletableFuture.

**Promise** [Promise DOC](http://www.functionaljava.org/javadoc/3.1/fj/control/parallel/Promise.html) represents a non-blocking future value. Promise serves as a handle on the result of the computation. Promise result can be combined. Promise cannot be used for blocking. <br />
Products, functions, and actors, given to the methods on this class, are executed concurrently, and the Promise serves as a handle on the result of the computation. Provides monadic operations so that future computations can be combined.


**CompletableFuture** [CompletableFuture DOC](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/concurrent/CompletableFuture.html) is used for asynchronous programming in Java. It implement two interfaces: Future and CompletionStage, belongs to java.util.cocurrent package. 

Asynchronous programming is a means of writing non-blocking code by running a task on a separate thread other than the main application thread and notifying the main thread about its progress, completion or failure. 
In this way, your main thread does not block/wait for the completion of the task and it can execute other tasks in parallel. Parallelism improves the performance of the program.

It has about 50 different methods for composing, combining, and executing asynchronous computation steps and handling errors. 

They are Futures that also allow you to string tasks together in a chain. 

You can use them to tell some worker thread to "go do some task X, and when you're done, go do this other thing using the result of X". 

Using CompletableFutures, you can do something with the result of the operation without actually blocking a thread to wait for the result. "non-blocking future".
[Baeldung Guide](https://www.baeldung.com/java-completablefuture)
```
// create a CF
CompletableFuture<String> CompletableFuture = new CompletableFuture<String>();  


//A supplier that sleeps for a second, and then returns one
public static class MySupplier implements Supplier<Integer> {

    @Override
    public Integer get() {
        try {
            Thread.sleep(1000);
        } catch (InterruptedException e) {
            //Do nothing
        }
        return 1;
    }
}


//A (pure) function that adds one to a given Integer
public static class PlusOne implements Function<Integer, Integer> {

    @Override
    public Integer apply(Integer x) {
        return x + 1;
    }
}

public static void main(String[] args) throws Exception {
    ExecutorService exec = Executors.newSingleThreadExecutor();
    CompletableFuture<Integer> f = CompletableFuture.supplyAsync(new MySupplier(), exec);
    System.out.println(f.isDone()); // False
    CompletableFuture<Integer> f2 = f.thenApply(new PlusOne());
    System.out.println(f2.get()); // Waits until the "calculation" is done, then prints 2
}

```





## Multithread
### Synchronization, Concurrency and Multithread
synchronization generally means sharing data between multiple processors or threads.

concurrency refers to a measure of how effectively an application allows multiple jobs required by that application (e.g. serving web page requests from a web server) to run simultaneously.


### Life Cycle of a Thread(6 states):
New. Runnable. Blocked. Waiting. Timed Waiting. Terminated.

### Document of Thread(Java 8)
https://docs.oracle.com/javase/8/docs/api/java/lang/Thread.html


### How to start a thread
**start() method of Thread class** is used to start a newly created thread. It performs following tasks:
- A new thread starts(with new callstack).
- The thread moves from "New" state to the "Runnable" state.
- When the thread gets a chance to execute, its target run() method will run.

**What happens if we override thread start() function?**
Whenever we override start() method then our start() method will be executed just like a normal method call and new thread wont be created. <br />
We can override start/run method of Thread class because it is not final. But it is not recommended to override start() method, otherwise it ruins multi-threading concept.


### Can we start a thread twice?
No. After starting a thread, it can never be started again. If you does so, an **IllegalThreadStateException** is thrown. In such case, thread will run once but for second time, it will throw exception.

### What if we call run() method directly instead start() method?
**Each thread starts in a separate call stack with start() method.**
Invoking the run() method from main thread, the run() method goes onto the current call stack rather than at the beginning of a new call stack.
There is no context-switching because here t1 and t2 will be treated as normal object not thread object.
```
public class TestThreadTwice1 extends Thread{  
    public void run(){  
        System.out.println("running...");  
    }
    public static void main(String args[]){  
        TestThreadTwice1 t1=new TestThreadTwice1();  
        t1.start();  
        t1.run(); //fine, but does not start a separate call stack  
    }  
}  
```



### Sleep()
The sleep() method of Thread class is used to sleep a thread for the specified amount of time.
public void sleep(long miliseconds): Causes the currently executing thread to sleep for the specified number of milliseconds.
public static void sleep(long miliseconds)throws InterruptedException


### wait() vs sleep()
| wait() | sleep() |
|--|--|
| wait() method releases the lock | sleep() method doesn't release the lock. |
| method of Object class | method of Thread class |
| non-static method | static method |
| should be notified by notify()/notifyAll() | complete after the specified amount of time |


### join() method in multithread
The join() method waits for a thread to die. In other words, it causes the currently running threads to stop executing until the thread it joins with completes its task.
public void join()throws InterruptedException



### Thread Synchronization
There are two types of thread synchronization "mutual exclusive" and "inter-thread communication"(Cooperation).

### Mutual Exclusive: synchionized keyword 互斥
Mutual Exclusive helps keep threads from interfering with one another while sharing data. This can be done by three ways in java:
- Synchronized method.
- Synchronized block.
- static synchronization.

**Synchronized method** is used to lock an object for any shared resource, allowing only one thread to execute at any given time.
When a thread invokes a synchronized method, it automatically acquires the lock for that object and releases it when the thread completes its task.
```
class Table{  
    public synchronized void printTable(int n){  //synchronized method  
        for(int i=1;i<=5;i++){  
            System.out.println(n*i);  
            try{  
                Thread.sleep(400);  
            }catch(Exception e) {
                System.out.println(e);
            }  
        }
    }
}
```
**Synchronized block** can be used to perform synchronization on any specific resource of the method.
1) Synchronized block is used to lock an object for any shared resource.
2) Scope of synchronized block is smaller than the method.
If you put all the codes of the method in the synchronized block, it will work same as the synchronized method.



### Inter-thread communication/Co-operation
It is all about allowing synchronized threads to communicate with each other.
It is a mechanism in which a thread is paused running in its critical section and another thread is allowed to enter (or lock) in the same critical section to be executed. It is implemented by following methods of Object class:
    wait()
    notify()
    notifyAll()

1) wait() method: 
Causes current thread to **release the lock** and wait until either another thread invokes the notify() method or the notifyAll() method for this object, or a specified amount of time has elapsed. 
The current thread must own this objects monitor, so it must be called from the synchronized method only, otherwise it will throw exception.

2) notify() method: 
Wakes up a single thread that is waiting on this objects monitor. If any threads are waiting on this object, one of them is chosen to be awakened. The choice is arbitrary and occurs at the discretion of the implementation. 
Syntax: public final void notify()

3) notifyAll() method: 
Wakes up all threads that are waiting on this objects monitor. 
Syntax: public final void notifyAll()


### Lock Interface
Each object in Java is associated with a monitor, which a thread can lock or unlock. Only one thread at a time may hold a lock on a monitor. Any other threads attempting to lock that monitor are blocked until they can obtain a lock on that monitor. <br />
Synchronization is built around an internal entity known as the lock or monitor. By convention, a thread that needs consistent access to an objects fields **has to acquire the objects lock before accessing them**, and then release the lock when its done with them. <br />
**Lock interface**: is used to as a thread synchronization mechanism similar to synchronized blocks.
```
public void lock() 
public void unlock()
    
public void lockInterruptibly(): Acquires the lock unless the current thread is interrupted.

public Condition newCondition()

public boolean tryLock()

public boolean tryLock(long time, TimeUnit unit)
```

### Lock vs Synchronized
| Lock Interface | Synchronized keyword |
|--|--|
| guarantee the sequence for its waiting threads | not guarantee of sequence in which waiting thread will be given access |
| provide timeout option | no option of timeout if lock is not granted |
| lock() and unlock() can be called in different methods| must be fully contained within a single method |



### Deadlock
Deadlock in java is a part of multithreading. Deadlock can occur in a situation when a thread is waiting for an object lock, that is acquired by another thread and second thread is waiting for an object lock that is acquired by first thread. Since, both threads are waiting for each other to release the lock, the condition is called deadlock.


### Executor Framework vs Fork-Join Pool Framework(preemptive)
Java 7 added ForkJoinPool an implementation of ExecutorService which specifically designed to **execute ForkJoinTask**. ForJoinPool is a special kind of thread pool. They use a **work-stealing pattern**. All threads in a fork-join pool attempt to find and execute tasks submitted to the pool and/or created by other active tasks. <br />

In short, the former provides a general-purpose thread pool, while the latter provides a special implementation that uses a work-stealing pattern for efficient processing of ForkJoinTask. 

1) ForkJoinPool is designed to accept and execute ForkJoinTask, which is a lightweight version of FutureTask, while ThreadPoolExecutor is designed to provide a normal thread pool which executes each submitted task using one of possibly several pooled threads.
2) ForkJoinPool uses a work-stealing pattern, which means one thread can also execute a pending task from another thread. This improves efficiency in the case of ForkJoinTask as most of the ForkJoinTask algorithm spawn new tasks.  


### Multithreading and implement
To maximum utilization of CPU, Multithreading allows concurrent execution of two or more threads. Threads are light-weight processes within a process. 
- Extend the Thread class;  and override the run method.
- Implement the Runnable Interface. 
- Implement Callable interface.
- Using the Executor framework to create a thread pool. 

#### Extend the Thread class; and override the run method
The following is far from production-ready code,  we now need to write additional boilerplate to deal with: <br/>
the consistent creation of new threads <br/>
the number of concurrent live threads <br/>
the threads deallocation: very important for daemon threads in order to avoid leaks <br/>


```
public class NewThread extends Thread {  
    // override run() method
    public void run(){  
        long startTime = System.currentTimeMillis();
        int i = 0;
        while(true){
            System.out.println(this.getName() + ": New thread is running..." + i++);
            try {
                // wait for one sec so it doesn't print too fast
                Thread.sleep(1000);
            } catch (InterruptedException e) {
                // It is a method of Java’s throwable class which prints the throwable along with other details like the line number and class name where the exception occurred.
                e.printStackTrack();  
            }
            ...
        }        
    }  
} 

//initialize and start one thread:
public class SingleThreadExample {
    public static void main(String[] args){
        NewThread t = new NetThread();
        t.start();
    }
}

// start multiple threads:
public class MultipleThreadExample {
    public static void main(String[] args){
        NewThread t1 = new NewThread();
        t1.setName("MyThread-1");
        NewThread t2 = new NewThread();
        t2.setName("MyThread-2");
        t1.start();
        t2.start();
    }
}
```

#### Implement the Runnable Interface
We create a new class which implements java.lang.Runnable interface and override run() method. Then we **instantiate a Thread object** and call start() method on this object. 
Runnable interface have only one method named run().
public void run(): is used to perform action for a thread.
Runnable interface is a functional interface which doesn't accept any parameters and doesn't return any value. 
```
public interface Runnable {
    public void run();
}
```
Example 1: Useful for incoming events logging.
```
public class EventLoggingTask implements Runnable{
    private Logger logger = LoggerFactory.getLogger(EventLoggingTask.class);

    @Override
    public void run() {
        logger.info("Message");
    }
}

//In this example, the thread will just read a message from the queue and log it in a log file. There's no value returned from the task; the task can be launched using ExecutorService:

public void executeTask() {
    executorService = Executors.newSingleThreadExecutor();
    //Future object will not hold any value.
    Future future = executorService.submit(new EventLoggingTask()); 
    executorService.shutdown();
}

```

Example 2:
```
class NewThread implements Runnable{  
    public void run(){
        try {
            System.out.println("Thread " + Thread.currentThread().getId() + " is running...");  
        } 
        catch (InterruptedException e) {
            e.printStackTrack();
        } 
        
    }  
}

class Multithread {
     public static void main(String args[]){  
        int n = 8;
        for (int i = 0; i < n; i++){
            Thread obj = new Thread(new NewThread());
            obj.start();
        }
    }  
} 

Output:
Thread 13 is running
Thread 11 is running
Thread 12 is running
Thread 15 is running
Thread 14 is running
Thread 18 is running
Thread 17 is running
Thread 16 is running 
``` 
If you are not extending the Thread class, your class object would not be treated as a thread object. So you need to explicitely **create Thread class object**.


#### Implement Callable interface
The Callable interface is a generic interface containing a single call() method – which returns a generic value V:
```
public interface Callable<V> {
    V call() throws Exception;
}
```
The result of call() method is returned within a Future object. <br />
In case of running a Callable using an ExecutorService, the exceptions are collected in the Future object, which can be checked by making a call to the Future.get() method. This will throw an ExecutionException – which wraps the original exception:

```
public class FactorialTask implements Callable<Integer> {
    int number;
    public Integer call() throws InvalidParamaterException {
        int fact = 1;
        for(int count = number; count > 1; count--) {
            fact = fact * count;
        }
        return fact;
    }
}

//The result of call() method is returned within a Future object:

@Test
public void whenTaskSubmitted_ThenFutureResultObtained(){
    FactorialTask task = new FactorialTask(5);
    Future<Integer> future = executorService.submit(task);
 
    assertEquals(120, future.get().intValue());
}

@Test(expected = ExecutionException.class)
public void whenException_ThenCallableThrowsIt() {
 
    FactorialCallableTask task = new FactorialCallableTask(-5);
    Future<Integer> future = executorService.submit(task);
    Integer result = future.get().intValue();
}

@Test
public void whenException_ThenCallableDoesntThrowsItIfGetIsNotCalled(){
    FactorialCallableTask task = new FactorialCallableTask(-5);
    Future<Integer> future = executorService.submit(task);
 
    assertEquals(false, future.isDone());
}

```

#### Runnable vs Callable
| Runnable | Callable |
|----------|----------|
| run() using Thread class or ExecutorService  | only ExecutorService  |
| run() dosen't return any value  | call() returns value   |
| cannot throw checked exception| can throw checked exception |

```
public interface Runnable {
    void run();
}

public interface Callable<V> {
    V call() throws Exception;
}
```


#### Implement ExecutorService Interface
Create a thread pool. (Features: thread reusability, task queues, fork-join pool, completableFuture).
Prons: Thread reusability, in particular, is very important: in a large-scale application, allocating and deallocating many thread objects creates a significant memory management overhead.

##### Instantiating ExecutorService:
Executes only one thread:
```
ExecutorService es = Executors.newSingleThreadExecutor(); 
```

Internally manages thread pool of 5 threads:
```
ExecutorService es = Executors.newFixedThreadPool(5); 
```

The ScheduledExecutorService runs tasks after some predefined delay and/or periodically. <br />
Internally manages thread pool of 10 threads to run **scheduled** tasks:
```
ExecutorService es = Executors.newScheduledThreadPool(10); 
ScheduledExecutorService es = Executors.newSingleThreadScheduledExecutor();

//run a task after an initial delay of 100 milliseconds. And after that, it will run the same task every 450 milliseconds:
Future<String> resultFuture = service.scheduleAtFixedRate(runnableTask, 100, 450, TimeUnit.MILLISECONDS);
```

Directly Create an ExecutorService: <br />
Because ExecutorService is an interface, an instance of any its implementations can be used. <br />
Choose an implementation class of **ExecutorService** interface and create it’s instance directly. Below statement creates a thread pool executor with minimum thread count 10, maximum threads count 100, 5 milliseconds keep alive time and a blocking queue to watch for tasks in future.
```
ExecutorService executorService = new ThreadPoolExecutor(10, 100, 5L, TimeUnit.MILLISECONDS,   
                                                    new LinkedBlockingQueue<Runnable>());
```

##### Assigning Tasks to the ExecutorService:
ExecutorService can execute Runnable and Callable tasks.
**execute():** returns nothing and dosen't get the result of a task's execution or to check the task's status (is it running):
```
es.execute(runnableTask);
```
**submit():** submits a Callable or a Runnable task to an ExecutorService and returns a result of type Future:
```
Future<String> future = es.submit(callableTask); 
```
Future allows us to get the result of a task's execution or to check the task's status (is it running). The Future interface provides a special blocking method get(), which returns an actual result of the Callable task's execution or null in the case of a Runnable task:

```
Future<String> future = es.submit(callableTask);
String result = null;
try {
    result = future.get(); //get() will block the execution, might degrade the app performance.
    result = future.get(200, TimeUnit.MILLISECONDS); //use timeouts instead.

} catch (InterruptedException | ExecutionException e) {
    e.printStackTrace();
}
```

**invokeAny():** assigns a collection of tasks to an ExecutorService, causing each to run, and returns the result of a successful execution of one task (if there was a successful execution):
```
String result = executorService.invokeAny(callableTasks);
```

**invokeAll():**  assigns a collection of tasks to an ExecutorService, causing each to run, and returns the result of all task executions in the form of a list of objects of type Future:
```
List<Future<String>> futures = executorService.invokeAll(callableTasks);
```


##### Shutting Down an ExecutorService:
In general, the ExecutorService will not be automatically destroyed when there is no task to process. It will stay alive and wait for new work to do. <br />
In some cases this is very helpful, such as when an app needs to process tasks that appear on an irregular basis or the task quantity is not known at compile time.  <br />
On the other hand, an app could reach its end but not be stopped because a waiting ExecutorService will cause the JVM to keep running. <br />

**shutdown():** It will make the ExecutorService stop accepting new tasks and shut down after all running threads finish their current work:
```
es.shutdown(); 
```

**shutdoenNow():** destroy the ExecutorService immediately, but it doesn't guarantee that all the running threads will be stopped at the same time. This method returns a list of tasks that are waiting to be processed. It is up to the developer to decide what to do with these tasks.
```
List<Runnable> notExecutedTasks = es.shutDownNow();
```

One good way to shut down the ExecutorService (recommended by Oracle) is to use both of these methods combined with the awaitTermination() method:
```
// first stop taking new tasks.
executorService.shutdown();
try {
    // wait up to a period time for all tasks to be completed.
    if (!executorService.awaitTermination(800, TimeUnit.MILLISECONDS)) { 
        executorService.shutdownNow();
    } 
} 
// If that time expires, the execution is stopped immediately.
catch (InterruptedException e) {
    executorService.shutdownNow();
}

```


##### Pitfalls of ExecutorService:
**Keeping an unused ExecutorService alive:** See the detailed explanation in Section 4 on how to shut down an ExecutorService.

**Wrong thread-pool capacity while using fixed length thread pool**: It is very important to determine how many threads the application will need to run tasks efficiently. A too-large thread pool will cause unnecessary overhead just to create threads that will mostly be in the waiting mode. Too few can make an application seem unresponsive because of long waiting periods for tasks in the queue.

**Calling a Future‘s get() method after task cancellation:** Attempting to get the result of an already canceled task triggers a CancellationException.

**Unexpectedly long blocking with Future‘s get() method:** We should use timeouts to avoid unexpected waits.

```
public class TestThreadPool {  
     public static void main(String[] args) {  
        ExecutorService executor = Executors.newFixedThreadPool(5);  
        for (int i = 0; i < 10; i++) {  
            Runnable worker = new WorkerThread("" + i);
            executor.execute(worker);//calling execute method of ExecutorService  
          }  
        executor.shutdown();  
        while (!executor.isTerminated()) {   }
  
        System.out.println("Finished all threads");
    }
}
```

##### Start a thread and execute parallel tasks
```
execute()
es.submit(() -> {
    new Task();
});
```

Reference Links:

https://www.baeldung.com/java-concurrency

https://www.baeldung.com/java-start-thread

https://www.baeldung.com/thread-pool-java-and-guava

https://www.baeldung.com/java-thread-lifecycle

https://www.baeldung.com/java-completablefuture

https://howtodoinjava.com/java/multi-threading/executor-service-example/












# DataBase
## DataBase
### Difference between PUT and POST
They both send data to a server to create/update a resource.
PUT method is *idempotent*, which means calling the same PUT request multiple times will always produce the same result. In contrast, calling a POST request repeatedly have side effects of creating the same resource multiple times.


### JOIN
A JOIN clause is used to combine rows from two or more tables, based on a related column between them. <br />
    (INNER) JOIN: Returns records that have matching values in both tables.<br />
    LEFT (OUTER) JOIN: Returns all records from the left table, and the matched records from the right table.<br />
    RIGHT (OUTER) JOIN: Returns all records from the right table, and the matched records from the left table.<br />
    FULL (OUTER) JOIN: Returns all records matched in either left or right table.

### Clustered Index vs Non-Clustered Index
Short answer: Clustered Index defines the order in which the data is physically stored, table can have only one clustered index. While non-Clustered indexes stored the pointers to the location of the data, instead of the data itself. <br />
A Clustered Index sorts and stores rows data in a table or view based on their fundamental values. Therefore table can have only one clustered index. The leaf nodes of a clustered index contain the data pages.<br />
A Non-Clustered Index poses a structure, which is separated from data rows, in which the logical order of the index does not match the physical order. The leaf node of a nonclustered index does not consist of the data pages. Instead, the leaf nodes contain index rows.<br />

### When should we not use indexes in sql databases?
Indexes should not be used on tables containing few records. <br />
Tables that have frequent, large batch updates or insert operations. <br />
Indexes should not be used on columns that contain a high number of NULL values. <br />
Indexes should not be used on the columns that are frequently manipulated. <br />


### KEYs
**Prime Key**: PK is a single column value used to identify a database record uniquely. cannot be NULL，must be unique，should rarely be changed，must be given a value when a new record is inserted.<br />
**Foreign Key**: references the primary key of another Table. It helps connect defferent Tables.<br />
**Composite Key**: a primary key composed of multiple columns used to identify a record uniquely.


### SQL Tuning
Database Tuning describes a group of activities used to optimize and enhance the performance of a database. It usually overlaps with query tuning, but refers to design of the database files, selection of the DBMS application, and configuration of the database's environment(CPU).

Database tuning aims to maximize use of system resources to perform work as efficiently and rapidly as possible.
- using execution plan to identify the cause of slowness
- try to reduce JOIN operations. remove unused JOIN and JOIN conditions.
- use UNION ALL(not remove deplicate data) instead UNION (will remove deplicate data)
- use the LIMIT to do the pagination
- create view or stored procedure to improve performance 
- avoid unused IN clause, but full table scan.

1)  Identifying high-load SQL statements. <br />
2)  Gathering performance-related data. <br />
3)  Determining the causes of the problem. <br />
    - Inefficiently designed SQL statements
        + Neglecting to add a join condition, which leads to a Cartesian join
        + Using hints to specify a large table as the driving table in a join
        + Specifying UNION instead of UNION ALL
        + Making a subquery execute for every row in an outer query
    - Suboptimal execution plans
    - Missing SQL access structures
    - Stale optimizer statistics
    - Hardware problems

4)  Defining the scope of the problem. <br />
5)  Implementing corrective actions for sub-optimally performing SQL statements. <br />
6)  Preventing SQL performance regressions. <br />

UNION is row-wise
JOIN is column-wise


### Normalization
Eliminate redundant data and ensure the data is stored logically.
In most practical applications, normalization achieves its best in 3rd Normal Form. 
- 1NF: Each table cell should contain a single value. Each record needs to be unique.
- 2NF: 1NF + Single Column Primary Key that does not functionally dependant on any subset of candidate key relation
- 3NF: 2NF + Has no transitive functional dependencies。
- Remove multi-valued attributes (Each col is unique) -> 1NF(1st Normal Form)
- Remove partial dependencies (each attribute describes PK) -> 2NF
- Remove transitive dependencies (each attribute should not describe other Non-PK attribute )->3NF 改变某一个属性，不会引起另一个属性也需要改变。


### De-normalization
Denormalization is a strategy used on a previously-normalized database to increase performance. In computing, denormalization is the process of trying to **improve the read performance of a database, at the expense of losing some write performance**, by adding redundant copies of data or by grouping data. <br />
normalization -> split table into several small tables -> slow performance. <br />
Thus denormalization will be needed. 


### Non-relational Database
Does not use the tabular schema of rows and columns. Instead, it uses a storage model that is optimized for specific requirements of stored data. <br />
**Document Data Stores**: key-document, form of JSON documents  -> can be encoded into XML, YAML, JSON, BSON. mongoDB, CouchDB. <br />
**Columnar Data Stores**: (Column Family) key-value data store essential a large hash table. implement de-normalization. Cassandra, Hbase. <br />
**Key-Value Data Stores**: essentially a large hash table. Redis, riak. <br />
**Graph Data Store**: node(entity) + edge(relationship). Neo4j, Hyper GraphDB. <br />


### MongoDB
Document store, JSON, run over multiple stores，Hash-based, schema-less database.
Mongod: database instance,

Functionality of MongoDB:
1. dynamic schema
2. document based
3. support secondary indexes  (B-tree)
4. master-slave replication
5. horizontal scaling
6. range based partition
7. no joins and transactions 
8. CP (Consistency and Partition Tolerance)


### Redis
Remote directory server is an in-memory, key-value data structure store.

Redis usage in Cache-Aside:
    Modular
    Cache failure is not critical
    Data models can be different
    Cached data can get stale(TTLs)
    Code changes required

Cache hit: read from cache     --> Write data to cache 
Cache miss: read from database

Redis support two persistence mechanisms:
- RDB(redis database): the RDB persistence performs point-in-time snapshots of dataset as specified intervals. Periodic back up. 
- AOF(append only file): the AOF persistence logs every wirte operation received by the server. (Back up those haven't be RDB data.)




### sql vs non-sql in database
|   SQL     |   No-SQL    |
|-|-|
|  relational  |  non-relational or distributed  |
|  structured query language and have a predefined schema  |  have dynamic schemas for unstructured data  |
|   vertically scalable  |  horizontally scalable  |
|  table based |  store with document, key-value, or graph  |
|  better for multi-row transactions  |  better for unstructured data like documents or JSON  |
|  not suited for hierarchical data storage  |  suited |
|  ACID  |  CAP |

vertical scaling: adding processing power to the the server can make it faster.<br />
horizontal scaling: add more servers/machine/nodes in the cluster.

**ACID:**<br />
    Atomicity: all changing to the data are single operation.<br />
    Consistency: data is in a consistent state when a transaction starts and ends.<br />
    Isolation: the intermediate state of a transcation is invisible to other transactions.<br />
    Durability: after a transaction successfully completes, changes to data persist and are not undone. 不能被回退 <br />

The CAP theorem is about distributed data stores that claims, in the event of a network failure on a distributed database, it is possible to provide either consistency or availability—but not both.
**CAP:** <br />
    Consistency: all clients will always have the same view of data.<br />
    Availability: each client can always read and write the data.<br />
    Partition Tolerance: 分区容错 the system works well despite the physical network partition.<br />


### Saga pattern
link: [Saga](https://microservices.io/patterns/data/saga.html) <br />
Implement each business transaction that spans multiple services is a saga. A saga is a sequence of local transactions. Each local transaction updates the database and publishes a message or event to trigger the next local transaction in the saga. <br />
A service publishes an event when its data changes. Other services consume that event and update their data. Two ways to achieve:<br />
**Choreograph** [ˈkɔriəˌɡræf]: each local transaction publishes domain events that trigger local transaction in other services. <br />
adv: sequencely. <br />
disadv: 

**Orchestration** [ˌɔrkɪ‘streɪʃn]: an orchestrator tells the participants what local transactions to execute. <br />
SEC: saga exection coordinative: each server : what, when to do.



### Sharding and Replica
**Sharding** of data: 
    distributes a single logical database system across a cluster of machines. <br />
    use range-based partition to distribute documents based on specific shard keys. 

**Replica**:
    copying data from a central database to one or more databases.
    failover(zero downtime), master-slave 


### JDBC
**Java database connectivity** is a software component that enables java applications to interact with the database. (middle ware) Connect DB -> statement of query and execute -> process query result -> close statement, close connection. 

### JPA
**Java Persistence API** provides an Object Relational Mapping(ORM) facility for managing **relational** data, object in Java class to records in DB. JPA internally uses the JDBC API to interact with the database.


### HQL
Hibernate Query Language is an object-oriented extension to SQL. It can be used to retrieve objects from database through O/R mapping.
- Provides full support for relational operations.
- Return results as objects. 
- Supports many advanced features: pagination, fetch join with dynamic profiling, inner/outer/full joins, and cartesian product. 
- Provides database independency. 


### Hibernate
Hibernate ORM is an object–relational mapping tool. It provides a framework for mapping objects to the database. It implements JPA (Java Persistence API) for data persistence. 

convert sql table to Java code:
```
Employee emp = new Employee();
emp.setId(4);
emp.setname("David");
emp.setSalary(987);
session.save(emp); // save to sql table
```
"ORM": Object Realtional Mapping 
    Hibernate -> easy orm 
    Sequelize -> good for node.js 
    SQLAlchemy
    MyBatis

**Advanced Hibernate** <br />
first level cache: default open, (thread level), local data;
second level cache: default close, (global), global data

Different Fetch type: eager, lazy, 详细补充下！

**Cascade:** 串联 //https://www.baeldung.com/jpa-cascade-types <br />
"Cascade": When we perform some action on the target entity(a column data), the same action will be applied to the associated entity.  e.g. Person–Address relationship. <br />
the primary object will always have operations on its associated objects. <br />
JPA Cascade type:
    all 
    persist, 
    merge, 
    refresh, 
    remove, 
    detach.




### Design Pattern
Design patterns are well-proved solution for solving the specific problem/task.

1）**Singleton Pattern:** A singleton class means only one object can be created from the class. Usage for singleton: logger, drivers objects, caching, thread pool.
```
public class SingletonD {
    private static volatile SingletonD instance= null;

    private SingletonD(){}

    public static SingletonD getInstance(){ 
        if(instance == null){
            synchronized(SingletonD.class){ 
                if(instance == null){
                    instance = new SingletonD(); 
                }
            } 
        }
        return instance; 
    }
}

@RestController
public class LibraryController {
    
    @Autowired
    private BookRepository repository;

    @GetMapping("/count")
    public Long findCount() {
        System.out.println(repository);
        return repository.count();
    }
}

```

2）**Factory Pattern:** create objects without exposing the creation logic to the client and refer to newly created objects using a common interface. <br />
Factory is a creational design pattern, related to object creation. Factory pattern hides the creation process of objects from being exposed to the caller. Caller of Factory doesn't know how the object gets created. This will make the code loosely coupled.

3）**Builder Pattern:** is used to simplify the process of building a complex object. Using one statement, we can set multiple attributes without creating a constructor. Also the setting of attributes is dynamic and flexible.
```
    Department d = Department.builder()
                    .setLocation("Here")
                    .setManagerName("dawei")
                    .setName("df")
                    .build();
```

4）**Proxy Pattern:** Proxy is a structural design pattern that provides a substitute for another object; control the access to the orginal objects; perform some operations before and after request/response; could dynamic change servers. <br />
The proxy object has the same interface as a service, which makes it interchangeable with a real object when passed to a client.


5）**Adapter Pattern:** An Adapter pattern acts as a connector between two incompatible interfaces that cannot be connected directly. An Adapter wraps an existing class with a new interface so that it becomes compatible with the client’s interface.
The main motive behind using this pattern is to convert an existing interface into another interface that the client expects.

6) **Template pattern:**is a technique that defines the steps required for some action, implementing the boilerplate steps, and leaving the customizable steps as abstract.  Subclasses can then implement this abstract class and provide a concrete implementation for the missing steps.


















# Advanced Java
##  Jakarta EE

### Jakarta EE
Jakarta EE, Java 2 Platform and Java Enterprise Edition is a set of specifications, extending Java SE(Standard Edition) with specifications for enterprise features such as distributed computing and web services.

### Servlet
A Servlet is a Java class that extend the capabilities of servers that host applications accessed by a request-response programming model. It is used to process client request and generate dynamic web content. **Servlets are mostly used to process or store data submitted by an HTML form, provide dynamic content and manage state information that does not exist in the stateless HTTP protocol.** 

(When Servlet is listening on the URL )
- **Servlet Filter** A filter is an object that is invoked at the preprocessing and postprocessing of a request. It is mainly used to perform filtering tasks such as recording all incoming requests, conversion, logging IP addresses, data compression, encryption and decryption, input validation etc.
- doGet(): when you want to intercept <!-- 拦截 --> on HTTP GET requests. 
- doPost(): when you want to intercept on HTTP POST requests. 

### DispatcherServlet(Spring Framework API)
Central dispatcher for HTTP request controllers. Dispatches to registered handlers for processing a web request, providing convenient mapping and exception handling facilities.

### JPA
**Java Persistence API** provides an object/relational mapping(ORM) facility for managing **relational** data in Java applications. JPA internally uses the JDBC API to interact with the database.

### Spring Data JPA
They are interfaces with methods supporting CRUD(create, read, update, and delete)records against a back end data store.

### JMS
**Java Message Service** API is a messaging standard that allows application components based on Jakarta EE to create, send, receive, and read messages. It enables distributed communication that is loosely coupled, reliable, and asynchronous.

### JSP
**Jakarta Server Pages**, is a collection of technologies that helps create dynamically generated web pages based on HTML, XML, SOAP, or other document types. 

### JAX-B(xml)
**Java Architecture for XML Binding**. It is a framework that allows developers to map Java classes to XML representations. JAX-B provides mechanism to marshal (write) java objects into XML and unmarshal (read) XML into object. 

### JAX-RS(rest api)
**Java API for RESTful Web Service**. It is a Jakarta EE API specification offers a set of interfaces and annotations to create web services according to the REST architectural pattern. 

### REST vs SOAP
REST and SOAP are 2 different approaches to online data transmission. Both define how to build APIs, which allow data to be communicated between web applications. 

**REpresentational State Transfer** (REST) is an architecture style for designing network applications. REST defines a set of constraints for how the architecture of an Internet-scaled, distributed, hypermedia system should behave. It's lightweight.

**Simple Object Access Protocol** (SOAP) is an official protocol with specific requirements like XML messaging. SOAP web services offer built-in security and transaction compliance that line up with many enterprise needs, but that also makes them heavier. 

The main difference is that SOAP is a protocol while REST is not. Typically, an API will adhere to either REST or SOAP, depending on the use case and preferences of the developer.



## HTTP (Hypertext Transfer Protocol)
### Request-Response Model
It's a communication model based on HTTP. A client, typically a web browser, sends a request for a resource to a server, and the server sends back a response corresponding to the resource. 

### Request
link: [All methods](https://www.tutorialspoint.com/http/http_requests.htm)

- **A request-line(Method)**: [Method, Request-URI, HTTP-Version]. <br />
    The Request-URI is a **Uniform Resource Identifier** and identifies the resource upon which to apply the request. 
- **Header**: The request-header fields allow the client to pass additional information about the request, and about the client itself, to the server. These fields act as request modifiers. (If-Match: ETag(); User-Agent; Host; Accept-Encoding; Connection; Proxy-Authorization) 
- **Message Body**(optional): data sending to the server. 

### Response
- **Status Code**: 
    + Informational responses (100–199)
    + Successful responses (200–299)
    + Redirects (300–399)
    + Client errors (400–499)
    + Server errors (500–599)
- **Header**:
- **Body**: the content returned from the server. 


| Method  | Description  |
|---------|---------|
| GET     | Transfer a current representation of the target resource.|
| HEAD    | Same as GET, but only transfer the status line and header section.|
| POST    | Perform resource-specific processing on the request payload. |
| PUT     | Replace all current representations of the target resource with the request payload. |
| DELETE  | Remove all current representations of the target resource. |
| CONNECT | Establish a tunnel to the server identified by the target resource. |
| OPTIONS | Describe the communication options for the target resource. |
| TRACE   | Perform a message loop-back test along the path to the target resource. |


| Code  | Reason-Phrase |
|---------|---------|
| 100  | Continue                      |
| 101  | Switching Protocols           |
| 200  | OK                            |
| 201  | Created                       |
| 202  | Accepted                      |
| 203  | Non-Authoritative Information |
| 204  | No Content                    |
| 205  | Reset Content                 |
| 206  | Partial Content               |
| 300  | Multiple Choices              |
| 301  | Moved Permanently             |
| 302  | Found                         |
| 303  | See Other                     |
| 304  | Not Modified                  |
| 305  | Use Proxy                     |
| 307  | Temporary Redirect            |
| 400  | Bad Request                   |
| 401  | Unauthorized                  |
| 402  | Payment Required              |
| 403  | Forbidden                     |
| 404  | Not Found                     |
| 405  | Method Not Allowed            |
| 406  | Not Acceptable                |
| 407  | Proxy Authentication Required |
| 408  | Request Timeout               |
| 409  | Conflict                      |
| 410  | Gone                          |
| 411  | Length Required               |
| 412  | Precondition Failed           |
| 413  | Payload Too Large             |
| 414  | URI Too Long                  |
| 415  | Unsupported Media Type        |
| 416  | Range Not Satisfiable         |
| 417  | Expectation Failed            |
| 426  | Upgrade Required              |
| 500  | Internal Server Error         |
| 501  | Not Implemented               |
| 502  | Bad Gateway                   |
| 503  | Service Unavailable           |
| 504  | Gateway Timeout               |
| 505  | HTTP Version Not Supported    |


### URL structure
**Uniform Resource Locator** is the global address of resources on the World Wide Web. <br />
scheme://host:port/path?query-string#fragment-id    <br />
https://www.xyz.com/path/user/123?name=jackie&tel=321

- The query string contains data to be passed to server-side scripts, running on the web server. 
- The query string preceded by a question mark (?), separated by ampersand (&).
- Fragment-id: if present, specifies a location within the page. Browser may scroll to display that part of the page. 

### REST API
**REpresentational State Transfer** REST is an architecture style for designing network applications. REST defines a set of constraints for how the _architecture_ of an Internet-scale distributed hypermedia system should behave. 
- Client - Server architecture
- Payload: JSON/XML





## Architecture Design
### Three-Layer/Tier Architecture(what, why)
- **Web Layer(Control Layer/Presentation  Layer)**: It is the user interface and communication layer of the application. Its main purpose is to display information to and collect information from the user. (http)
- **Service Layer(Application Layer)**: The place where the collected information is processed using bussiness logic.
- **DAO Layer**: Data Access Layer. It is the place where the information processed by the application is stored and managed. 

The chief benefit of three-layer architecture is that because each layer runs on its own infrastructure, each layer can be developed simultaneously by a separate development team, and can be updated or scaled as needed without impacting the other layers.<br />
**Pros**:
- Faster development
- Improved scalability
- Improved reliability
- Improved security



### Inversion Of Control(IOC)
It is a design principle which transfers the control of objects to a container or framework. (In contrast with traditional programming, in which our custom code makes calls to a library,) IOC enables a framework to take control of the flow of a program and make calls to our custom code. <br />
**Pros**:
-   decoupling the execution of a **task** from its **implementation**. loosely coupled.
-   making it easier to switch between different implementations.
-   greater modularity of a program. <!-- 模块化 -->
-   easier in testing a program by isolating a component or mocking its dependencies, and allowing components to communicate through contracts.



### Dependency Injection(DI)
It is a design pattern that implement IoC principle, where the inverted control is setting an object's dependencies. We do not create our objects manually but instead describe how they should be created. Then an IoC container will instantiate required classes if needed.<br />
**DI Tpyes**:
- Field Injection.(@Autowired)
- Constructor Injection. 
- Setter Injection.

**Pros**:
- **Loosely coupled** architecture.
- reduce module complexity.
- increase module reusability.
- increase system maintainability.
- more resuable, testable, readable.



### Aspect Oriented programming(AOP)
Aspect Oriented programming, one of the key components of Spring Framework. In AOP the key unit of modularity is the Aspect, instead the Class in OOP. 
**AOP aims to increase modularity by allowing the separation of cross-cutting concerns.** It does so by adding additional behavior to existing code without modification of the code itself. Helps us monitor and manage the work flow and the program, like Security, Transation, Cache, Log. 

- **Aspect**: a class that implements cross-cutting concerns, such as transaction management. 
- **Advice**: the **methods** that get executed when a specific JoinPoint with matching Pointcut is reached in the application. Types of advice include Before, After, Around, AfterReturning, AfterThrowing. 
- **JointPoint**: a point during the execution of a program, such as the execution of a method or the handling of an exception. 
- **PointCut**: **a set of regular expressions** that are matched with JoinPoint to determine whether Advice needs to be executed or not.


### Loose Coupling
Simply means objects are mostly **independent**. When an object gets the object to be used from the outside, then it is a loose coupling situation. As the main object is merely using the object, this object can be changed from the outside world easily marked it as loosely coupled objects. 



### Monolithic Architecture
Monolithic architecture is built as one large system and is usually one code-base. Monolithic application is tightly coupled and entangled as the application evolves, making it difficult to isolate services for purposes such as independent scaling or code maintainability.  
It extremely difficult to change technology or language or framework because everything is **tightly coupled and depend on each other**.  
**Pros**: fast, high level transaction.  
**Cons**: not scalable (hard to add moer servers), not distributed, 



### Service Orienter Architecture (SOA)
A type of software design that makes software components **reusable and interoperable** via service interfaces across different platforms and languages to form applications.
A **Service** is a self-contained unit of software functionalities, it is designed to complete a specific task (such as retrieving specified information or executing an operation). It contains the code and data integrations necessary to carry out a complete, discrete business function and can be accessed remotely and interacted with or updated independently.

### Enterprise Service Bus (ESB)
An enterprise service bus implements a communication system between mutually interacting software applications in a SOA(service-oriented architecture). It represents a software architecture for distributed computing, and is a special variant of the more general client-server model.



### Microservices architecture
Microservice is an architecture that structures an application loosely from other services so it is independent and modular. Each service running has its own process and this achieves the lightweight model to support business applications.

**Pros**: More Dynamic, Scalable; Flexibility; parallel development; Resilient: if any down, no impact to others; Docker continer technology; Cloud technology, Vertical and Horizontal.  
**Cons**: Complex architecture; challenge to design; DB for each service, challenge to share database (infact share API); Transaction data; DevOps challenge.  



### Basic components of Microservice
**Microservice** is an architectural style that structures an application as a collection of services. 
[link: Architecture](https://dzone.com/articles/microservice-architecture-learn-build-and-deploy-a)

|   Client    |     Identity Prociders  |   API Gateway    |    Messaging Format    |
|-------------|-------------------------|------------------|------------------------|
|   Database  |     Static Content      |   Management     |    Service Discovery   |

![pic](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/02/Architecture-Of-Microservices-Microservice-Architecture-Edureka.png)

![pic2](https://microservices.io/i/PatternsRelatedToMicroservices.jpg)

**Why do we need microservices in architecture?**    
Microservice architecture allows you to maximize deployment velocity and application reliability by helping you move at the speed of the market. Since applications each run in their own containerized environment, applications can be moved anywhere without altering the environment.



### What's the difference between microservices and service oriented architecture?
SOA is focused on application service reusability while Microservices are more focused on decoupling. SOA is full-stack in nature whereas Microservices is monolithic. SOA applications are built to perform numerous business tasks, but microservices are built to perform a single business task.


### Benefits of separating Frontend/backend. (vs Monolitic Architecture?)
- Modularity: easier to code for a single specific functionality.
- Reusability: With a separate API, your application logic can be reused by any number of applications. 
- Content Delivery: Separate client-side and server-side,  
- Responsiveness:
- Versioning: With separate API and UI projects, you can upgrade and deploy one without the other.





## Microservices Componemt
### Service Discovery (Eureka)
Service discovery is how applications and microservices locate each other on a network. Implementations include both a central server(s) that maintain a global view of addresses and clients that connect to the central server to update and retrieve addresses.  
Service instances have dynamically assigned network locations and changes dynamically. _In order to make a request, the code need to find out the network location IP addresses and ports of a service instance. Service instances have dynamically assigned network locations._
Client-side discovery and Server-side discovery. 


### Load Balancing (Netflix Ribbon: Client-side)
Load balancing is the process of sharing, incoming network traffic in concurrent time between servers. 
- **Server Side Load Balancing**: Server side load balancing is a monolithic. It applies between the client and the server. It accepts incoming network, application traffic, and distributes the traffic across the multiple backend servers by using various methods. The middle component is responsible for distributing the client requests to the server.
- **Client-Side Load Balancing**: The client holds the list of server’s IPs so that it can deliver the requests. The client selects an IP from the list, randomly, and forwards the request to the server.
- Ribbon is a client-side load balancer that gives you a lot of control over the behavior of HTTP and TCP clients


### Communication (Sleuth Zipkin?)
- **REST API**: Directly call the domain of a resource, and only focus on the data that belongs to that a specific domain. Communication on REST often happens using a JSON. No need to set up a client. For hypermedia.   
- **RPC**: Remote Procedure Call, refers to making a local call and having it execute on a remote service somewhere.   
- **Messaging System**: **Kafka** the services push messages to a **message broker** that other services subscribe to. It removes the need for services to call each other directly.   
Kafka
    - **Kafka**The Spring for Apache Kafka (spring-kafka) project applies core Spring concepts to the development of Kafka-based messaging solutions. It provides a "template" as a high-level abstraction for sending messages. It also provides support for Message-driven POJOs with @KafkaListener annotations and a "listener container". These libraries promote the use of dependency injection and declarative. In all of these cases, you will see similarities to the JMS support in the Spring Framework and RabbitMQ support in Spring AMQP.
    - Features:
    KafkaTemplate
    KafkaMessageListenerContainer
    @KafkaListener
    KafkaTransactionManager
    spring-kafka-test jar with embedded kafka server

### Logging
As microservices are running on multiple hosts, you should send all the generated logs across the hosts to an external, centralized place. From there, you can easily get the log information from one place. 

### Monitoring (Azure Monitor)
To ensure each service is able to interact with others, provide an early warning system for application deterioration or failure. Monitoring Microservices can help organizations.
**Zuul** is an API gateway that provides capabilities for dynamic routing, monitoring, resiliency, security, and more.

- Understand the overall health of the application
- Glean insight into the performance of each individual service 
- Ensure the API transactions are available and performing well
- Isolate problematic transactions and endpoints
- Optimize end-user experience

### Fault Tolerance (Resilience4j: a library) Hystrix
Fault tolerance is the property that enables a microservice to continue operating properly in the event of the failure of some of its components. Retry -> Cache -> Fall back -> Circuit Breaker.

**Circuit breaker**: A design pattern allows microservice to fail immediately to prevent repeated calls that are likely to fail. 
    A closed circuit represents a fully functional system, and an open circuit represents an incomplete system. If a failure occurs, the circuit breaker triggers to open the circuit, removing the point of failure from the system. An additional half-open state exists. After the circuit is opened, it periodically changes to the half-open state, where it checks whether the failed component is restored and closes the circuit after it is considered safe and functional.

**Fall back**: provides an alternative solution during a service request failure. When the circuit breaker trips and the circuit is open, a fallback logic can be started instead. Custom fallback, Fail silent, Fail fast.






## RESTful Web Services
### Design
- Method:(GET, POST, PUT, DELETE, PATCH)
- URI: Uniform Resource Identifier
- Header(Authorization, content-type)
- Payload (JSON/XML)

### Implementation
- Spring Web MVC (@RestController)
The Spring Web MVC framework provides Model-View-Controller (MVC) architecture and ready components that can be used to develop flexible and loosely coupled web applications. 

### Documentation(Swagger) in RESTful API
In the REST API documentation, you describe the various endpoints, their methods, parameters, and other details, and you also document sample responses from the endpoints.  
**Swagger** is a set of open-source tools built around the OpenAPI Specification that can help us to design, build, document and consume REST APIs. 

### Test (POSTman, RestAssured) with in RESTful API
Testing a RESTful Web service includes the following checks: 
Check URL addresses are constituted correctly based on the service deployment end-point and the method annotations. 
Check the generated server requests call the corresponding methods. 
Check the methods return acceptable data.

### RestTemplate class with RESTful API
It is **the central class within the Spring framework for executing synchronous HTTP requests on the client side**. RestTemplate is also a high-level API, which in turn is based on an HTTP client.

### OpenFeign Client(Spring Cloud) @Feign
Feign makes writing web service clients easier with pluggable annotation support, which includes Spring MVC annotations and JAX-RS annotations.




## Spring Family

### Spring Basic Annotations
- @Component: allows Spring to automatically detect our custom beans. They are registered in ApplicationContext. Without having to write any explicit code, Spring will: Scan our application for classes annotated with @Component; Instantiate them and inject any specified dependencies into them; Inject them wherever needed.
- @Service (Service Layer): indicates that they're holding the business logic. 
- @Repository (DAO Layer): indicates that the decorated class is a repository. A repository is a mechanism for encapsulating storage, retrieval, and search behavior which emulates a collection of objects.
- @Controller: simply a specialization of the @Component class, which allows us to auto-detect implementation classes through the classpath scanning. 
- @ComponentScan: add to class file to scan your components to find beans and the corresponding injected with @Autowired annotation. 
- @Mapper 
- @Configuration: Ioc contanier. Beans 依赖关系的配置。
- @Bean，**Bean Scope:** singleton, prototype, request, session, application, global session.
- @Primary: indicates that a bean should be given **preference** when multiple candidates are qualified to autowire a single-valued dependency.
- @Qualifier: indicates specific bean should be **autowired** when there are multiple candidates.
- @RestController: indicates that the data returned by each method will be written straight into the response body instead of rendering a template. = @Controller + @ResponseBody.
- @RequestMapping: is used to define the Request URI to access the REST Endpoints. The default request method is GET.     @RequestMapping(value = "/path", method = RequestMethod.POST) .
- @RequestBody: is used to define the request body content type.
- @PathVariable: is used to define the custom or dynamic request URI. 
- @RequestParam: is used to read the request parameters from the Request URL. 
- @GetMapping @PostMapping @DeleteMapping: no need to specific in method.
- @Entity: is a JPA annotation to make this object ready for storage in a JPA-based data store.
- @Table(name): mapping this Entity to a table in database.
- @Id @GeneratedValue常常组合起来，用于主键声明，并指定主键生成策略和生成器（若不指定，JPA会根据所引入驱动依赖的数据库进行默认策略的设置）
- @Column(name,nullable,length,insertable,updatable): new a colunm to an attribute.


### What is the difference between @ApplicationContext and @beanfactory.
They are both IOC container. The BeanFactory is the most basic version of IOC containers, and the ApplicationContext extends the features of BeanFactory. including messaging functionality, event publication functionality, annotation-based dependency injection and easy integration with Spring AOP features. 


### Spring AOP
```
@Aspect
public class NotVeryUsefulAspect {
}

@Pointcut("execution(* transfer(..))")// the pointcut expression
private void anyOldTransfer() {}// the pointcut signature
```

### Spring Boot
Spring Boot is an open source platform with auto configuration for Java developers to develop a stand-alone and production-grade spring application that you can just run. You can get started with minimum configurations without the need for an entire Spring configuration setup.

- **Advantages**:  
    + Easy to understand and develop spring applications.
    + Increases productivity.
    + Reduces the development time.

- **Goals**:  
    + To avoid complex XML configuration in Spring.
    + To develop a production ready Spring applications in an easier way.
    + To reduce the development time and run the application independently.
    + Offer an easier way of getting started with the application. 

- **Why Spring Boot**: 
    1. It helps you to get production-grade applications up and running quickly without having to worry about configuring your application correctly and safely.
    2. It provides a flexible way to configure Java Beans, XML configurations, and Database Transactions.
    3. It provides a powerful batch processing and manages REST endpoints.
    4. In Spring Boot, everything is auto configured; no manual configurations are needed.
    5. It offers annotation-based spring application.
    6. Eases dependency management.
    7. It includes Embedded Servlet Container.

- **SpringBoot features**: 
    1. Create stand-alone Spring applications.
    2. Embed Tomcat, Jetty or Undertow directly (no need to deploy WAR files).
    3. Provide opinionated 'starter' dependencies to simplify your build configuration.
    4. Automatically configure Spring and 3rd party libraries whenever possible.
    5. Provide production-ready features such as metrics, health checks, and externalized configuration.
    6. Absolutely no code generation and no requirement for XML configuration.


### Spring Framework vs Spring Boot
Spring Boot is built on top of the Spring framework, and it comes with many dependencies that can be plugged into the Spring application. 

**Spring framework** focuses on providing flexibility through its dependency injection feature. It helps to inject the required dependencies quickly but also to develop your application in a loosely coupled fashion.

**Spring Boot,** on the other hand, is focused on shortening the code length and providing you with an easy way to run your Spring application.







### Spring MVC
A Spring MVC is a Java framework which is used to build web applications. It follows the Model-View-Controller design pattern. It implements all the basic features of a core spring framework like Inversion of Control, Dependency Injection.

The Spring Web model-view-controller (MVC) framework is designed around a DispatcherServlet that dispatches requests to handlers, with configurable handler mappings, view resolution, locale and theme resolution as well as support for uploading files. The default handler is based on the @Controller and @RequestMapping annotations, offering a wide range of flexible handling methods. The @Controller mechanism also allows you to create **RESTful** Web sites and applications, through the @PathVariable annotation and other features.

### Spring Security
[baeldung Spring Security series link:][https://www.baeldung.com/security-spring]
Spring Security is a powerful and highly customizable authentication and access-control framework that focuses on providing both authentication and authorization to Java applications. 

Spring Security maintains a filter chain internally where each of the filters has a particular responsibility and filters are added or removed from the configuration depending on which services are required. The ordering of the filters is important as there are dependencies between them.


### Spring Web Flow
Spring Web Flow is the sub-project of the Spring Framework that focuses on providing the infrastructure for building and running rich web applications. It builds on Spring MVC and allows implementing the "flows" of a web application. It spans multiple HTTP requests, has state, deals with transactional data, is reusable, and may be dynamic and long-running in nature.


### Spring Data (Big Family)
Spring Data provides a familiar and consistent, Spring-based programming model for data access while still retaining the special traits of the underlying data store. <br />
Spring Data is a high level Spring Source project whose purpose is to unify and ease the access to different kinds of persistence stores, both relational and non-relational data stores. It is used to reduce your code and simplify your Data Access Layer. <br />
**Spring Data JDBC, Spring Data JPA, Spring Data MongoDB, Spring Data Redis, Spring Data REST.**


### Spring Data JDBC
Spring Data JDBC(Java Database Connectivity), part of the larger Spring Data family, makes it easy to implement JDBC based repositories. This module deals with enhanced support for JDBC based data access layers. It makes it easier to build Spring-powered applications that use data access technologies. <br />

Spring Data JDBC aims at being conceptually easy. In order to achieve this it does NOT offer caching, lazy loading, write behind or many other features of JPA. This makes Spring Data JDBC a simple, limited, opinionated ORM.  <br />
@Query, @EnableJdbcRepositories.  <br />
Only for relational database.  <br />
JDBC is an interface for interacting with a database using pure SQL - sending queries and retrieving results.  


### Spring Data JPA
Part of Spring Data family, they are interfaces with methods supporting CRUD(create, read, update, and delete)records against a back end data store.

Spring Data JPA(Java Persistence API), part of the larger Spring Data family, makes it easy to easily implement JPA based repositories. This module deals with enhanced support for JPA based data access layers. It makes it easier to build Spring-powered applications that use data access technologies.<br />
Spring Data JPA repositories are interfaces with methods supporting CRUD(creating, reading, updating, and deleting) records/database interactions. 


### JDBC vs JPA
**JDBC** is a standard for Database Access. CRUD operations. One of the issues with traditional JDBC apps is that you can often have some crappy code where lots of mapping between data sets and objects occur, logic is mixed in with SQL. 

**JPA** is a standard for ORM(Object Relational Mapping). This standard allows you to bind Java objects to records in a relational database. Allows the developer to retrieve, store, update, and delete data in a relational database using Java objects. 
This can "hide" the SQL from the developer so that all they deal with are Java classes, and the provider allows you to save them and load them magically.  Mostly, XML mapping files or annotations on getters and setters can be used to tell the JPA provider which fields on your object map to which fields in the DB. The most famous JPA provider is *Hibernate*.


### Spring Data MongoDB
Provides integration with the MongoDB document database. Key functional areas of *Spring Data MongoDB* are a POJO centric model for interacting with a MongoDB DBCollection and easily writing a Repository style data access layer. MongoTemplate, 

### Spring Data Redis
Provides easy configuration and access to Redis from Spring applications. It offers both low-level and high-level abstractions for interacting with the store, freeing the user from infrastructural concerns. RedisTemplate, 



### Spring Cloud
Spring Cloud provides an approach where all the **configurations** across environments for all the microservices are stored in a Git reporsity, called **Spring Cloud Config Server**, then it exposes this information to all the microservices. Storing the configurations in such a centralized location makes it easier for the operations team to manage the application / architecture. (Eureka)

**Features:**
- Distributed/versioned configuration
- Service registration and discovery
- Routing
- Service-to-service calls
- Load balancing
- Circuit Breakers
- Global locks
- Leadership election and cluster state
- Distributed messaging

**Thymeleaf**: a Java-based library used to create a web application. It provides a good support for serving a XHTML/HTML5 in web applications. 

**Eureka Server**: is an application that holds the information about all client-service applications. Every Micro service will register into the Eureka server and Eureka server knows all the client applications running on each port and IP address. Eureka Server is also known as **Discovery Server**.

**Eureka Client**: register the Spring Boot Micro service application into the Eureka Server. The @EnableEurekaClient annotation makes your Spring Boot application act as a Eureka client.

**Zuul Proxy Server**: a gateway application that handles all the requests and does the dynamic routing of microservice applications. The Zuul Server is also known as Edge Server. **Internally, Zuul uses Netflix Ribbon** to look up for all instances of the service from the service discovery (Eureka Server). <br />
For Example, "/api/user" is mapped to the user service and "/api/products" is mapped to the product service and Zuul Server dynamically routes the requests to the respective backend application.



**Cloud Configuration Server**: a centralized application that manages all the application related configuration properties. Spring Cloud Configuration Server lets developers to load the new configuration properties without restarting the application and without any downtime.


**Actuator**: provides secured endpoints for monitoring and managing your Spring Boot application.

**Admin Server/Client**: if you have ‘n’ number of applications, every application has separate actuator endpoints. Admin Server is an application used to manage and monitor your Microservice application. Spring Boot Admin UI can manage and monitor all your Spring Boot application Actuator endpoints at one place.
For monitoring and managing your microservice application via Spring Boot Admin Server, you should add the Spring Boot Admin starter client dependency and point out the Admin Server URI into the application properties file.

**Swagger2**: an open source project used to generate the REST API documents for RESTful web services. It provides a user interface to access our RESTful web services via the web browser.


**Sleuth**: tracing logs. Sleuth logs are printed in the following format 
[application-name,traceid,spanid,zipkin-export].
Most developers face difficulty of tracing logs if any issue occurred. This can be solved by Spring Cloud Sleuth and ZipKin server for Spring Boot application.
    - Application-name = Name of the application
    - raceid = each request and response traceid is same when calling same service or one service to another service.
    - Spanid = Span Id is printed along with Trace Id. Span Id is different every request and response calling one service to another service.
    - Zipkin-export = By default it is false. If it is true, logs will be exported to the Zipkin server.

**ZipKin Server**: Zipkin is an application that monitors and manages the Spring Cloud Sleuth logs of your Spring Boot application.

**Flyway**: a version control application to evolve your Database schema easily and reliably across all your instances.

**Hytrix**: Spring Cloud Netflix Hystrix – the fault tolerance library. Hystrix implements the Circuit Breaker enterprise pattern, which is describing a strategy against failure cascading at different levels in an application. Hystrix is watching methods for failing calls to related services. If there is such a failure, it will open the circuit and forward the call to a fallback method.


**Apache Kafka**: an open source project used to publish and subscribe the messages based on the fault-tolerant messaging system. It is fast, scalable and distributed by design. 

**Mockito**: mock Spring Beans for testing. 

**Log4j**: is a Java-based logging utility/logging frameworks.


### Netflix OSS Components
- Gateway Service: Zuul.
- Registry Service: Eureka.
- Dynamic Properties: Archaius.
- REST client: Ribbon for load balancing. @Bean @Loadbalanced, @RibbonClient()
- Circuit Breaker: Hystrix. 

## Message System
### SNS, SQS,


### Kafka
Apache Kafka is a distributed publish-subscribe messaging system and a robust queue that can handle a high volume of data and enables you to pass messages from one end-point to another. 
Kafka is suitable for both offline and online message consumption. 
Kafka messages are persisted on the disk and replicated within the cluster to prevent data loss. Kafka is built on top of the ZooKeeper synchronization service. It integrates very well with Apache Storm and Spark for real-time streaming data analysis. 
Kafka has better throughput, built-in partitioning, replication and inherent fault-tolerance, which makes it a good fit for large-scale message processing applications.
Kafka is very fast and guarantees zero downtime and zero data loss.


### SOAP(Simple Object Access Protocol)
It is a messaging protocol specification for exchanging structured information in the implementation of web services in computer networks. It uses XML Information Set for its message format, and relies on application layer protocols, most often Hypertext Transfer Protocol (HTTP), although some legacy systems communicate over Simple Mail Transfer Protocol (SMTP), for message negotiation and transmission.

### RabbitMQ(Basic message queue)




## AWS Key Components
### Compute
- EC2: Elastic Compute Cloud is a part of Amazon.com's **cloud-computing platform**.
- Lambda: It is a computing service that runs code in response to events and automatically manages the computing resources required by that code. It allows you to run code in the  AWS Cloud without managing servers.

### Storage
- S3: Simple Storage Service, provides object storage through a web service interface. Amazon S3 is a REST service, and you can send a request by using the REST API or the AWS SDK wrapper libraries that wrap the underlying Amazon S3 REST API.

    ```
    // To copy the files from EC2 to S3, cp command
    aws s3 cp <Fully Qualified Local filename> s3://<S3BucketName>
    // To copy the files from S3 to EC2
    aws s3 cp s3://<S3BucketName> <Fully Qualified Local filename/Directory>
    ```

### Route 53
A DNS web service.

### AWS CLI
The AWS Command Line Interface (CLI). aws-shell to manage AWS services.
```
// copy from local PC to S3, or use SnowBall app
aws s3 cp MyFolder s3://bucket-name/myfolder —- recursive [–region us-west-2]

//Synchronize the contents of a local folder with a copy in an S3 bucket.
$ aws s3 sync myfolder s3://mybucket/myfolder --exclude *.tmp

// To copy the files from EC2 to S3, cp command
aws s3 cp <Fully Qualified Local filename> s3://<S3BucketName>

// To copy the files from S3 to EC2
aws s3 cp s3://<S3BucketName> <Fully Qualified Local filename/Directory>

// Display subsets of all available ec2 images
aws ec2 describe-images | grep ubuntu

// List the sizes of an S3 bucket and its contents
aws s3api list-objects --bucket BUCKETNAME --output json --query "[sum(Contents[].Size), length(Contents[])]"

$ asw ec2 describe-instances
$ aws ec2 start-instances --instance-ids i-1348636c
$ aws help
$ aws autoscaling help

```

### IAM
Identity and Access Management (IAM) enables users to manage access to AWS services and resources securely. 


### AMI
An Amazon Machine Image (AMI) is a template that contains a software configuration (for example, an operating system, an application server, and applications) required to launch an instance. From an AMI, you launch an instance, which is a copy of the AMI running as a virtual server in the cloud. You can launch instances from as many different AMIs as you need. <br />
The types of AMI provided by AWS are: Instance store backed, EBS backed

**What the different between an instance and AMI is?** <br />
From a single AMI, you can launch multiple types of instances.  An instance type defines the hardware of the host computer used for your instance. Each instance type provides different computer and memory capabilities.  Once you launch an instance, it looks like a traditional host, and we can interact with it as we would with any computer.

**An AMI includes the following things**
A template for the root volume for the instance
Launch permissions decide which AWS accounts can avail the AMI to launch instances
A block device mapping that determines the volumes to attach to the instance when it is launched


### Integration
- SQS: Simple Queue Service is a distributed message queuing service. It supports programmatic sending of messages via web service applications as a way to communicate over the Internet.
- SNS: Simple Notification Service. It is distributed queuing service which acts as a mediator for two controllers. It provides a low-cost infrastructure for the mass delivery of messages, predominantly to mobile users.

### DB
- RDS: Relational Database Service is a distributed relational database. It is a web service running "in the cloud" designed to simplify the setup, operation, and scaling of a relational database for use in applications.

### DynamoDB
It is a fully managed proprietary NoSQL database service that supports key–value and document data structures.

### DocumentDB (MongoDB)
It is a managed proprietary NoSQL database service that supports document data structures and has limited support for MongoDB workloads.



### VPC
Virtual Private Cloud. It allows you to customize your networking configuration. It is a network which is logically isolated from another network in the cloud. It allows you to have your IP address range,  internet gateways, subnet and security groups.

### ECS/ECR
- ECS: Elastic Container Service. Enables users to easily run and manage container workloads on customer-managed infrastructure. 
- ECR: Elastic Container Registry, is a fully managed container registry that makes it easy to store, manage, share, and deploy your container images and artifacts.
- Fargate: AWS Fargate is a technology that you can use with Amazon ECS to run containers without having to manage servers or clusters of Amazon EC2 instances. With Fargate, you no longer have to provision, configure, or scale clusters of virtual machines to run containers.


### IAAS
**Infrastructure** as a service, providing infrastructure services based on cloud computing technology. IaaS Amazon Service is used to replace physical resources, such as servers, with virtual resources hosted and managed by Amazon. 

### PAAS
**Platforms** as a Service (PaaS) removes the need for organizations to manage the underlying infrastructure (usually hardware and operating systems) and allows you to focus on the deployment and management of your applications.

### SAAS
**Software** as a service (SaaS) products, you deploy software hosted on AWS infrastructure and grant buyers access to the software in your AWS environment. 


### ELB: Elastic Load Balancing

### AWS CodeBuild
A fully managed continuous integration service that compiles source code, runs tests, and produces software packages that are ready to deploy. CodeBuild scales continuously and processes multiple builds concurrently. Customer build env, 




## Build
### SpringBoot
- executable Jar
- **JAR** stands for Java ARchive. It's a file format based on the popular ZIP file format and is used for aggregating many files into one. The only archive format that is cross-platform; the only format that handles audio and image files as well as class files; backward-compatible with existing applet code; an open standard, fully extendable, and written in java; the preferred way to bundle the pieces of a java applet. 
(After test, package all JAR file, then to deploy it.)

- **WAR** stand for Web application ARchive. It is a file used to distribute a collection of JAR-files, JavaServer Pages, Java Servlets, Java classes, XML files, tag libraries, static web pages and other resources that together constitute a web application. 

### Maven / Gradle
- structure
- lify cycle(compile, test, package, install..)
- dependency management
- plugins



## Project management
### Maven

### Version Control
- Git: use for version control of the code.
- SVN:

### Issue Tracking tools
- **Jira**: is a proprietary issue tracking product that allows bug tracking and agile project management.

### Analysis Tools
- SonarQube: a code quality inspection platform, automatic reviews with static analysis of code to detect bugs, coding errors, duplicate code blocks, coding standards, unit tests, code coverage, code complexity and security weakness. Offer reports.

- JaCoCo: to keep track of unit test coverage(code coverage) and generate reports.
- Cobertura: to keep track of unit test coverage(code coverage) and generate reports.







## Test / Quality Analysis

### Unit Test vs Integration Test
**Unit test**: is a way of testing a unit - the smallest piece of code that can be logically isolated in a system.

**Integration test**, test services working well bewteen each other. is a type of testing where software modules are integrated logically and tested as a group. 

**Performance test**: Performance testing is a testing measure that evaluates the speed, responsiveness and stability of a computer, network, software program or device under a workload. Organizations will run performance tests in order to identify performance-related bottlenecks.


### Manual Test vs Automation Test
**Manual Test**: requires a tester to play the role of an end user whereby they use most of the application's features to ensure correct behavior.  
**Automation Test**: is a Software testing technique to test and compare the actual outcome with the expected outcome. This can be achieved by writing test scripts or using any automation testing tool. 

### Maven
Test can be started Automatically by Maven. 

### JUnit

### Mockito
When testing, we can use Mockito to mock the dependency injection of objects in a Spring Boot application. Therefore, we can suppose all dependent objs working in testing. 

When testing, make sure all dependent object working. Mock sth to be inject into the test. Fake an instance. 
when(XXX mock object or method).thenReturn();
simulate a return, exception, 


### TDD / BDD
Test Driven Development: get requirement -> (write test -> run test -> test fail -> run code) -> write test ...-> successful test. Use test to build code base. Take lots of time. 

Behavior Dirven Development: write behavior scripts, use Cucumber and Karate tool to test. 


### API test( RESTAssured), PostMan


### PMD/SonaQube Report(Static code scan), Jacoco coverage report





## DevOps

### Jar file vs War file
- **JAR** stands for Java ARchive. Convert between Java code and JSON. 
It's a file format based on the popular ZIP file format and is used for aggregating many files into one. The only archive format that is cross-platform; the only format that handles audio and image files as well as class files; backward-compatible with existing applet code; an open standard, fully extendable, and written in java; the preferred way to bundle the pieces of a java applet. 
- **WAR** stand for Web application ARchive. It is a file used to distribute a collection of JAR-files, JavaServer Pages, Java Servlets, Java classes, XML files, tag libraries, static web pages and other resources that together constitute a web application. 


### CI/CD continuous integration, continuous delivery.
CI/CD is a method to frequently deliver apps to customers by introducing automation into the stages of app development. The main concepts attributed to CI/CD are continuous integration, continuous delivery, and continuous deployment.  <br />
Specifically, CI/CD introduces ongoing automation and continuous monitoring throughout the lifecycle of apps, from integration and testing phases to delivery and deployment. Taken together, these connected practices are often referred to as a "CI/CD pipeline" and are supported by development and operations teams working together in an agile way with either a DevOps or site reliability engineering (SRE) approach. 

DevOps tools: Jenkins, Docker, Maven, Kubernetes, Chef, 


### Jenkins
A tool uses for CI/CD. It has a feature called Pipelines: Pull -> Build -> Test -> Package -> Deploy. And return a file.  <br />
setting up a Pipeline project means writing a script that will sequentially apply some steps of the process we want to accomplish.

STEPS:
1. Wrap the application Jar file into Dockerfile.

2. Set Docker congif(Run Docker in Jenkins Docker), AWS ECS to process Docker image.
    Create CloudFormation(AWS templating language) template with YAML for application to create resources in AWS. Build CloudFormation env, stack.
    ECS cluster: where to deploy ECS tasks
    ECS task definition: description of how Docker image should run.
    ECS service: create and manage ECS tasks, making surn running well.
    Security group: prots, IP address for traffic from/to.

3. Config Dockerfile(how to build Docker image), config Jenkinsfile, Jenkinsfile-aws.

4. Use Jenkins to deploy Docker, AWS; add their credentials in Jenkins.
    Use aws-credentials, and pipeling-aws. scriptPath "Jenkinsfile-aws"

5. Define the pipeline(Jenkinsfile): triggers,stage, steps
    - Build, 
    - Test, 
    - Build Docker image: jar file -> docker image 
    - Push Docker image: push images to a remote repository, AWS ECS/Docker Hub.
    - Deploy to AWS
6. Initialize seed-job, define Jenkins pipeline for jobs, run the Deploy to AWS stage.
7. Access AWS deploy: Aws console -> services -> ClouldFormation -> Stack

The end result will be that we, the user, will be able to make API calls to our Spring Boot API application running as a Docker container in AWS, via its public IP address.


**Pipeling:** a set of instructions given in the form of code for continuous delivery and consists of instructions needed for the entire build process. With pipeline, you can build, test, and deliver the application.

**Node:** The machine on which Jenkins runs is called a node. A node block is mainly used in scripted pipeline syntax.

**Stage:** A stage block contains a series of steps in a pipeline. That is, the build, test, and deploy processes all come together in a stage. Generally, a stage block is used to visualize the Jenkins pipeline process.

**Step:** A step is nothing but a single task that executes a specific process at a defined time. A pipeline involves a series of steps.


**Checkstyle, Static Analysis Collector and JUnit plugins**. (Compilation and Analysis, Checkstyle, Tests and Deployment, Unit tests, Integration tests, Staging)


**Build a Pipeline**


**
Part 1: writing a Spring Boot application and setting up a Jenkins pipeline to build it (this article)


Part 2: wrapping the application in a Docker image, building it in Jenkins, then pushing it to Docker Hub



Part 3: deploying the Docker image as a container from Jenkins into AWS.





**Check Result**
Logs: log messages
Checkstyle Warnings: code analysis
Test Result: the full test report of each test file with its d uration and status




### Docker (ECR)
**Docker image:** is an immutable file that contains the source code, libraries, dependencies, tools, and other files needed for an application to run.
- Docker images act as a set of instructions to build a Docker container, like a template. 
- Due to their read-only quality, these images are sometimes referred to as snapshots. They represent an application and its virtual environment at a specific point in time. 
- The default docker images will show all top level images, their repository and tags, and their size.
- Docker images have multiple layers, each one originates from the previous layer but is different from it.
- Images are just templates, can not be run. Must use that template as a base to build a container.


**Docker container**: is a running image,  is a virtualized run-time environment where users can isolate applications from the underlying system. 
- Once you create a container, it adds a writable layer on top of the immutable image, meaning you can now modify it.
- When you run a containerized environment, you essentially create a read-write copy of that filesystem (docker image) inside the container. This adds a container layer which allows modifications of the entire copy of the image.
- You can create an unlimited number of Docker images from one image base.



### AWS ECS: Elastic Container Service.
Enables users to easily run and manage container workloads on customer-managed infrastructure. 



### Kubernetes
is an open-source container-orchestration system for automating computer application deployment, scaling, and management.
Kubernetes is a portable, extensible, open-source platform for managing containerized workloads and services, that facilitates both declarative configuration and automation. 













## Security
### Encode / Encryption / Hash
**Encode** is the process of converting data from one format to another and has nothing to do with cryptography.
**Encryption**<!-- (加密) --> is used to scramble <!-- 争夺 --> or encode a message or a file so that unauthorized users can’t tamper <!-- 篡改 --> with or steal sensitive information. Purpose of encryption is to transmit data securely.
**Hashing**: is the process of converting an input of variables to a fixed size array of numbers and letters using a mathematical function. The objective of using hashing is to verify data to prevent anybody from changing the content or corrupting it.

### Basic HTTP Authentication(username/password)
In the context of an HTTP transaction, basic access authentication is a method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request. 

### HTTP Authorization Header
The HTTP Authorization request header contains the credentials to authenticate a user agent with a server.

### Cookies
A cookie is a piece of data that is stored on each individual browser (the browser you’re using) that sends that data to the server that the web app is communicating with, on each request.

### Sessions
A session is a collection of data stored on a server (that is the back-end of the web app) that is associated with a user, usually via a cookie containing an id like the user’s id.


### JWT (JSON Web Token)
[JWT](https://www.javainuse.com/spring/boot-jwt) <br />
JWT is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. The client will need to authenticate with the server using the credentials only once.

During this time the server validates the credentials and returns the client a JSON Web Token(JWT). For all future requests the client can authenticate itself to the server using this JSON Web Token(JWT) and so does not need to send the credentials like username and password. A JWT payload can contain things like user ID so that when the client again sends the JWT, you can be sure that it is issued by you. 

In the payload of the JWT is visible to everyone. Should not have password, and can encrypt.

Structure: **header.payload.signature**
Base64 Encoding.
Header: "typ":"JWT", "alg":"RS512";
Payload: claims. names..
Signature: hash of the header, payload using the hashing alg. var signature = hashAlgRS512(ste, secret).



### OAuth2
‘OF’ OAuth is an open-standard authorization protocol that provides applications the ability for "secure designated access". **OAuth doesn’t share password data but instead uses authorization tokens to prove an identity between consumers and service providers.** (For example, you can tell Facebook that it’s OK for ESPN.com to access your profile or post updates to your timeline without having to give ESPN your Facebook password.)


### Single-sign-on(SSO)
Single Sign On is a centralized session and user authentication service in which **one set of login credentials can be used to access multiple applications**.  in its simplicity; the service authenticates you on one designated platform, enabling you to then use a plethora of services without having to log in and out each time.


### Authentication vs Authorization
**Authentication**: refers to the process of **confirming identity**, validating who they claim to be. Whether the user is vaild or not. (DB , CDAP, AD)

- Determines whether users are who they claim to be.
- Challenges the user to validate credentials (for example, through passwords, answers to security. - questions, or facial recognition).
- Usually done before authorization.
- Generally, transmits info through an ID Token.
- Generally governed by the OpenID Connect (OIDC) protocol.

**Authorization**: refers to the process of verifying what a user could access to. Authorization happens after a user’s identity has been successfully authenticated. Rule based, super admin. valid to some import operation: access CPU? memory.

- Determines what users can and cannot access.
- Verifies whether access is allowed through policies and rules.
- Usually done after successful authentication.
- Generally, transmits info through an Access Token.
- Generally governed by the OAuth 2.0 framework.


### Server Side validation (@Valid)
Validations can be performed on the server side or on the client side.  
In the **Server Side Validation**, the input submitted by the user is being sent to the server. After the validation process on the Server Side, the feedback is sent back to the client by a new dynamically generated web page.  
**Client Side Validation**  
In the Client Side Validation you can provide a better user experience by responding quickly at the browser level. When you perform a Client Side Validation, all the user inputs validated in the user's browser itself. Client Side validation does not require a round trip to the server, so the network traffic which will help your server perform better. 


### CORS
**Cross-origin resource sharing** is a browser mechanism which enables controlled access to resources located outside of a given domain. 

For example, your web application is running on 8080 port and by using JavaScript you are trying to consuming RESTful web services from 9090 port. Under such situations, you will face the Cross-Origin Resource Sharing security issue on your web browsers.

### Basic Spring Security configuration
[Spring Security Architecture]{https://spring.io/guides/topicals/spring-security-architecture}

[Java Config for Spring Security]{https://www.baeldung.com/java-config-spring-security}








## SDE Qestion

What will you do after getting a new task?

What if the project is running slow?

How to fix an error or exception occured on the server?
1. try reproduce test, to find what's wrong. check logs. 

How do you do code review? or what kind of code is good code?

What are the aspects to consider to start a new project if you are the technical lead?

Do you have a complete picture of SDLC?

What is the typical day of a software engineer?




## Other Concepts

### Agile
Agile software development is a process that focuses on incremental delivery by the team as a whole. The project is broken up into small chunks that are able to be completed within a given timeframe called ‘sprints.’

### Scrum

### Functional Programming vs OOP
- Functional programming is used for performing many different operations for which the data is fixed. Object-oriented programming used for performing a few operations which are having common behavior and different variants.
- Functional programming has a stateless programming model. Object-oriented programming has a stateful programming model.
- In functional programming, a state does not exist. In object-oriented programming, the state exists.
- In functional programming, a function is the primary manipulation unit. In object-oriented, an object is the primary manipulation unit.
- In functional programming, its functions have no side effects means it does not impact code running on multiple processors. In Object-oriented programming, its methods can have side effects and may put an impact on processors.
- In functional programming, the main focus of programming is what are we doing. In object-oriented programming, the main focus of programming is how are we doing.
- Functional programming mainly supports abstraction over data and abstraction over behavior. Object-oriented programming mainly supports abstraction over data only.
- Functional programming provides high performance in processing large data for applications. Object-oriented programming is not good for big data processing.
- Functional programming does not support conditional statements. In Object-oriented programming, conditional statements can be used like if-else statements and switch statement.


|   |   Functional Programming  |   OOP    |
|----|----|----|
|  Definition | emphasizes on evaluation of functions  | based on concept of objects  |
| data  | uses immutable data  | uses mutable data  |
| Model  | follow declarative programming model  | follow imperative programming model  |
| Parallel  | support  | not support  |
| Execution  | statement can be exe in any order  | in particular order  |
| Iteration | recursion  | loops  |
| Element  | variables and functions  | objects and methods  |
| Use  | be used only when there are few things with more operations  | many things with few operations  |





### Callback
A callback method is a method that allows the subject to signal to the client that some desired action has completed. In some cases, the subject can use this callback to perform actions — such as mapping results.

### Apache Family
Tomcat, Kafka, Spark, Perl, 

### Netflix OSS Components
- Gateway Service: Zuul.
- Registry Service: Eureka.
- Dynamic Properties: Archaius.
- REST client: Ribbon.
- Circuit Breaker: Hystrix. 











# Apache Kafka

### Messaging System
A Messaging System is responsible for transferring data from one application to another, so the applications can focus on data, but not worry about how to share it. 
Distributed messaging is based on the concept of reliable message queuing.
Messages are queued asynchronously between client applications and messaging system. Two types of messaging patterns are available − one is point to point and the other is publish-subscribe (pub-sub) messaging system. Most of the messaging patterns follow pub-sub.

### Point to Point Messaging System
In a point-to-point system, messages are persisted in a queue. One or more consumers can consume the messages in the queue, but a particular message can be consumed by a maximum of one consumer only. Once a consumer reads a message in the queue, it disappears from that queue.

### Publish-Subscribe Messaging System
In the publish-subscribe system, messages are persisted in a topic. In the Publish-Subscribe system, message producers are called publishers and message consumers are called subscribers. 


### Apache Kafka messaging system
Apache Kafka is a distributed publish-subscribe messaging system and a robust queue that can handle a high volume of data and enables you to pass messages from one end-point to another. Kafka is suitable for both offline and online message consumption. Kafka messages are persisted on the disk and replicated within the cluster to prevent data loss. Kafka is built on top of the ZooKeeper synchronization service. It integrates very well with Apache Storm and Spark for real-time streaming data analysis.
Kafka has better throughput, built-in partitioning, replication and inherent fault-tolerance, which makes it a good fit for large-scale message processing applications.Kafka is very fast and guarantees zero downtime and zero data loss.

**Benefits:**
- Reliability − Kafka is distributed, partitioned, replicated and fault tolerance.
- Scalability − Kafka messaging system scales easily without down time.
- Durability − Kafka uses Distributed commit log which means messages persists on disk as fast as possible, hence it is durable.
- Performance − Kafka has high throughput for both publishing and subscribing messages. It maintains stable performance even many TB of messages are stored.

**Usages:**
- **Metrics** − Kafka is often used for operational monitoring data. This involves aggregating statistics from distributed applications to produce centralized feeds of operational data.
- **Log Aggregation Solution** − Kafka can be used across an organization to collect logs from multiple services and make them available in a standard format to multiple con-sumers.
- **Stream Processing** − Popular frameworks such as Storm and Spark Streaming read data from a topic, processes it, and write processed data to a new topic where it becomes available for users and applications. Kafka’s strong durability is also very useful in the context of stream processing.


### RabbitMQ vs Kafka ？
As general guidance, I’d use RabbitMQ for message passing to replace some RPC scenarios, or to implement a lightweight EDA. If you set it up in the correct way, RabbitMQ can carry you a long way before you need a heavier solution.
If your needs are more complex and elaborated, Kafka is probably the way to go. Nowadays you can use cloud services like Confluent or Cloudkarafka that make it easier for you to set up a Kafka cluster with a few clicks and start testing.


## Kafka Components

### Topics
A stream of messages belonging to a particular category is called a topic. Data is stored in topics.

Topics are split into partitions. For each topic, Kafka keeps a mini-mum of one partition. Each such partition contains messages in an immutable ordered sequence. A partition is implemented as a set of segment files of equal sizes.


### Partition
Topics may have many partitions, so it can handle an arbitrary amount of data.

   
### Partition offset
Each partitioned message has a unique sequence id called as offset.

   
### Replicas of partition
Replicas are nothing but backups of a partition. Replicas are never read or write data. They are used to prevent data loss.


### Brokers
Brokers are simple system responsible for maintaining the pub-lished data. Each broker may have zero or more partitions per topic. Kafka brokers are stateless, so they use ZooKeeper for maintaining their cluster state. One Kafka broker instance can handle hundreds of thousands of reads and writes per second and each bro-ker can handle TB of messages without performance impact. Kafka broker leader election can be done by ZooKeeper.

Assume, if there are N partitions in a topic and N number of brokers, each broker will have one partition.
Assume if there are N partitions in a topic and more than N brokers (n + m), the first N broker will have one partition and the next M broker will not have any partition for that particular topic.
Assume if there are N partitions in a topic and less than N brokers (n-m), each broker will have one or more partition sharing among them. This scenario is not recommended due to unequal load distri-bution among the broker.



### Kafka Cluster
Kafka’s having more than one broker are called as Kafka cluster. A Kafka cluster can be expanded without downtime. These clusters are used to manage the persistence and replication of message data.


### Producers
Producers are the publisher of messages to one or more Kafka topics. Producers send data to Kafka brokers. Every time a producer pub-lishes a message to a broker, the broker simply appends the message to the last segment file. Actually, the message will be appended to a partition. Producer can also send messages to a partition of their choice.


### Consumers
Consumers read data from brokers. Consumers subscribes to one or more topics and consume published messages by pulling data from the brokers.


### Leader
Leader is the node responsible for all reads and writes for the given partition. Every partition has one server acting as a leader.


### Follower
Node which follows leader instructions are called as follower. If the leader fails, one of the follower will automatically become the new leader. A follower acts as normal consumer, pulls messages and up-dates its own data store.


### ZooKeeper
ZooKeeper is used for managing and coordinating Kafka broker. ZooKeeper service is mainly used to notify producer and consumer about the presence of any new broker in the Kafka system or failure of the broker in the Kafka system. As per the notification received by the Zookeeper regarding presence or failure of the broker then producer and consumer takes decision and starts coordinating their task with some other broker.


### Producers
Producers push data to brokers. When the new broker is started, all the producers search it and automatically sends a message to that new broker. Kafka producer doesn’t wait for acknowledgements from the broker and sends messages as fast as the broker can handle.


### Consumers
Since Kafka brokers are stateless, which means that the consumer has to maintain how many messages have been consumed by using partition offset. If the consumer acknowledges a particular message offset, it implies that the consumer has consumed all prior messages. The consumer issues an asynchronous pull request to the broker to have a buffer of bytes ready to consume. The consumers can rewind or skip to any point in a partition simply by supplying an offset value. Consumer offset value is notified by ZooKeeper.















