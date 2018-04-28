<p align="center"><img width="160" height="160" src="./art/icon.png"></p>

<h1 align="center">UV Index</h1>

<p align="center">A simple ultraviolet index viewer app for demonstrating:<br><i>Instant Apps + Kotlin + Dagger + MVP</i></p>

<p align="center">
  <a href="https://travis-ci.org/mustafaberkaymutlu/uv-index"><img src="https://travis-ci.org/mustafaberkaymutlu/uv-index.svg?branch=master" alt="Build Status"></a>
  <a href="https://github.com/KotlinBy/awesome-kotlin"><img src="https://kotlin.link/awesome-kotlin.svg" alt="Awesome Kotlin Badge"></a>
  <a href="https://github.com/mustafaberkaymutlu/uv-index/blob/master/LICENSE"><img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" alt="License"></a>
</p>

## Built With
* [Weatherbit](https://www.weatherbit.io/)  as weather API
* [Android Instant Apps](https://developer.android.com/topic/instant-apps/index.html)
* [Kotlin](https://kotlinlang.org/)
* [Mosby](https://github.com/sockeqwe/mosby) for MVP
* [Dagger 2](https://google.github.io/dagger/) for Dependency Injection
* [Retrofit](https://github.com/square/retrofit) for HTTP client
* [PermissionsDispatcher](https://github.com/permissions-dispatcher/PermissionsDispatcher) for Runtime Permissions
* [Timber](https://github.com/JakeWharton/timber) for logging
* [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) for line chart
* [Geocoder](https://developer.android.com/reference/android/location/Geocoder.html) for getting address from coordinates or location name 
* [Crashlytics](https://fabric.io/kits/android/crashlytics/install) for crash logging
* Google Location API for receiving user's location

## Demo
<p><img src="./art/demo.gif"></p>

## Getting Started with Development

- Sign up to [Weatherbit](https://www.weatherbit.io/) (they also have a free plan)
- Get your API key
- Put your API key to the `data.Services.API_KEY` constant inside the `:base` module

## TODO
* Move Google Play APIs from `:base` module to `:query` module

## License
    Copyright 2017 Mustafa Berkay Mutlu.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
