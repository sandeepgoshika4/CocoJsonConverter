# CocoJsonConverter
This Code is used to convert Mask into Coco data format with semantic segmentation
This code takes binary mask as input and converts them into COCO json format with specified label.

# Label ids of the dataset
category_ids = {
    "background": 0,
    "damage": 1
}

# Define which colors match which categories in the images
category_colors = {
    "(0, 0, 0)": 0,  # background
    "(255, 255, 255)": 1  # damage
}

Specific labeling is refferd to specific colour category
