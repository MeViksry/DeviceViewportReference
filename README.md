<div align="center">

# Device Viewport Reference

**A clean, developer-friendly reference of logical resolution, pixel density and safe area insets for 82 phones, tablets, laptops and consoles.**

<br/>

[![License](https://img.shields.io/github/license/MeViksry/device-viewport-reference?style=for-the-badge&color=2563eb)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/MeViksry/device-viewport-reference?style=for-the-badge&color=10b981)](https://github.com/MeViksry/device-viewport-reference/commits)
[![Stars](https://img.shields.io/github/stars/MeViksry/device-viewport-reference?style=for-the-badge&logo=github&color=f59e0b)](https://github.com/MeViksry/device-viewport-reference/stargazers)
[![Forks](https://img.shields.io/github/forks/MeViksry/device-viewport-reference?style=for-the-badge&logo=github&color=8b5cf6)](https://github.com/MeViksry/device-viewport-reference/network/members)
[![Issues](https://img.shields.io/github/issues/MeViksry/device-viewport-reference?style=for-the-badge&color=ef4444)](https://github.com/MeViksry/device-viewport-reference/issues)

![Devices](https://img.shields.io/badge/devices-82-2563eb?style=for-the-badge)
![Platforms](https://img.shields.io/badge/platforms-iOS%20%7C%20Android%20%7C%20macOS%20%7C%20Windows%20%7C%20Console-0ea5e9?style=for-the-badge)
![Format](https://img.shields.io/badge/format-Markdown-083fa1?style=for-the-badge&logo=markdown&logoColor=white)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge)](#contributing)

<br/>

[![Overview](https://img.shields.io/badge/-Overview-1f2937?style=flat-square)](#overview)
[![Concepts](https://img.shields.io/badge/-Key%20Concepts-1f2937?style=flat-square)](#key-concepts)
[![Coverage](https://img.shields.io/badge/-Coverage-1f2937?style=flat-square)](#coverage)
[![Device Data](https://img.shields.io/badge/-Device%20Data-1f2937?style=flat-square)](#device-data)
[![Usage](https://img.shields.io/badge/-Usage-1f2937?style=flat-square)](#usage)
[![Contributing](https://img.shields.io/badge/-Contributing-1f2937?style=flat-square)](#contributing)
[![License](https://img.shields.io/badge/-License-1f2937?style=flat-square)](#license)

</div>

<br/>

## Overview

![Section](https://img.shields.io/badge/section-overview-2563eb?style=flat-square)

Designing or testing a responsive layout means knowing the real numbers behind each screen: how many logical points wide it is, how dense the pixels are, and how much room the notch, Dynamic Island, rounded corners and home indicator take away.

This repository collects those numbers in one place, so you can:

- Pick accurate frame sizes in Figma, Sketch or Penpot.
- Set the right breakpoints and viewport values for web and hybrid apps.
- Respect safe area insets in native iOS, Android, Flutter and React Native code.
- Cross-check emulator and simulator profiles against real hardware.

<br/>

## Key Concepts

![Section](https://img.shields.io/badge/section-concepts-8b5cf6?style=flat-square)

| Term | Meaning |
| :--- | :--- |
| **Logical size (pt)** | Screen size in points, which map to CSS pixels on the web and dp on Android. This is the number your layout works with. |
| **Resolution (px)** | Physical pixel grid of the panel. |
| **Scale** | Ratio between physical pixels and logical points. |
| **PPI** | Pixel density, in pixels per inch. |
| **Safe area (pt)** | Area of the screen not covered by cutouts, rounded corners, system bars or the home indicator. |
| **Insets** | Distance, in points, reserved on each edge, listed as Top / Bottom / Left / Right. |

The relationship between the first three values is simple:

```text
physical pixels = logical points x scale
safe area       = logical size - insets
```

<br/>

## Coverage

![Section](https://img.shields.io/badge/section-coverage-10b981?style=flat-square)

| Category | Devices | Brands |
| :--- | :---: | :--- |
| Apple iPhone | 20 | Apple |
| Samsung Galaxy | 14 | Samsung |
| Google Pixel | 4 | Google |
| Xiaomi, POCO and Redmi | 11 | Xiaomi |
| Other Android phones | 10 | OnePlus, Motorola, Infinix, Huawei |
| Tablets | 10 | Apple, Samsung, Xiaomi, Redmi, OnePlus |
| Laptops | 9 | Apple, Microsoft, Dell, Huawei |
| TV and consoles | 4 | Sony, Nintendo, Valve |
| **Total** | **82** | |

<br/>

## Device Data

![Section](https://img.shields.io/badge/section-device%20data-f59e0b?style=flat-square)

All values are for the default portrait orientation on phones and tablets. The **Insets** column reads Top / Bottom / Left / Right.

<br/>

### Apple iPhone

![Apple](https://img.shields.io/badge/devices-20-000000?style=flat-square&logo=apple&logoColor=white)

| Device | Logical (pt) | Resolution (px) | Scale | PPI | Safe Area (pt) | Insets (T / B / L / R) |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| iPhone 18 Pro Max | 440 × 956 | 1320 × 2868 | 3× | 460 | 440 × 860 | 62 / 34 / 0 / 0 |
| iPhone 18 Pro | 402 × 874 | 1206 × 2622 | 3× | 460 | 402 × 778 | 62 / 34 / 0 / 0 |
| iPhone Duo | 466 × 678 | 1398 × 2034 | 3× | 460 | 382 × 644 | 0 / 34 / 0 / 84 |
| iPhone 17 | 402 × 874 | 1206 × 2622 | 3× | 460 | 402 × 778 | 62 / 34 / 0 / 0 |
| iPhone 17 Pro | 402 × 874 | 1206 × 2622 | 3× | 460 | 402 × 778 | 62 / 34 / 0 / 0 |
| iPhone 17 Pro Max | 440 × 956 | 1320 × 2868 | 3× | 460 | 440 × 860 | 62 / 34 / 0 / 0 |
| iPhone Air | 420 × 912 | 1260 × 2736 | 3× | 460 | 420 × 810 | 68 / 34 / 0 / 0 |
| iPhone 17e | 390 × 844 | 1170 × 2532 | 3× | 460 | 390 × 763 | 47 / 34 / 0 / 0 |
| iPhone 16 | 393 × 852 | 1179 × 2556 | 3× | 460 | 393 × 759 | 59 / 34 / 0 / 0 |
| iPhone 16 Plus | 430 × 932 | 1290 × 2796 | 3× | 460 | 430 × 839 | 59 / 34 / 0 / 0 |
| iPhone 16 Pro | 402 × 874 | 1206 × 2622 | 3× | 460 | 402 × 778 | 62 / 34 / 0 / 0 |
| iPhone 16 Pro Max | 440 × 956 | 1320 × 2868 | 3× | 460 | 440 × 860 | 62 / 34 / 0 / 0 |
| iPhone 15 | 393 × 852 | 1179 × 2556 | 3× | 460 | 393 × 759 | 59 / 34 / 0 / 0 |
| iPhone 14 and 15 Pro | 393 × 852 | 1179 × 2556 | 3× | 460 | 393 × 759 | 59 / 34 / 0 / 0 |
| iPhone 13 and 14 | 390 × 844 | 1170 × 2532 | 3× | 460 | 390 × 763 | 47 / 34 / 0 / 0 |
| iPhone 13 Mini | 375 × 812 | 1080 × 2340 | 2.9× | 476 | 375 × 728 | 50 / 34 / 0 / 0 |
| iPhone SE 2022 | 375 × 667 | 750 × 1334 | 2× | 326 | 375 × 647 | 20 / 0 / 0 / 0 |
| iPhone X | 375 × 812 | 1125 × 2436 | 3× | 458 | 375 × 734 | 44 / 34 / 0 / 0 |
| iPhone 6 and 6s | 375 × 667 | 750 × 1334 | 2× | 326 | 375 × 647 | 20 / 0 / 0 / 0 |
| iPhone 5 and 5s | 320 × 568 | 640 × 1136 | 2× | 326 | 320 × 548 | 20 / 0 / 0 / 0 |

<br/>

### Samsung Galaxy

![Samsung](https://img.shields.io/badge/devices-14-1428A0?style=flat-square&logo=samsung&logoColor=white)

| Device | Logical (pt) | Resolution (px) | Scale | PPI | Safe Area (pt) | Insets (T / B / L / R) |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| Galaxy S26 | 360 × 780 | 1080 × 2340 | 3× | 480 | 360 × 728 | 37 / 15 / 0 / 0 |
| Galaxy S26+ | 384 × 832 | 1440 × 3120 | 3.8× | 450 | 384 × 780 | 37 / 15 / 0 / 0 |
| Galaxy S26 Ultra | 384 × 832 | 1440 × 3120 | 3.8× | 450 | 384 × 780 | 37 / 15 / 0 / 0 |
| Galaxy Z Flip8 | 399 × 441 | 948 × 1048 | 2.4× | 380 | 399 × 353 | 0 / 88 / 0 / 0 |
| Galaxy Z Fold8 | 475 × 751 | 1248 × 1972 | 2.6× | 420 | 475 × 694 | 42 / 15 / 0 / 0 |
| Galaxy Z Fold8 Ultra | 360 × 840 | 1080 × 2520 | 3× | 480 | 360 × 787 | 38 / 15 / 0 / 0 |
| Galaxy Z Flip6 | 360 × 880 | 1080 × 2640 | 3× | 480 | 360 × 834 | 31 / 15 / 0 / 0 |
| Galaxy Z Fold6 | 707 × 823 | 1856 × 2160 | 2.6× | 420 | 707 × 772 | 36 / 15 / 0 / 0 |
| Galaxy S25 | 360 × 780 | 1080 × 2340 | 3× | 480 | 360 × 731 | 34 / 15 / 0 / 0 |
| Galaxy S25+ | 384 × 832 | 1440 × 3120 | 3.8× | 450 | 384 × 783 | 34 / 15 / 0 / 0 |
| Galaxy S25 Ultra | 384 × 832 | 1440 × 3120 | 3.8× | 450 | 384 × 783 | 34 / 15 / 0 / 0 |
| Galaxy S22 | 360 × 780 | 1080 × 2340 | 3× | 422 | 360 × 738 | 27 / 15 / 0 / 0 |
| Galaxy A56 | 360 × 780 | 1080 × 2340 | 3× | 385 | 360 × 728 | 36 / 16 / 0 / 0 |
| Galaxy A24 | 360 × 780 | 1080 × 2340 | 3× | 396 | 360 × 738 | 27 / 15 / 0 / 0 |

<br/>

### Google Pixel

![Google](https://img.shields.io/badge/devices-4-4285F4?style=flat-square&logo=google&logoColor=white)

| Device | Logical (pt) | Resolution (px) | Scale | PPI | Safe Area (pt) | Insets (T / B / L / R) |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| Pixel 9 | 411 × 923 | 1080 × 2424 | 2.6× | 420 | 411 × 845 | 54 / 24 / 0 / 0 |
| Pixel 9 Pro | 427 × 952 | 1280 × 2856 | 3× | 495 | 427 × 876 | 52 / 24 / 0 / 0 |
| Pixel 9 Pro XL | 448 × 997 | 1344 × 2992 | 3× | 486 | 448 × 920 | 53 / 24 / 0 / 0 |
| Pixel 8 | 360 × 800 | 1080 × 2400 | 3× | 428 | 360 × 726 | 50 / 24 / 0 / 0 |

<br/>

### Xiaomi, POCO and Redmi

![Xiaomi](https://img.shields.io/badge/devices-11-FF6900?style=flat-square&logo=xiaomi&logoColor=white)

| Device | Logical (pt) | Resolution (px) | Scale | PPI | Safe Area (pt) | Insets (T / B / L / R) |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| Xiaomi 17 | 407 × 885 | 1220 × 2656 | 3× | 460 | 407 × 807 | 54 / 24 / 0 / 0 |
| Xiaomi 17 Pro | 407 × 885 | 1220 × 2656 | 3× | 464 | 407 × 807 | 54 / 24 / 0 / 0 |
| Xiaomi 17 Pro Max | 400 × 869 | 1200 × 2608 | 3× | 416 | 400 × 791 | 54 / 24 / 0 / 0 |
| Xiaomi 17 Ultra | 400 × 869 | 1200 × 2608 | 3× | 416 | 400 × 791 | 54 / 24 / 0 / 0 |
| POCO X8 Pro | 423 × 919 | 1268 × 2756 | 3× | 460 | 423 × 841 | 54 / 24 / 0 / 0 |
| POCO X7 Pro | 407 × 904 | 1220 × 2712 | 3× | 446 | 407 × 852 | 36 / 16 / 0 / 0 |
| POCO X7 | 407 × 904 | 1220 × 2712 | 3× | 446 | 407 × 836 | 52 / 16 / 0 / 0 |
| POCO X3 | 360 × 800 | 1080 × 2400 | 3× | 395 | 360 × 744 | 40 / 16 / 0 / 0 |
| Redmi Note 15 Pro | 427 × 924 | 1280 × 2772 | 3× | 447 | 427 × 860 | 48 / 16 / 0 / 0 |
| Redmi Note 15 | 360 × 797 | 1080 × 2392 | 3× | 388 | 360 × 741 | 40 / 16 / 0 / 0 |
| Redmi 10C | 360 × 825 | 720 × 1650 | 2× | 268 | 360 × 769 | 40 / 16 / 0 / 0 |

<br/>

### Other Android Phones

![OnePlus](https://img.shields.io/badge/OnePlus-3-F5010C?style=flat-square&logo=oneplus&logoColor=white)
![Motorola](https://img.shields.io/badge/Motorola-3-5C92FA?style=flat-square&logo=motorola&logoColor=white)
![Infinix](https://img.shields.io/badge/Infinix-2-0f766e?style=flat-square)
![Huawei](https://img.shields.io/badge/Huawei-2-FF0000?style=flat-square&logo=huawei&logoColor=white)

| Device | Logical (pt) | Resolution (px) | Scale | PPI | Safe Area (pt) | Insets (T / B / L / R) |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| OnePlus 15 | 424 × 924 | 1272 × 2772 | 3× | 450 | 424 × 860 | 48 / 16 / 0 / 0 |
| OnePlus 13 | 412 × 905 | 1440 × 3168 | 3.5× | 510 | 412 × 845 | 44 / 16 / 0 / 0 |
| OnePlus Nord CE5 | 360 × 797 | 1080 × 2392 | 3× | 387 | 360 × 733 | 48 / 16 / 0 / 0 |
| Motorola Edge 60 Fusion | 407 × 904 | 1220 × 2712 | 3× | 446 | 407 × 840 | 48 / 16 / 0 / 0 |
| Motorola G22 | 360 × 800 | 720 × 1600 | 2× | 268 | 360 × 742 | 42 / 16 / 0 / 0 |
| Motorola G20 | 360 × 800 | 720 × 1600 | 2× | 269 | 360 × 752 | 32 / 16 / 0 / 0 |
| Infinix Note 60 Pro | 403 × 881 | 1208 × 2644 | 3× | 429 | 403 × 817 | 48 / 16 / 0 / 0 |
| Infinix Hot 50 Pro | 360 × 812 | 1080 × 2436 | 3× | 393 | 360 × 758 | 38 / 16 / 0 / 0 |
| Huawei Mate X6 | 1120 × 1220 | 2240 × 2440 | 2× | 418 | 1120 × 1126 | 70 / 24 / 0 / 0 |
| Huawei Mate XT Ultimate | 1592 × 1116 | 3184 × 2232 | 2× | 381 | 1592 × 1040 | 52 / 24 / 0 / 0 |

<br/>

### Tablets

![Tablets](https://img.shields.io/badge/devices-10-6366f1?style=flat-square&logo=ipad&logoColor=white)

| Device | Logical (pt) | Resolution (px) | Scale | PPI | Safe Area (pt) | Insets (T / B / L / R) |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| iPad Pro 12.9 | 1024 × 1366 | 2048 × 2732 | 2× | 264 | 1024 × 1309 | 32 / 25 / 0 / 0 |
| iPad Pro 11 | 834 × 1194 | 1668 × 2388 | 2× | 264 | 834 × 1137 | 32 / 25 / 0 / 0 |
| iPad Mini 6 | 744 × 1133 | 1488 × 2266 | 2× | 326 | 744 × 1081 | 32 / 20 / 0 / 0 |
| iPad Mini 5 | 768 × 1024 | 1536 × 2048 | 2× | 326 | 768 × 992 | 32 / 0 / 0 / 0 |
| iPad Air | 820 × 1180 | 1640 × 2360 | 2× | 264 | 820 × 1128 | 32 / 20 / 0 / 0 |
| iPad 10.2 (9th gen) | 810 × 1080 | 1620 × 2160 | 2× | 264 | 810 × 1048 | 32 / 0 / 0 / 0 |
| Samsung Galaxy Tab S10 | 876 × 1400 | 1752 × 2800 | 2× | 266 | 876 × 1356 | 24 / 20 / 0 / 0 |
| Xiaomi Pad 8 | 854 × 1280 | 2136 × 3200 | 2.5× | 344 | 854 × 1232 | 32 / 16 / 0 / 0 |
| Redmi Pad 2 | 800 × 1280 | 1600 × 2560 | 2× | 274 | 800 × 1232 | 32 / 16 / 0 / 0 |
| OnePlus Pad Go 2 | 990 × 1400 | 1980 × 2800 | 2× | 283 | 990 × 1348 | 36 / 16 / 0 / 0 |

<br/>

### Laptops

![Laptops](https://img.shields.io/badge/devices-9-0ea5e9?style=flat-square&logo=apple&logoColor=white)
![Dell](https://img.shields.io/badge/Dell-1-007DB8?style=flat-square&logo=dell&logoColor=white)

Laptop displays have no cutout or system bar reserved by the OS, so the safe area equals the full logical size and all insets are `0`.

| Device | Logical (pt) | Resolution (px) | Scale | PPI |
| :--- | :---: | :---: | :---: | :---: |
| MacBook Air 13" M5 | 1280 × 832 | 2560 × 1664 | 2× | 224 |
| MacBook Pro 14" M5 | 1512 × 982 | 3024 × 1964 | 2× | 254 |
| MacBook Pro 16" M5 (2025) | 1728 × 1117 | 3456 × 2234 | 2× | 254 |
| MacBook Neo | 1204 × 753 | 2408 × 1506 | 2× | 219 |
| MacBook Air 13" M1 (2020) | 1440 × 900 | 2560 × 1600 | 1.8× | 227 |
| MacBook Pro 13" M1 (2020) | 1680 × 1050 | 2560 × 1600 | 1.5× | 227 |
| Microsoft Surface Go 12.4" | 1536 × 1024 | 1536 × 1024 | 1× | 148 |
| Dell Latitude 3450 14" | 1920 × 1080 | 1920 × 1080 | 1× | 157 |
| Huawei MateBook D 14 (2024) | 1280 × 800 | 1920 × 1200 | 1.5× | 161 |

<br/>

### TV and Consoles

![Sony](https://img.shields.io/badge/Sony-1-000000?style=flat-square&logo=sony&logoColor=white)
![Nintendo](https://img.shields.io/badge/Nintendo-2-E60012?style=flat-square&logo=nintendoswitch&logoColor=white)
![Steam](https://img.shields.io/badge/Valve-1-171a21?style=flat-square&logo=steam&logoColor=white)

Insets are `0` on every device in this group.

| Device | Logical (pt) | Resolution (px) | Scale | PPI |
| :--- | :---: | :---: | :---: | :---: |
| Sony 4K TV 55" | 1920 × 1080 | 3840 × 2160 | 2× | 40 |
| Nintendo Switch 2 | 1920 × 1080 | 1920 × 1080 | 1× | 279 |
| Nintendo Switch OLED | 1280 × 720 | 1280 × 720 | 1× | 210 |
| Steam Deck OLED | 1280 × 800 | 1280 × 800 | 1× | 204 |

<br/>

## Usage

![Section](https://img.shields.io/badge/section-usage-ec4899?style=flat-square)

![Web](https://img.shields.io/badge/Web-CSS-1572B6?style=for-the-badge&logo=css&logoColor=white)
![Swift](https://img.shields.io/badge/iOS-Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/Android-Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Figma](https://img.shields.io/badge/Design-Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

**Web.** Enable edge to edge rendering, then pad with the environment variables so content stays clear of cutouts:

```html
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
```

```css
.app-header { padding-top: env(safe-area-inset-top, 0px); }
.app-footer { padding-bottom: env(safe-area-inset-bottom, 0px); }
.app-body   {
  padding-left:  env(safe-area-inset-left, 0px);
  padding-right: env(safe-area-inset-right, 0px);
}
```

**iOS (SwiftUI).** Read the insets from a geometry proxy:

```swift
GeometryReader { proxy in
    let insets = proxy.safeAreaInsets
    Text("Top inset: \(insets.top) pt")
}
```

**Android (Jetpack Compose).** Keep content out of system bars and cutouts:

```kotlin
Scaffold(
    modifier = Modifier.safeDrawingPadding()
) { padding ->
    Content(Modifier.padding(padding))
}
```

**Design tools.** Create a frame using the **Logical** size, then draw a safe area guide using the **Insets** columns.

<br/>

## Notes

![Section](https://img.shields.io/badge/section-notes-64748b?style=flat-square)

- Phone and tablet values describe portrait orientation. In landscape, the insets rotate with the device.
- Safe area insets can change with system settings such as gesture navigation, three button navigation and display size.
- Foldables report different values folded and unfolded. Each entry lists the profile shown in the table above.
- Logical size is what CSS media queries and layout engines see, not the physical panel resolution.

<br/>

## Contributing

![Section](https://img.shields.io/badge/section-contributing-22c55e?style=flat-square)

Missing a device or spotted a wrong value? Contributions are welcome.

1. Fork this repository.
2. Add a row to the matching table, keeping the column order and the `W × H` format.
3. Check that `physical px = logical pt × scale` and `safe area = logical size - insets` both hold.
4. Open a pull request and name the device and the source of the numbers.

<br/>

## License

![Section](https://img.shields.io/badge/section-license-f97316?style=flat-square)

Released under the [MIT License](LICENSE).

<br/>

<div align="center">

[![Made by MeViksry](https://img.shields.io/badge/made%20by-MeViksry-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MeViksry)
[![Followers](https://img.shields.io/github/followers/MeViksry?style=for-the-badge&logo=github&label=followers&color=2563eb)](https://github.com/MeViksry?tab=followers)

If this reference saved you time, consider leaving a star on the repository.

[![Star this repo](https://img.shields.io/github/stars/MeViksry/device-viewport-reference?style=social)](https://github.com/MeViksry/device-viewport-reference)

</div>
