## Installation
pip install -r requirements.txt

## Data Preparation
### Prepare Image you want to evaluate by Atlas
We support the evaluation for a single image or multiple images. You can prepare and store the path of image/image directory. 

## Usage of Atlas
- Single Image Evaluation
python atlas_agent.py --mode evaluate_image --image_path 'your image path'


- Multiple Image Evaluations
python atlas_agent.py --mode evaluate_multiple_images --image_path 'your image directory' --image_output_path 'your target output xlsx'