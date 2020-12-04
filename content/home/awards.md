+++
# A Skills section created with the Featurette widget.
widget = "featurette"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

title = "Honor & Awards"
subtitle = ""

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background image.
   image = "image.jpg"  # Name of image in `static/media/`.
   image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
   image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
   image_position = "center"  # Options include `left`, `center` (default), or `right`.
   image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["140px", "0", "40px", "0"]

# Date format
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format: Jan 2006

# Accomplishments.
#   Add/remove as many `item` blocks below as you like.
#   `title`, `organization` and `date_start` are the required parameters.
#   Leave other parameters empty if not required.
#   You can begin a multiline `description` using YAML's `|-`.
item:
- certificate_url: https://www.coursera.org
  date_end: ""
  date_start: "2018-10-01"
  description: ""
  organization: Coursera
  organization_url: https://www.coursera.org
  title: Neural Networks and Deep Learning
  url: ""
- certificate_url: https://www.edx.org
  date_end: ""
  date_start: "2018-03-01"
  description: Formulated informed blockchain models, hypotheses, and use cases.
  organization: edX
  organization_url: https://www.edx.org
  title: Blockchain Fundamentals
  url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals

+++

# Showcase personal skills or business features.
# 
# Add/remove as many `[[feature]]` blocks below as you like.
# 
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons

# [[feature]]
#  icon = "r-project"
#  icon_pack = "fab"
#  name = "R"
#  description = "90%"
  
# [[feature]]
#  icon = "chart-line"
#  icon_pack = "fas"
#  name = "Statistics"
#  description = "100%"  
  
# [[feature]]
#  icon = "camera-retro"
#  icon_pack = "fas"
#  name = "Photography"
#  description = "10%"

# Uncomment to use emoji icons.
# [[feature]]
#  icon = ":smile:"
#  icon_pack = "emoji"
#  name = "Emojiness"
#  description = "100%"  

# Uncomment to use custom SVG icons.
# Place custom SVG icon in `assets/images/icon-pack/`, creating folders if necessary.
# Reference the SVG icon name (without `.svg` extension) in the `icon` field.
# [[feature]]
#  icon = "your-custom-icon-name"
#  icon_pack = "custom"
#  name = "Surfing"
#  description = "90%"
