# Android Icons

There is a huge range of Android devices, all having different screen sizes and densities. To make icons look good across all devices in an Android App, you will have to provide icons for different screen densities.

## Screen Densities and Icon Sizes
- **MDPI (1x)**: 48x48px
- **HDPI (1.5x)**: 72x72px
- **XHDPI (2x)**: 96x96px
- **XXHDPI (3x)**: 144x144px
- **XXXHDPI (4x)**: 192x192px

## Icon Format
- **PNG**: The recommended format for Android Icons.

### Adaptive Icons for Android 8.0 and Newer
Adaptive icons let icons appear in various shapes on different devices. You will need two layers: a foreground and a background layer.
- **Foreground Layer**: 108x108px
- **Background Layer**: 72x72px

Example directory structure:
```plaintext
res/
   mipmap-mdpi/
      ic_launcher.png (48x48)
   mipmap-hdpi/
      ic_launcher.png (72x72)
   mipmap-xhdpi/
      ic_launcher.png (96x96)
   mipmap-xxhdpi/
      ic_launcher.png (144x144)
   mipmap-xxxhdpi/
      ic_launcher.png (192x192)
