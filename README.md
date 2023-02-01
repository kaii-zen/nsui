[![License][license badge]][license]

# NSUI
AppKit and UIKit without conditional compilation

There are small differences between otherwise-source-compatible classes in AppKit and UIKit and it drives everyone bananas. I was inspired by [Nick Lockwood](https://gist.github.com/nicklockwood/19569dc738b565c67f4d97302bf48697) to make this into a package. If you happen to know of another package at already does this, please let me know. I'd love to find a way to collaborate.

When it doubt, UIKit wins. This keeps things familar to the most people.

## Integration

Swift Package Manager:

```swift
dependencies: [
    .package(url: "https://github.com/mattmassicotte/nsui")
]
```

## Types

```
NSUITextView
NSUITextStorageEditActions
```

## Contributing and Collaboration

## Suggestions, Contributing, Feedback

I'd love to hear from you! Get in touch via [mastodon](https://mastodon.social/mattiem), an issue, or a pull request.

I prefer collaboration, and would love to find ways to work together if you have a similar project.

I prefer indentation with tabs for improved accessibility.

By participating in this project you agree to abide by the [Contributor Code of Conduct](CODE_OF_CONDUCT.md).

[license]: https://opensource.org/licenses/BSD-3-Clause
[license badge]: https://img.shields.io/github/license/mattmassicotte/nsui
