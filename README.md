# StableDiffusion_ComfyUI

## Overview
StableDiffusion_ComfyUI is a project that integrates the Stable Diffusion model (using the v1-4 .ckpt checkpoint) with ComfyUI, providing a user-friendly interface for generating images from text prompts.

## Features
- Utilizes the original v1-4 Stable Diffusion .ckpt model.
- Easy-to-use interface powered by ComfyUI.
- Customizable generation settings.

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Akhil200324/-StableDiffusion_ComfyUI.git
   cd -StableDiffusion_ComfyUI
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
   (Or list the dependencies here if requirements.txt is not present.)

3. **Download the Stable Diffusion v1-4 .ckpt model**
   - Place the model file in the appropriate directory (specify the path here).

## Usage

1. **Start the UI**
   ```bash
   python app.py  # or the relevant script to launch ComfyUI
   ```

2. **Interact**
   - Open your browser and go to `http://localhost:XXXX` (specify the correct port).
   - Input your text prompts and adjust settings as needed.
   - Generate images.

## Example

```
Prompt: "A futuristic cityscape at sunset"
[Insert generated image example here]
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE) (or specify your license).

## Acknowledgments

- [Stable Diffusion](https://github.com/CompVis/stable-diffusion)
- [ComfyUI](https://github.com/comfyanonymous/ComfyUI)
