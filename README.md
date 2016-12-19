### Colloid Lightweight Front-end ###

This repo will serve as a (mostly) light front end for serving web pages associated with colloid-backend endpoints.  Bear in mind, it uses Angular 2, so there's a limit to how lightweight it can be.  It's currently written in dart, so it may become deprecated or I may just add web apps written in other languages to this repo.

#### Requirements ####

+ Dart
	- <a href="https://www.dartlang.org/install">Install Dart SDK</a>

#### Project Files ####

Note: Dart file structure in /lib includes a .css, .dart, .html file for each angular component.  Only .dart files are listed here.

+ lib
	- root_component.dart
		- Used to organize other components and create neat component hierarchy
+ web
	- main.dart
		- Entrypoint to the dart web app, performs bootstrapping
	- index.html
		- Landing page, loads CDN links and root-app

#### TODO ####

+ Fill out the TODO list!