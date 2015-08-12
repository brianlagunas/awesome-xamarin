# awesome-xamarin [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A hand-picked bookmark collection of subjectively modern/interesting libraries/tools for Xamarin Android/iOS/WP libraries.

Inspired by [awesome-dotnet](https://github.com/quozd/awesome-dotnet)
  
* [Awesome Xamarin](#awesome-xamarin)
  * [General](#general)
  * [Async](#async)
  * [Cloud](#cloud)
  * [Database/Caching](#database-caching)
  * [Framework](#frameworks)
  * [Fody](#fody)
  * [Game Engine](#game-engine)
  * [Imaging](#imaging)
  * [IOC](#ioc)
  * [Internationalization](#internationalization)
  * [MVVM](#mvvm)
  * [Network](#network)
  * [Security](#security)
  * [Serialization](#serialization)
  * [TDD/BDD](#tdd-bdd)
  * [Tools](#tool)
  * [Wearable](#wearable)
  * [Xamarin.Forms](#xamarin-forms)
  * [XPlat APIs](#xplat-apis)

## General
* [AutoMapper](https://github.com/AutoMapper/AutoMapper) - A convention-based object-object mapper in .NET
* [Humanizer](https://github.com/MehdiK/Humanizer) - Manipulation and displaying of strings, enums, dates, times, timespans, numbers and quantities
* [Fluent Validation](https://github.com/JeremySkinner/FluentValidation) - Fluent interface and lambda expressions for building validation rules
* [Polly](https://github.com/michael-wolfenden/Polly) - Exception handling policies such as Retry, Retry Forever, Wait and Retry or Circuit Breaker
* [Stateless](https://github.com/nblumhardt/stateless) - State Machines

## Async
* [AsyncEx](https://github.com/StephenCleary/AsyncEx) - A helper library for async/await.
* [LinqToAwait](https://github.com/paulcbetts/LinqToAwait) - A Task-based LINQ designed to work with async/await

## Cloud
* [Azure](http://developer.xamarin.com/guides/cross-platform/azure/) - Microsoft Azure
* [FireSharp](https://github.com/ziyasal/FireSharp) - Firebase REST API wrapper

## Database/Caching
* [Akavache](https://github.com/akavache/Akavache) - An Asynchronous Key-Value Store for Native Applications
* [Massive](https://github.com/FransBouma/Massive) - "wrapper" for your DB tables and uses System.Dynamic extensively
* [SQLite.Net-PCL](https://github.com/oysteinkrog/SQLite.Net-PCL) - SQLite 3 databases support, PCL, async

## Fody
* [Fody](https://github.com/Fody/Fody) - Extensible tool for weaving .net assemblies 
* [ReactiveUI.Fody](https://github.com/kswoll/ReactiveUI.Fody) - Generate RaisePropertyChange notifications for properties and ObservableAsPropertyHelper properties
* [AutoDependencyProperty.Fody](https://bitbucket.org/robertvazan/autodependencyproperty.fody/overview) - Automatically generates DependencyProperty boilerplate from simple C# properties
* [PropertyChanged.Fody](https://github.com/Fody/PropertyChanged/) - Injects INotifyPropertyChanged code into properties at compile time

## Framework
* [SimplyMobile](https://github.com/sami1971/SimplyMobile) - Collection of abstracted mobile functionalities

## Game Engine
* [CocosSharp](https://github.com/mono/CocosSharp) - C# implementation of the Cocos2D and Cocos3D APIs
* [MonoGame](https://github.com/mono/MonoGame) - Open source implementation of the Microsoft XNA 4.x Framework 
* [Paradox](https://github.com/SiliconStudio/paradox) - Paradox3D + Silicon Studio .NET

## Imaging
* [Fast & Furious Image Loading](https://github.com/molinch/FFImageLoading) - Xamarin library to load images quickly & easily
* [NGraphics](https://github.com/praeclarum/NGraphics) - Cross platform library for rendering vector graphics
* [Splat](https://github.com/paulcbetts/splat) - Cross platform image loading, colors and stuff
* [EZ-Compress](https://github.com/VictorGrunn/EZ-Compress-for-Xamarin) - A simple image stream compression plugin for Xamarin

## IOC
* [Autofac](https://github.com/autofac/Autofac) - An addictive .NET IoC container
* [Ninject](https://github.com/ninject/ninject) - The ninja of .net dependency injectors
* [TinyIoC](https://github.com/grumpydev/TinyIoC) - Single-class easy IoC container

## Internationalization
* [Vernacular](https://github.com/rdio/vernacular) - Cross Platform Localisation, tools to convert standard strings formats

## MVVM
* Frameworks
  * [MVVMCross](https://github.com/MvvmCross/MvvmCross) - Cross-platform mvvm mobile development framework
	* [Cheesebaron.MvxPlugins](https://github.com/Cheesebaron/Cheesebaron.MvxPlugins) - A collection of plugins
	* [MvxAms](https://github.com/MobiliTips/MvxPlugins) - MVVMCross Azure Mobile Services plugin
	* [MvxForms](https://github.com/MobiliTips/MvxPlugins) - MVVMCross plugin for using Xamarin.Forms
	* [acrmvvmcross](https://github.com/aritchie/acrmvvmcross) - Barcode, Device Info, IO, Network, Settings, Signature, User Dialogs
  * [ReactiveUI](https://github.com/reactiveui/ReactiveUI) - Rx MVVM framework
* [Bind](https://github.com/praeclarum/Bind) - Bind gives you easy two-way data binding between properties of objects.
* [Fody/PropertyChanged](https://github.com/Fody/PropertyChanged) - Injects INotifyPropertyChanged code into properties at compile time

## Network
* [Flurl](https://github.com/tmenier/Flurl) - Flurl is a modern, fluent, asynchronous, testable, portable, buzzword-laden URL builder and HTTP client library.
* [Fusillade](https://github.com/paulcbetts/Fusillade) - set of HttpMessageHandlers that make your mobile applications more efficient and responsive
* [ModernHttpClient](https://github.com/paulcbetts/ModernHttpClient) - Accelerates HTTP requests by using mobile-optimized libs (NSURLSession / OkHttp)
* [Push Notification](https://github.com/rdelrosario/xamarin-plugins/tree/master/PushNotification) - Simple cross platform plugin to handle push notification events such as registering, unregistering and messages arrival on Android and iOS.
* [Reachability](https://github.com/has-taiar/Reachability.Net) - Online/offline connected check
* [Refit](https://github.com/paulcbetts/refit) - The automatic type-safe REST library for Xamarin and .NET
* [RestEase](https://github.com/canton7/RestEase) - Refit on steroids, simpler auth, parsing...
* [Sockets](https://github.com/rdavisau/sockets-for-pcl) - An abstraction over the socket helper classes of .NET and WinRT

## Security
* [PCLCrypto](https://github.com/AArnott/PCLCrypto) - Cryptography for portable class libraries (MD5,...)
* [BoucyCastle.PCL](https://github.com/onovotny/BouncyCastle-PCL) PCL Version of BouncyCastle (Cryptography) targetting .NET, SL, WP and WinRT

## Serialization
* [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json) - Popular high-performance JSON framework for .NET

## TDD/BDD
* [FluentAssertions](http://www.fluentassertions.com/) - TDD/BDD fluent asserts
* [NBehave](https://github.com/nbehave/NBehave) - framework for Behaviour-Driven Development

## Tools
* [PushSharp](https://github.com/Redth/PushSharp) - A server-side library for sending Push Notifications to iOS (iPhone/iPad APNS), Android (C2DM and GCM - Google Cloud Message), Windows Phone, Windows 8, Amazon, Blackberry, and (soon) FirefoxOS devices!
* [Xamaridea](https://github.com/EgorBo/Xamaridea) - Visual Studio extension, opens *.axml files in Android Studio 
* [GradleBindings](https://github.com/EgorBo/Xamarin.GradleBindings) - Visual Studio extension, for referencing gradle libs in Android projects

## Wearable
* [WormHoleSharp](https://github.com/Clancey/WormHoleSharp) - Communication between Watch and iDevice

## Xamarin.Forms
* [Acr-xamarin-forms](https://github.com/aritchie/acr-xamarin-forms) - Camera/Gallery, Barcode Scanning, User Dialogs, Geo-Location, Network Utils, Device Info, Settings, E-Mail, Phone, SMS all for Xamarin.Forms
* [AdvancedTimer](https://github.com/ufuf/AdvancedTimer) - Timer object and its methods are implemented for extended support for timers.
* [Circle Image Control](https://github.com/jamesmontemagno/Xamarin.Plugins/tree/master/ImageCircle) - Simple but elegant way of display circle images in your Xamarin.Forms projects
* [Compass](https://github.com/JarleySoft/Xamarin.Plugins/tree/master/Compass) - Provides and simple way to access the compass on Windows Phone, iOS and Android from you Xamarin.Forms projects
* [Device Orientation](https://github.com/aliozgur/Xamarin.Plugins/tree/master/DeviceOrientation) - Simple way to get device orientation or be notified of orientation changes in your Xamarin.Forms projects
* [NControl](https://github.com/chrfalch/NControl) - Xamarin.Forms control for NGraphics
* [MvxForms](https://github.com/MobiliTips/MvxPlugins) - MVVMCross plugin for using Xamarin.Forms
* [SolTech Xamarin Forms Toolkit](https://github.com/soltechinc/soltechxf) - set of helpful extensions to the Xamarin Forms framework
* [Store Rating Plugin](https://github.com/voxdev/Xamarin.Plugins) - Rate app popup
* [SVG](https://github.com/paulpatarinski/Xamarin.Forms.Plugins/tree/master/SVG) - SVG file format support
* [Toasts Plugin](https://github.com/EgorBo/Toasts.Forms.Plugin) - A simple way of showing some notifications inside your Xamarin.Forms application
* [TwinTechsFormsLib](https://github.com/twintechs/TwinTechsFormsLib) - FastCell, FastImage, FastGridCell
* [Xamarin-Forms-Labs](https://github.com/XLabs/Xamarin-Forms-Labs) - Powerful and cross platform set of controls and helpers
* [xamarin-forms-xna](https://github.com/jvlppm/xamarin-forms-xna) - Monogame wrapper for Xamarin.Forms

## XPlat APIs
Most of them support Android and iOS, some do Windows Phone 8

* [barcodes](https://github.com/aritchie/barcodes) - A cross platform barcode scanning and creating library built on top of ZXing.Net.Mobile.
* [biometrics](https://github.com/aritchie/biometrics) - (Fingerprint Sensor) For Xamarin (iOS & Android)
* [Calendars](https://github.com/TheAlmightyBob/Calendars) - Calendar API plugin for Xamarin and Windows Phone, Supports basic CRUD operations with calendars and events.
* [Device Motion](https://github.com/rdelrosario/xamarin-plugins/tree/master/DeviceMotion) - Simple cross platform plugin to read motion vectors value for device motion sensors such as: Accelerometer, Gyroscope, Magnetometer, Compass.
* [HybridKit](https://github.com/chkn/HybridKit) - Simple C# – JavaScript bridge for building hybrid iOS and Android apps.
* [io](https://github.com/aritchie/io) - Access system folders and files using a familiar api
mobile-optimized libs (NSURLSession / OkHttp)
* [Lager](https://github.com/ghuntley/Lager) - Cross-platform settings storage that uses Akavache as a storage backend
* [Lamp](https://github.com/kphillpotts/Xamarin.Plugins/tree/master/Lamp) - Simple way of controlling the lamp/LED on the back of your phone from Xamarin and Xamarin.Forms projects
* [ManageSleep](https://github.com/molinch/Xam.Plugins.ManageSleep) - Manage auto sleep / auto lock in all platforms. This is useful when dealing with long running processes
* [Messaging](https://github.com/cjlotz/Xamarin.Plugins) - The Messaging plugin makes it possible to make a phone call, send a sms or send an e-mail using the default messaging applications on the different mobile platforms.
* [ModernHttpClient](https://github.com/paulcbetts/ModernHttpClient) - Accelerates HTTP requests by using 
* [notifications](https://github.com/aritchie/notifications) - Notifications plugin for Xamarin and Windows
* [Reachability](https://github.com/has-taiar/Reachability.Net) - Online/offline connected check
* [Settings](https://github.com/aritchie/settings) - Cross platform settings plugin for Xamarin and Windows
* [Telephony](https://github.com/ghuntley/telephony) - Email, sms, voice and video call functionality
* [userdialogs](https://github.com/aritchie/userdialogs) - Standard user dialogs from a shared/portable library.
* [Version](https://github.com/mtrinder/Xamarin.Plugins/tree/master/Version) - Get app version from bundle
* [Xamarin.Badge](https://github.com/B1naryStudio/Xamarin.Badge) - Simple cross platform plugin to work with application badge
* [Xamarin.LocalNotifications](https://github.com/B1naryStudio/Xamarin.LocalNotifications) - Simple cross platform plugin to work with mobile local notifications
* [Xamarin.Mobile](https://github.com/xamarin/Xamarin.Mobile) - Reading the user's address book and using the camera
* [xamarin-plugins](https://github.com/domaven/xamarin-plugins) - Device Motion, Geofencing, Push Notifications (Beta)
* [Xamarin.Plugins](https://github.com/jamesmontemagno/Xamarin.Plugins) - Battery Status, Connectivity, Contacts, Device Information, Extended Maps, Geolocator, Media, Settings, Text To Speech, Vibrate, Circle Image for Xamarin.Forms


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Benoit Jadinon has waived all copyright and related or neighboring rights to this work.
