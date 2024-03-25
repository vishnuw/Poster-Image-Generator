# Poster-Image-Generator

---

# Poster Design Code

This repository contains code to generate custom poster designs using the **Stable Diffusion** model. You can create eye-catching posters with various themes, color schemes, and design preferences.

## Prerequisites

Make sure you have the following installed:

- Python 3.6 or later
- [PyTorch](https://pytorch.org/) (for Stable Diffusion)
- [PIL (Pillow)](https://pillow.readthedocs.io/en/stable/) (for image handling)
- [ipywidgets](https://ipywidgets.readthedocs.io/en/stable/) (for interactive input)

## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/poster-design.git
   cd poster-design
   ```

2. Install the required packages:

   ```bash
   pip install torch pillow ipywidgets
   ```

3. Run the `poster_design.py` script:

   ```bash
   python poster_design.py
   ```

4. Follow the prompts to input the following details:

   - **Title/Theme**: Specify the main theme or title for your poster.
   - **Color Scheme/Vibe**: Choose the color palette or overall vibe (e.g., vibrant, minimalistic).
   - **Aim/Objective**: Describe the purpose or objective of the poster.
   - **Key Text Elements**: List important text elements (e.g., event details, taglines).
   - **Design Preference**: Indicate your preferred design style (e.g., retro, modern).
   - **Additional Notes**: Any extra instructions or specific requirements.

5. Click the "Generate Poster" button to create your custom design.

## Example

Here's an example prompt:

```
A vibrant poster with a retro design style for a music festival. The title/theme is 'Groove Fest'. The key text elements are: 'Live Bands, Food Trucks, Dance Floor'. Add some funky graphics and neon colors!
```

## Generated Posters

The generated posters will be saved as `poster_design_1.png`, `poster_design_2.png`, etc.

Feel free to experiment with different prompts and create unique posters!

---

Remember to adjust the paths and filenames according to your project structure. Happy designing! 🎨🌟
