# WORK IN PROGRESS

This is a sample page of the potential next documentation. It is not complete and requires a lot of work
from everyone who want to help. Read [the guideline](NEXT_DOC_GUIDELINE.md) for more information !

# React Native Router [![Join the chat at https://gitter.im/aksonov/react-native-router-flux](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/aksonov/react-native-router-flux?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Codacy Badge](https://api.codacy.com/project/badge/grade/c6d869e2367a4fb491efc9de228c5ac6)](https://www.codacy.com/app/aksonov-github/react-native-router-flux) [![npm version](https://badge.fury.io/js/react-native-router-flux.svg)](http://badge.fury.io/js/react-native-router-flux) [![CircleCI](https://circleci.com/gh/aksonov/react-native-router-flux.svg?style=svg)](https://circleci.com/gh/aksonov/react-native-router-flux)

[![NPM](https://nodei.co/npm/react-native-router-flux.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/react-native-router-flux/)
Router for React Native based on new React Native Navigation API.
It allows you to :
- Group your scenes in a central place
- Switch to a scene with a simple and beautiful syntax
- Pass props without handling any context

## Features

- **Manage your scenes** : wrap your scenes inside the Router and you're ready to go ! Switch from a scene to another
using a simple directive, available everywhere, at any moment.
- **Portable** : no matter you are on Android or IOS. It will work just as fine !
- **Highly Customizable Navigation Bar** : give it any React Component and it will
do the trick ! Manage its visibility as your wish, RNRF will do the rest.
- **Tab Bar Support** : you can switch from a tab to another easily ! Using
[react-native-tabs](https://github.com/aksonov/react-native-tabs) your scenes will be ready in a second.
- **Nested Navigators** : *[completed and appealing description required]*
- **Custom Scene Renderers** : *[completed and appealing description required]*
- **Dynamic Routing** : render a scene depending on your application's internal state.
- **Bring your own reducer** : bind your state's manager to react-native-router-flux and it will dispatch
his actions to your reducer, so you can have your own copy of the router's state !
- **Reset History Stack** : go back to your initial scene within a single action.
- **More Powerful State Control** : *[completed and appealing description required]*

## Who uses it ?
+ Buddify ([iOS](https://itunes.apple.com/app/id1149011372), [Android](https://play.google.com/store/apps/details?id=com.buddify)) - helps travelers discover fun things to do locally.
+ GuavaPass.com ([iOS](https://itunes.apple.com/en/app/guavapass-one-pass-fitness/id1050491044?l=en&mt=8), Android) - offers convenient access to top classes at boutique fitness studios across Asia.
+ Epic Fail Videos ([iOS](https://itunes.apple.com/us/app/epic-fail-videos-best-fail/id1115219339), [Android](https://play.google.com/store/apps/details?id=com.hazuu.epicfailvideos)) - The best Fail Videos Collection, never miss a laugh with your friends!
+ Junk Free ([iOS](https://itunes.apple.com/us/app/junk-free-by-junk-free-june/id1109940159)) - A simple way to find, share, and save recipes, workouts, and other healthy content with your friends, family and workmates.
+ chozun ([iOS](https://itunes.apple.com/au/app/chozun/id1097365167), [Android](https://play.google.com/store/apps/details?id=com.chozun)) - Your travel companion, matching your lifestyle on the go!
+ Snappatizer ([iOS](https://itunes.apple.com/us/app/snappatizer-find-rank-best/id1147400405?mt=8)) - Find and rank the best food around you.
+ Look Lock ([GitHub](https://github.com/7kfpun/PhotosReactNative), [iOS](https://itunes.apple.com/us/app/look-lock-show-photos-without/id1151863742), [Android](https://play.google.com/store/apps/details?id=com.kfpun.photos)) - Show photos without worries.
+ BusDue, ([iOS](https://itunes.apple.com/gb/app/busdue/id1185327843?mt=8), [Android](https://play.google.com/store/apps/details?id=com.busdue)) - London bus arrival time app

## Installation

It's as easy as any package. Just do `npm install --save react-native-router-flux`.

## Getting Started

- Basics
  - Scene
  - Actions
  - Navigation Bar
- Advanced
  - Tabs
  - Drawer
  - Animation
- Third Party Integration
  - redux
  - react-native-menu
