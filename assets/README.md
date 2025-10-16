# Assets Folder

This folder contains all the images and assets for the Pixelas Studio website.

## Required Images

Please add the following images to this folder:

### Logo and Branding
- `logo.png` - Main Pixelas Studio logo (recommended size: 64x64px or larger)
- `hero-screenshot.png` - Main hero image showing the software interface (recommended size: 800x600px or larger)

### AI Model Icons
- `nano-banana-icon.png` - Icon for Nano Banana AI model (recommended size: 80x80px)
- `flux-kontext-icon.png` - Icon for Flux Kontext AI model (recommended size: 80x80px)
- `seedream-icon.png` - Icon for Seedream 4 AI model (recommended size: 80x80px)
- `qwen-edit-icon.png` - Icon for Qwen Edit AI model (recommended size: 80x80px)

## Image Guidelines

- **Format**: PNG or SVG preferred for logos and icons, PNG or JPG for screenshots
- **Quality**: High resolution for crisp display on all devices
- **Style**: Consistent with the dark theme and modern aesthetic
- **Transparency**: Use transparent backgrounds for logos and icons when possible

## Fallback Behavior

If any image is missing, the website will automatically show:
- Text fallback for the logo ("Pixelas Studio")
- Placeholder boxes with emoji icons for AI model icons
- A placeholder box with instructions for the hero image

## File Structure
```
assets/
├── README.md (this file)
├── logo.png (your logo)
├── hero-screenshot.png (software screenshot)
├── nano-banana-icon.png (AI model icon)
├── flux-kontext-icon.png (AI model icon)
├── seedream-icon.png (AI model icon)
└── qwen-edit-icon.png (AI model icon)
```

## Notes

- All images are referenced with relative paths from the root directory
- The website is designed to gracefully handle missing images
- Consider optimizing images for web (compression, appropriate sizing) for better performance
