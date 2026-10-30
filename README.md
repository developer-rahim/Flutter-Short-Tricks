# Flutter-Short-Tricks

A collection of practical Flutter snippets, each solving one real problem.

## Highlights

- **bKash balance animation** — a loading shimmer for balance lookups.
- **Cached images** — avoid re-downloading and flashing the same network image.
- **Date logic** — expiry checks, Bangla date conversion, current date and time.
- **Show more button** — expand long text without a full expansion panel.
- **Bottom navigation variants** and a reusable **drawer** setup.
- **Error handling** patterns and an **API call** example with Provider.

## Tech Stack

| Concern | Choice |
|---|---|
| UI | Flutter, Material |
| State management | `provider` |
| Utilities | `cached_network_image`, `intl` |

## Project Structure

```
lib/
- `Each trick in its own folder — Error Solving, api Call With Provider & model, app version check, bkash balance animation, cached image, cart Page price count, color pick and icon picker website, current date v& time flutter, date expaire or not logic, date time convert in bangla, discount Till or not, drawer`
```

## Getting Started

### Prerequisites

- Flutter `>= 3.16` (Dart `>= 3.2`)

### Run

```bash
git clone https://github.com/developer-rahim/Flutter-Short-Tricks.git
cd Flutter-Short-Tricks
flutter pub get
flutter run
```

### Test

```bash
flutter test
flutter analyze
```

## Notes

This repository is organised as a cookbook rather than an app — open the folder for the trick you need.

## License

Released under the MIT License.
