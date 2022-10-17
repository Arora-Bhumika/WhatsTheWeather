# What's The Weather
![appicon](https://user-images.githubusercontent.com/22769589/68296145-f7305d80-00a4-11ea-9cbe-24b18222bfa9.png)

This weather app is a simple weather forecast app, which uses some APIs to fetch 5 day / 3 hour forecast data from the [OpenWeatherMap](https://openweathermap.org/forecast5) and to fetch places,cities,counties,coords etc. from [Algolia Places](https://community.algolia.com/places/). The main goal of this app is to be a sample of how to build an high quality Android application that uses the Architecture components in Kotlin.

<h2 id="Outputs">Outputs</h2>
<p><img height= "200" src="https://user-images.githubusercontent.com/22769589/68296813-82f6b980-00a6-11ea-80bc-7a0e36e6336f.gif" alt="Gif1" />
<img height= "200" src="https://user-images.githubusercontent.com/22769589/73372162-ce94ba00-42c7-11ea-9100-642953ec9c7e.gif" alt="Gif2" />
<img height= "200" src="https://user-images.githubusercontent.com/22769589/68296812-82f6b980-00a6-11ea-946b-ede239a4446a.gif" alt="Gif3" />
<img height= "200" src="https://user-images.githubusercontent.com/22769589/68296815-838f5000-00a6-11ea-86ed-8587458d2bb2.gif" alt="Gif4" /></p>

## Libraries and tools 🛠

<li><a href="https://developer.android.com/topic/libraries/architecture/navigation/">Navigation</a></li>
<li><a href="https://developer.android.com/training/data-storage/shared-preferences">Shared Preferences</a></li>
<li><a href="https://developer.android.com/topic/libraries/architecture/viewmodel">ViewModel</a></li>
<li><a href="https://developer.android.com/topic/libraries/architecture/livedata">LiveData</a></li>
<li><a href="https://square.github.io/retrofit/">Retrofit</a></li>
<li><a href="https://github.com/square/picasso">Picasso</a></li>
<li><a href="https://material.io/develop/android/docs/getting-started/">Material Design</a></li>
<li><a href="https://github.com/lopspower/RxAnimation">RxAnimation</a></li>
<li><a href="https://github.com/algolia/algoliasearch-client-android">Algolia Search API Client for Android</a></li>
<li><a href="https://github.com/loopeer/shadow">Shadow</a></li>

## Architecture
The app uses MVVM [Model-View-ViewModel] architecture to have a unidirectional flow of data, separation of concern, testability, and a lot more.

![Architecture](https://developer.android.com/topic/libraries/architecture/images/final-architecture.png)

## Dependency Graph 🔪
The following diagram shows the dependency graph of the app.

![Screen Shot 2019-11-20 at 12 03 24](https://user-images.githubusercontent.com/22769589/69224544-ce709380-0b8d-11ea-9bb5-51e9ea8828c9.png)
