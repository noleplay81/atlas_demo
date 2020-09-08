# atlas_demo

Atlas Demo that is built to work with [atlas](https://pub.dev/packages/atlas).

## Quick Start

### Usage

```dart
import 'package:flutter/material.dart';
import 'package:atlas/atlas.dart';
import 'package:google_atlas/google_atlas.dart';

void main() {
  AtlasProvider.instance = GoogleAtlas();
  runApp(AtlasDemo('My Atlas Demo', InitialMapData(
    cameraPositions: DemoCameraPosition(
      name: 'Initial Position',
      type: CameraPositionType.Center,
      center: DemoGeoCoordinates(41.875492, -87.645631),
      zoom: 12,
    ),
  ));
}
```
- Please refer to the file 'initial_map_data_sample.dart'

## Maintainers

Project Lead(s):

- [@ksantiya](https://github.com/ksantiya)

Main Maintainer(s):

- [@sunoh5](https://github.com/sunoh5)
- [@noleplay81](https://github.com/noleplay81)
- [@dydkask](https://github.com/dydkask)
