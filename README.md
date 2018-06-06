# PopularMovies2
A simple Android app that helps users discover most popular and most rated movies. Project 1 &amp; 2 of Udacity Android Developer Nanodegree.

Popular Movies App
Build Status Codacy Badge Codacy Badge

A simple Android app, that helps user to discover movies. This is Project 1 & Project 2 of Udacity's Android Developer Nanodegree.

Features:

Discover the most popular, the highest rated and the most rated movies
Watch movie trailers and teasers
Read reviews from other users
Mark movies as favorites
Search for movies
Offline work
Material design
UI optimized for phone and tablet
Download:

You can download APK on releases page.

Screenshots








Developer setup
Requirements
Java 8
Latest version of Android SDK and Android Build Tools
API Key
The app uses themoviedb.org API to get movie information and posters. You must provide your own API key in order to build the app.

Just put your API key into ~/.gradle/gradle.properties file (create the file if it does not exist already):

MY_MOVIE_DB_API_KEY="abc123"
Building
You can build the app with Android Studio or with ./gradlew assembleDebug command.

Testing
This project integrates a combination of local unit tests, instrumented tests and code analysis tools.

Just run build.sh to ensure that project code is valid and stable. This will run local unit tests on the JVM, instrumented tests on connected device (or emulator) and analyse code with Checkstyle, Findbugs and PMD.

License
Copyright 2016 Maksim Moiseikin

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
