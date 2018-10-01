# Android-Ganje
![Android-Ganje-Banner](https://github.com/Ssisakhti/android-ganje/blob/master/android-ganje-banner.png)

# About

All of the documents, blog posts, videos and books listed below are hand picked to teach us how to build Android apps. If you're brand new to Android development or one of the legendaries in this area, maybe find useful learning resource here.

Anyway, "Ganje" is a persian word that means Closet.

# Languages

[Android Ganje in English](#content-english)

# Content [English]

* [Kotlin](#kotlin)
    * [Nothing](#nothing)
    * [Standard Functions](#standard-functions)
    * [Lambda Expressions](#lambda-expressions)

* [Clean Architecture](#clean-architecture)
* Android Jetpack Components
    * [Android Architecture Components](#android-architecture-components)
        * [Handling lifecycles](#handling-lifecycles)
        * [ViewModel](#viewmodel)
        * [LiveData](#livedata)
* [Networking](#networking)
    * [Retrofit](#retrofit)
* [Dependency Injection](#dependency-injection)
    * [Dagger 2](#dagger-2)

## Kotlin
[Introduction to Kotlin Programming](http://shop.oreilly.com/product/0636920052982.do) [oreilly] [Hadi Hariri]

[The Ultimate Kotlin Tutorials for Beginners](https://www.callicoder.com/categories/kotlin/) [callicoder] [Rajeev Kumar Singh]

[Advanced Kotlin Programming](http://shop.oreilly.com/product/0636920052999.do) [oreilly] [Hadi Hariri]

## Nothing

[The Nature of Nothing in Kotlin](http://the-cogitator.com/2018/06/29/the-nature-of-nothing-in-kotlin.html) [the-cogitator] [Adam Arold]

[Kotlin has Nothing but there is nothing like Nothing in Java](https://medium.com/thoughts-overflow/kotlin-has-nothing-but-there-is-nothing-like-nothing-in-java-cab98e4f4d26) [medium] [Bob]

## Standard Functions
[Mastering Kotlin standard functions: run, with, let, also and apply](https://medium.com/@elye.project/mastering-kotlin-standard-functions-run-with-let-also-and-apply-9cd334b0ef84) [medium] [Elye]

[Exploring the Kotlin standard library](http://beust.com/weblog/2015/10/30/exploring-the-kotlin-standard-library/) [beust] [Cédric Beust]

[the tldr; on Kotlin’s let, apply, also, with and run functions](https://proandroiddev.com/the-tldr-on-kotlins-let-apply-also-with-and-run-functions-6253f06d152b) [medium] [Andre Perkins]

[Exploring Kotlin: Useful Standard Library Functions](http://the-cogitator.com/2018/02/10/exploring-kotlin-useful-stdlib-functions.html) [the-cogitator] [Adam Arold]

## Lambda Expressions
[Lambda Expressions in Kotlin](https://www.baeldung.com/kotlin-lambda-expressions) [baeldung] [ Paul Jervis ]

[Lambda expressions in Kotlin](https://marcin-chwedczuk.github.io/lambda-expressions-in-kotlin) [marcin-chwedczuk.github] [Marcin Chwedczuk]

## Clean Architecture
[Architecting Android...The clean way?](https://fernandocejas.com/2014/09/03/architecting-android-the-clean-way/) [fernandocejas] [Fernando Cejas]

[Architecting Android...The evolution](https://fernandocejas.com/2015/07/18/architecting-android-the-evolution/) [fernandocejas] [Fernando Cejas]

[Architecting Android...Reloaded](https://fernandocejas.com/2018/05/07/architecting-android-reloaded/) [fernandocejas] [Fernando Cejas]

[Android Architecture: Part 1 – Every New Beginning is Hard](https://five.agency/android-architecture-part-1-every-new-beginning-is-hard/) [five] [Tomislav Homan]

[Android Architecture: Part 2 – the clean architecture](https://five.agency/android-architecture-part-2-clean-architecture/) [five] [Tomislav Homan]

[Android Architecture: Part 3 – Applying Clean Architecture on Android](https://five.agency/android-architecture-part-3-applying-clean-architecture-android/) [five] [Tomislav Homan]

[Android Architecture Part 4: Applying Clean Architecture on Android, Hands on (source code included)](https://five.agency/android-architecture-part-4-applying-clean-architecture-on-android-hands-on/) [five] [Mihael Franceković]

[Android Architecture Part 5: How to Test Clean Architecture](https://five.agency/android-architecture-part-5-test-clean-architecture/) [five]

[A Guided Tour inside a clean architecture code base.](https://proandroiddev.com/a-guided-tour-inside-a-clean-architecture-code-base-48bb5cc9fc97) [medium] [Yossi Segev]

[MVVM on Android with the Architecture Components](https://medium.com/@margaretmz/exploring-the-android-architecture-components-117515acfa8) [medium] [Margaret Maynard-Reid]

[Maintainable Architecture – Introduction](https://blog.stylingandroid.com/maintainable-architecture-introduction/) [stylingandroid] [Mark Allison]

[Maintainable Architecture – Separation Of Concerns](https://blog.stylingandroid.com/maintainable-architecture-introduction-2/) [stylingandroid] [Mark Allison]

[Maintainable Architecture – Dependency Injection](https://blog.stylingandroid.com/maintainable-architecture-dependency-injection/) [stylingandroid] [Mark Allison]

[Maintainable Architecture – Lifecycle](https://blog.stylingandroid.com/maintainable-architecture-lifecycle/) [stylingandroid] [Mark Allison]

[Maintainable Architecture – Testing](https://blog.stylingandroid.com/maintainable-architecture-testing/) [stylingandroid] [Mark Allison]

[Maintainable Architecture – Repository](https://blog.stylingandroid.com/maintainable-architecture-repository/) [stylingandroid] [Mark Allison]

[Maintainable Architecture – Five Day Forecast – Data Layer](https://blog.stylingandroid.com/maintainable-architecture-five-day-forecast-data-layer/) [stylingandroid] [Mark Allison]

[Maintainable Architecture – Five Day Forecast – UI Layer](https://blog.stylingandroid.com/maintainable-architecture-five-day-forecast-ui-layer/) [stylingandroid] [Mark Allison]

[Maintainable Architecture – Daily Forecast](https://blog.stylingandroid.com/maintainable-architecture-daily-forecast/) [stylingandroid] [Mark Allison]

[Maintainable Architecture – Readability](https://blog.stylingandroid.com/maintainable-architecture-readability/) [stylingandroid] [Mark Allison]

[Maintainable Architecture – Navigation](https://blog.stylingandroid.com/maintainable-architecture-navigation/) [stylingandroid] [Mark Allison]

## Android Architecture Components
[droidcon NYC 2017 - ViewModels, LiveData and Lifecycles, oh my!](https://www.youtube.com/watch?v=SlZVYkhoSq8) [youtube] [droidcon NYC]

[Guide to App Architecture](https://developer.android.com/jetpack/docs/guide) [android]

[Introduction to Android Architecture Components](https://code.tutsplus.com/tutorials/introduction-to-android-architecture--cms-28749) [tutsplus] [Tin Megali]

[The Missing Google Sample of Android “Architecture Components” Guide.](https://proandroiddev.com/the-missing-google-sample-of-android-architecture-components-guide-c7d6e7306b8f) [medium] [Philippe BOISNEY]

[Basic Example of LiveData and ViewModel](https://medium.com/@taman.neupane/basic-example-of-livedata-and-viewmodel-14d5af922d0) [medium] [taman neupane]

[MVVM architecture, ViewModel and LiveData (Part 1)](https://proandroiddev.com/mvvm-architecture-viewmodel-and-livedata-part-1-604f50cda1) [medium] [Hazem Saleh]

[MVVM architecture, ViewModel and LiveData — Part 2 (DI)](https://proandroiddev.com/mvvm-architecture-viewmodel-and-livedata-part-2-di-1a6b1f96d84b) [medium] [Hazem Saleh]

[ViewModels and LiveData: Patterns + AntiPatterns](https://medium.com/google-developers/viewmodels-and-livedata-patterns-antipatterns-21efaef74a54) [medium] [Jose Alcérreca]

[Android's Architecture Components](https://commonsware.com/AndroidArch/) [Book]

## Handling lifecycles
[Handling lifecycles with lifecycle-aware components ](https://developer.android.com/topic/libraries/architecture/lifecycle) [android]

## ViewModel
[Android Jetpack: ViewModel](https://www.youtube.com/watch?v=5qlIPTDE274) [youtube] [Android Developers]

[ViewModels : A Simple Example](https://medium.com/google-developers/viewmodels-a-simple-example-ed5ac416317e) [medium] [Lyla Fujiwara]

[ViewModels: Persistence, onSaveInstanceState(), Restoring UI State and Loaders](https://medium.com/google-developers/viewmodels-persistence-onsaveinstancestate-restoring-ui-state-and-loaders-fc7cc4a6c090) [medium] [Lyla Fujiwara]

[The death of Presenters and the rise of ViewModels (AAC).](https://proandroiddev.com/the-death-of-presenters-and-the-rise-of-viewmodels-aac-f14d54b419a) [medium] [Mario Sanoguera de Lorenzo]

[Internals of Android Architecture Components Part I — The ViewModel](https://medium.com/the-lair/internals-of-android-architecture-components-part-i-the-viewmodel-d893e362a0d9) [medium] [Josep Rodriguez]

## LiveData
[Android Jetpack: LiveData](https://www.youtube.com/watch?v=OMcDk2_4LSk) [youtube] [Android Developers]

[Life saving LiveData class Android](https://medium.com/@taman.neupane/life-saving-livedata-class-android-b3f36d57d79f) [medium] [taman neupane]

[Basic Example of LiveData and ViewModel](https://medium.com/@taman.neupane/basic-example-of-livedata-and-viewmodel-14d5af922d0) [medium] [taman neupane]

[Android Architecture Components: LiveData](https://code.tutsplus.com/tutorials/android-architecture-component-livedata--cms-29317) [tutsplus] [Tin Megali]

[When and why to use Android LiveData](https://medium.com/sears-israel/when-and-why-to-use-android-livedata-93d7dd949138) [medium] [Giora Shevach]

[Internals of Android Architecture Components Part II— LiveData](https://medium.com/the-lair/internals-of-android-architecture-components-part-ii-livedata-a26a4d11795) [medium] [Josep Rodriguez]

[Architecture Components pitfalls — Part 1 : LiveData and the Fragment lifecycle](https://medium.com/@BladeCoder/architecture-components-pitfalls-part-1-9300dd969808) [medium] [Christophe Beyls]

[LiveData beyond the ViewModel — Reactive patterns using Transformations and MediatorLiveData](https://medium.com/google-developers/livedata-beyond-the-viewmodel-reactive-patterns-using-transformations-and-mediatorlivedata-fda520ba00b7) [medium] [Jose Alcérreca]

[LiveData with SnackBar, Navigation and other events (the SingleLiveEvent case)](https://medium.com/google-developers/livedata-with-snackbar-navigation-and-other-events-the-singleliveevent-case-ac2622673150) [medium] [Jose Alcérreca]

## Networking
[Droidcon Montreal Jake Wharton - A Few Ok Libraries](https://www.youtube.com/watch?v=WvyScM_S88c) [youtube] [Droidcon Montreal]

## Retrofit
[Retrofit Basics](https://futurestud.io/learningpaths/retrofit-basics) [futurestud] [Marcus Pöhls]

[How does Retrofit work](https://proandroiddev.com/how-does-retrofit-work-6ecad1bb683b) [medium] [Mihaly Nagy]

## Dependency Injection

## Dagger 2
[Dagger 2 for Android Beginners — Introduction](https://medium.com/@harivigneshjayapalan/dagger-2-for-android-beginners-introduction-be6580cb3edb) [medium] [Hari Vignesh Jayapalan]

[Dagger 2 for Android Beginners — DI part I](https://medium.com/@harivigneshjayapalan/dagger-2-for-android-beginners-di-part-i-f5cc4e5ad878) [medium] [Hari Vignesh Jayapalan]

[Dagger 2 for Android Beginners — DI part II](https://medium.com/@harivigneshjayapalan/dagger-2-for-android-beginners-di-part-ii-bce68f463bfe) [medium] [Hari Vignesh Jayapalan]

[Dagger 2 for Android Beginners — Dagger 2 part I](https://medium.com/@harivigneshjayapalan/dagger-2-for-android-beginners-dagger-2-part-i-f2de5564ab25) [medium] [Hari Vignesh Jayapalan]

[Dagger 2 for Android Beginners — Dagger 2 part II](https://medium.com/@harivigneshjayapalan/dagger-2-for-android-beginners-dagger-2-part-ii-436c3e3aa15b) [medium] [Hari Vignesh Jayapalan]

[Dagger 2 for Android Beginners — Dagger 2 Advanced part I](https://medium.com/@harivigneshjayapalan/dagger-2-for-android-beginners-advanced-part-i-1e14fccf2cc8) [medium] [Hari Vignesh Jayapalan]

[Dagger 2 for Android Beginners — Dagger 2 Advanced part II](https://medium.com/@harivigneshjayapalan/dagger-2-for-android-beginners-advanced-part-ii-eb6f8d8a8926) [medium] [Hari Vignesh Jayapalan]

[New Android Injector with Dagger 2 — part 1](https://medium.com/@iammert/new-android-injector-with-dagger-2-part-1-8baa60152abe) [medium] [Mert Şimşek]

[New Android Injector with Dagger 2 — part 2](https://medium.com/@iammert/new-android-injector-with-dagger-2-part-2-4af05fd783d0) [medium] [Mert Şimşek]

# Contributing
Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.