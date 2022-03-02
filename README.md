# GitHubSearch
 :octocat: 🧐 A GitHub Search Android apps using Coroutine Flow, Dagger 2, MVVM, Modularization, Clean Architecture, Airbnb Epoxy, and Unit Test.
There are 2 features on this apps:
1. Search GitHub users by name.
2. Get detail information of the user including Profile and Repository with load more features.

## 💡 Stack and Libraries
* [Kotlin](https://https://kotlinlang.org/) - built with 100% Kotlin.
* [Coroutines Flow](https://github.com/alvayonara/OpenWeatherApps#:~:text=with%20100%25%20Kotlin.-,Coroutines%20Flow,-%2D%20emit%20multiple%20values) - emit multiple values sequentially (flatMap, zip, etc.)
* [Jetpack Components](https://developer.android.com/jetpack/)
  - Navigation
  - ViewModel
  - Material Components
  - ViewBinding
  - KTX
* [Dagger 2](https://dagger.dev/) - dependency injection.
* [Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html) - separates code into layers.
* [Modularization](https://developer.android.com/guide/app-bundle/play-feature-delivery/) - separating logical components of project into discrete modules.
* [Epoxy](https://github.com/airbnb/epoxy) - library for building complex screens in a RecyclerView.
* [Retrofit2](https://github.com/square/retrofit/) - REST APIs.
* [Moshi](https://github.com/square/moshi) - modern JSON library.
* [Glide](https://github.com/bumptech/glide/) - load images.
* [Timber](https://github.com/JakeWharton/timber/) - logger.
* [Chucker](https://github.com/ChuckerTeam/chucker/) - an HTTP inspector.
* [MockK](https://mockk.io/) - mocking unit testing.

## 💎 Architecture
This apps uses Clean Architecture to separate code into layers (Data - Domain - Presentation).
![app structure](./image/app-structure.png)

## 📱 App Preview
![app preview](./image/app-preview.png)
