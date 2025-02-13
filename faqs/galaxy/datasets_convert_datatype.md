---
title: Converting the file format
description: Some datasets can be transformed into a different format. Galaxy has some built-in file conversion options depending on the type of data you have.
area: datasets
box_type: tip
layout: faq
contributors: [shiltemann,hexylena,lldelisle]
optional_parameters:
  conversion: The datatype to convert the dataset to
examples:
  Convert to BAM:
    conversion: BAM
---

* Click on the {% icon galaxy-pencil %} **pencil icon** for the dataset to edit its attributes
* In the central panel, click on the {% icon galaxy-gear %} **Convert** tab on the top
* In the upper part {% icon galaxy-gear %} **Convert**, select {% if include.conversion %}`{{ include.conversion }}`{% else %}the appropriate datatype from the list {% endif %}
* Click the **Create dataset** button to start the conversion.
