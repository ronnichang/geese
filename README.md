
# Goose Individual Identification Dataset

This dataset contains photographic images and manual polygonal segmentations of 58 individual Canada geese. 
Each goose is associated with a unique numeric ID, such as 02, 03, . . ., 69. 

## Structure
- `images/`: Contains subfolders `02/`, `03/`, ..., `69/`, each with original images.
- `annotations/`: Polygon annotations in JSON format (one file per goose).
- `merged_annotations.json`: A merged COCO-format file.
- `goose_metadata.csv`: Metadata linking each image to its goose ID.

## Data Collection
Images were captured along Emeral Necklace of Brookline and Boston, Massachusetts, during early 2023 to early 2025, using mobile phones, e.g., Google Pixel 4 and Pixel 7. Segmentation was manually annotated using DigitalSreeni Image Annotator.

## License
Open data licenses. 

## Citation
If you use this dataset, please cite:
- Ronni Chang (2025). Goose Individual Identification Dataset. Scientific Data. [DOI after acceptance]

