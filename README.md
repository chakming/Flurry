Flurry
======

Latest Flurry SDK

this repository is forked from [AntonPalich/Flurry](https://github.com/AntonPalich/Flurry)


## This shows how to use this repo as a Private Spec Repo

1. Add this repo to your CocoaPods installation

    ```
    $ pod repo add FlurrySDK https://github.com/nafu/Flurry.git
    ```

2. Add this repo's Podspec to your repo

    ```
    $ git clone https://github.com/nafu/Flurry.git FlurrySDK
    $ cd FlurrySDK
    $ pod repo push FlurrySDK FlurrySDK.podspec
    ```
3. Change your Podfile

    Add source like this

    ```
    source 'https://github.com/nafu/Flurry.git'
    ```

    Podfile looks something like this

    ```
    source 'https://github.com/CocoaPods/Specs.git'
	source 'https://github.com/nafu/Flurry.git'
	platform :ios, '8.0'

	target 'YourProject' do
	  pod 'FlurrySDK', '6.0'
	end
    ```

For more information about Private Pods. see [here](http://guides.cocoapods.org/making/private-cocoapods.html)


## Basic Usage

To use 6.0.0 FlurrySDK from cocoapods, add this line in your Pods file:

```
  pod 'FlurrySDK', '6.0'
```


If you also want the FlurryAds SDK, you can define pods to install both subspecs:

```
  pod 'FlurrySDK/FlurrySDK', '6.0'
  pod 'FlurrySDK/FlurryAds', '6.0'
```
