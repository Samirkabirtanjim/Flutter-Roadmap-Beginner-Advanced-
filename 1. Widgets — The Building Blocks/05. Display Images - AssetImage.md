# Flutter Display Images Widget Example  

This Flutter widgets demonstrates how to **Display Images** using **AssetImage** in **Container**

---

```dart
import 'package:flutter/material.dart';

class AssetsFlutter extends StatelessWidget {
  const AssetsFlutter({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      home: Scaffold(
        appBar: AppBar(
          title: Text('Display Images', style: TextStyle(color: Colors.white)),
          backgroundColor: Colors.teal,
        ),
        body: Container(
          width: double.infinity,
          child: Image(
            image: AssetImage('images/images.png'),
            fit: BoxFit.cover,
          ),
        ),
      ),
    );
  }
}
```

---

## 📸 Screenshot

<p align="center">
  <img src="https://github.com/Samirkabirtanjim/Flutter-Roadmap-Beginner-Advanced-/blob/main/1.%20Widgets%20%E2%80%94%20The%20Building%20Blocks/ScreenShots/Container.png" width="150">
</p>
