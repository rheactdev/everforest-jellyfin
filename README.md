<h3 align="center">
    Everforest for <a href="https://jellyfin.org">Jellyfin</a>
</h3>

<p align="center">
    Everforest is a green-based color scheme, it is designed to be warm and soft in order to protect the eyes of developers and users alike.
</p>

<p align="center">
    <img src="/assets/preview.webp"/>
</p>

## Usage

1. Open settings, navigate to Display and paste the following CSS into the section called "Custom CSS code":
    ```css
    @import url('https://cdn.jsdelivr.net/gh/rheactdev/everforest-jellyfin/themes/theme.css');
    @import url('https://cdn.jsdelivr.net/gh/rheactdev/everforest-jellyfin/themes/everforest.css');
    ```
2. Press save and you're done!

## Customization

The accent color can be overridden by adding the following **after** the imports:
```css
:root {
    --main-color: var(--aqua);
}
```

### Creating your own theme

All colors can be easily changed by overriding [these CSS variables](./themes/everforest.css).

## 💝 Thanks to

- [Catppuccin](https://github.com/catppuccin/jellyfin) (Original theme structure)
- [sainnhe](https://github.com/sainnhe/everforest) (Everforest creator)
- [Dachi](https://github.com/dachinat) (DaisyUI Everforest colors)

&nbsp;

<p align="center">
    Licensed under the MIT License
</p>

