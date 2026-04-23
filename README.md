<div align="center">
  <h1>
    ✨ Niri GLSL Shader Collection
  </h1>
</div>

This is a collection of GLSL shaders for **window open** and **window close** animations for [niri window manager](https://github.com/niri-wm/niri)

Use the shaders as they are or go through each one and learn to write your own. 

Starting from the very basic fade animations, all the way up to complex burn effects using `Fractional Brownian Motion` noise and much more.

## 🎥 Demos

| Animation Name | Preview | Source Code |
| :--- | :--- | :--- |
| Ribbons | <video src="./DEMOS/ribbons.mp4" width="300" muted autoplay loop></video> | [ribbons](./07_Ribbons/04_rotated.kdl) |
| Burn | <video src="./DEMOS/burn.mp4" width="300" muted autoplay loop></video> | [burn](./10_Advanced/burn.kdl) |
| Honeycomb |<video src="./DEMOS/honeycomb.mp4" width="300" muted autoplay loop></video> | [honeycomb](./10_Advanced/honeycomb.kdl) |

## 🚀 Usage

1. Go to the shader you want to use

2. Copy all contents of the file

3. Paste in animations section inside your niri config generally found at `~/.config/niri/config.kdl`  

  ```kdl
  animations {
    // Uncomment to turn off all animations.
    // off
  
    // Slow down all animations by this factor. Values below 1 speed them up instead.
    // slowdown 2.0
    
    // All code from any file goes here 
    // Avoid multiple entries of same section
  }
  ```
## ✍️ Write your own

1. Go through the learning resources linked at the end.

2. Go through this repo start to end.

3. Understand how shaders work in niri by slightly modifing some working shaders.

4. Search for other's work and use that as reference to write your own shader. 

## 📑 References

### 📄 Niri Documentation

1. [Wiki Entry](https://github.com/niri-wm/niri/wiki/Configuration:-Animations#custom-shader)

2. [Example Shader](https://raw.githubusercontent.com/wiki/niri-wm/niri/examples/open_custom_shader.frag)

### 💡 Inspiration 

1. [This Reddit Post](https://www.reddit.com/r/niri/comments/1s2u6mq/i_found_out_niri_has_glsl_support_for_animations/)

2. [Animation Collection](https://github.com/jgarza9788/niri-animation-collection)

3. [Noctalia Shell wallpaper shader](https://github.com/noctalia-dev/noctalia-shell/blob/d7b68652e79bce5813dc4fea7e51636a5da3e1b7/Shaders/frag/wp_honeycomb.frag)

## 📚 Learning Resources

1. [The Book of Shaders](https://thebookofshaders.com/)

2. [Learn OpenGL Shaders](https://learnopengl.com/Getting-started/Shaders)
