
# Goose Individual Identification Dataset

This dataset contains photographic images and manual polygonal segmentations of 70 individual Canada geese (some IDs missing). 
Each goose is associated with a unique numeric ID (01 to 70).

## Structure
- `images/`: Contains subfolders `01/`, `02/`, ..., `70/`, each with original images.
- `annotations/`: Polygon annotations in JSON format (one file per goose).
- `merged_annotations.json`: A merged COCO-format file.
- `goose_metadata.csv`: Metadata linking each image to its goose ID.

## Data Collection
Images were captured in [your location, e.g., Massachusetts wetlands], during [time period, e.g., Spring 2024], using [camera model, e.g., Google Pixel 6 Pro]. Segmentation was manually annotated using [tool name, e.g., DigitalSreeni Image Annotator].

## License
[Insert license type here, e.g., CC BY 4.0]

## Citation
If you use this dataset, please cite:
- [Author(s)] (2025). Goose Individual Identification Dataset. Scientific Data. [DOI after acceptance]

