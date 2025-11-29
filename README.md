# LPR Project

## Run
1. Install dependencies: `pip install -r requirements.txt`
2. Ensure `model/` contains `binary_128_0.50_ver3.pb` and label file.
3. Place video `test.MOV` in project root.
4. Run: `python lpr_pipeline.py`
Press `q` to stop video windows.

## Notes
- Model expects 128x128 character images normalized to [-0.5,0.5].
- Tweak PlateFinder(minPlateArea, maxPlateArea) for different camera setups.
