---

# Gravitational Lensing Simulation

This script simulates a gravitational lensing effect using the Lenstronomy package. 
Gravitational lensing is a phenomenon predicted by Einstein's theory of General Relativity where light from a distant source 
is bent by the gravitational field of a massive object, such as a galaxy or a cluster of galaxies.

## Dependencies

Make sure you have the following Python libraries installed:
- `numpy`
- `lenstronomy`
- `matplotlib`

You can install them using pip:
```bash
pip install numpy lenstronomy matplotlib
```

## Overview

This script simulates the lensing effect caused by a point mass, using the Lenstronomy package.
It creates a simulated lensed image of a point source (star or quasar) that is gravitationally lensed by a massive object acting as a gravitational lens.

## Simulation Process

1. **Lensing Parameters**:
   - The script defines the mass of the lens and the distance to the source.
   - It converts the lens mass from kilograms to solar masses and the source distance from parsecs to arcseconds.

2. **Lens Model**:
   - The lens model is defined using a point mass.

3. **Source Setup**:
   - A lensed point source is set up at the position where lensing occurs.

4. **PSF and Image Data Setup**:
   - The script sets up a Gaussian PSF and creates a blank image with specified pixel and coordinate details.

5. **Image Model**:
   - Components (image data, PSF, lens model, and point source) are combined to form an image model.

6. **Image Simulation**:
   - A lensed image is simulated based on the lens model and point source parameters.

## Parameters

- **Lens Mass**: Mass of the lensing object in kilograms, converted to solar masses.
- **Source Distance**: Distance to the source in parsecs, converted to angular distance in arcseconds.
- **PSF FWHM**: Full Width at Half Maximum (FWHM) of the Gaussian PSF in arcseconds.
- **Image Size**: Number of pixels in the simulated image.
- **Pixel Coordinates**: RA and DEC coordinates at the position of the pixel edge.
- **Transform Matrix**: Linear translation matrix for converting pixel shifts to angular shifts.

## Running the Code

1. **Clone the repository**:
   ```bash
   git clone https://github.com/the-w00d/Specific-Test-VII.-Expanding-Strong-Gravitational-Lensing-Simulations.git
   cd Specific-Test-VII.-Expanding-Strong-Gravitational-Lensing-Simulations-main
   ```

2. **Run the script**:
   ```bash
   Strong Gravitational Lensing Simulations.ipynb
   ```

3. **View Results**:
   - The script will generate a simulated lensed image and display it using Matplotlib.

## Example Output

The simulated lensed image will demonstrate the gravitational lensing effect on the point source due to the lensing object's mass.

## References

- Lenstronomy documentation: [Lenstronomy GitHub](https://github.com/sibirrer/lenstronomy)
- Gravitational lensing: [Wikipedia - Gravitational lens](https://en.wikipedia.org/wiki/Gravitational_lens)

---

## Author

- **Dawood Khan**
- GitHub: [@the-w00d](https://github.com/the-w00d)
- linkden: [@Dawoodkhan](https://www.linkedin.com/in/thewood11062004/)
---
