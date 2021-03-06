# ProfileImageView
A little IBDesignable Swift class for creating round profile image view in, like this:

![man](https://photos-4.dropbox.com/t/2/AABWOaYcJHVtFJ9faHTFVzn31kuDsQqK3f85FCLoTVaGfg/12/47958737/png/1024x768/3/1427144400/0/2/Screenshot%202015-03-23%2019.48.31.png/CNGV7xYgASACIAMoASgC/ZPB48UKgIWOvE2kKSqyS4re583l0dZdvQBvcAKt2xkk)
![girl](https://photos-6.dropbox.com/t/2/AAChRVhxs5qRVQGVhKEfUgv-ylMaWGbby1rY6W8pbHlcVg/12/47958737/png/1024x768/3/1427144400/0/2/Screenshot%202015-03-23%2019.50.05.png/CNGV7xYgASACIAMoASgC/o0Mi1R38zWiVyuXcMnQuHAW_glR4MIjZk26fj43TjjI)

You can customize the border and overlay of the images from Interface Builder:

![parameters](https://photos-5.dropbox.com/t/2/AADOhFj5sOnyGZYwZ4Dzbdp7oZc30slAGE7mC34wBnPPgg/12/47958737/png/1024x768/3/1427144400/0/2/Screenshot%202015-03-23%2019.48.49.png/CNGV7xYgASACIAMoASgC/uVZ5CorJatBmZg-xAKMHaA0A06s61XOapZVez573ntY)

Just include the ProfileImageView.swift class, set this custom class on an UIView, and set it's image from code:

`@IBOutlet weak var profileImageView: ProfileImageView!`

`profileImageView.image = UIImage(named: "dad")`

## Usage

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

## Installation

ProfileImageView is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "ProfileImageView"
```

## Author

David Judik, judik.david@gmail.com

## License

ProfileImageView is available under the MIT license. See the LICENSE file for more info.
