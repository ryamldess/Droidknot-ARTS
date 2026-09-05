# Droidknot-ARTS

AI Rating Transparency System -- Official Repository

ARTS is an accessible, human-centric, consumer-, business- and creator-friendly labeling standard that is broadly compliant with several regulatory frameworks regarding AI transparency labeling around the world:

* EU AI Act Article 50
* California SB942
* NY State Senate Bill 2025-S8420A (Synthetic Performer Law)
* KAIBA (Korean AI Basic Act)

It is free to use and open-source, released under a Creative Commons Zero Universal license.

Download the standard to get acquainted with using ARTS, then use the guide below to creating your first Arts Label and System Information Sheet.

Example labels and System Information Sheets are available under the /Examples folder.

# Getting Started Guide

This guide assumes you have read and understand the ARTS standard.

## Create a label

1. Download the label .SVG template from /Templates, ARTS_Template_2_082626.svg.
2. Open it with your favorite .SVG editor. We used Inkscape; Affinity also works. The ARTS template has every layer unlocked by default, remember to unlock the layers you wish to edit.
3. Edit the text field in the layer labeled 'Rating Designator' to set the Rating Designator for the label.
4. There are 4 layers for the modifiers, one for each modifier. Each layer has 4 sublayers with a different group consisting of the modifier icon and the number representing a modifier score from 0-3. Hide all of these sub-layers except for the one that represents the score of the product you are evaluating.
5. Calculate the CACS from the Rating Designator and the 4 Modifiers. Edit the text field in the layer labeled 'CACS' to set the score.
6. Click the rectangle in the layer labeled 'Card'. In Inkscape, click the 'Fill and Stroke' tab and then the 'Fill' sub-tab. In Affinity, select the 'Color' tab. Set the color based on the equations or pre-calculated values in the standard.
7. Click the rectangle labeled 'Bar' in the 'Visual Scale' layer. Set its height and y-value based on the table in the standard for your CACS value. If you have forked the standard and changed the layout, you will have to use the equations in the standard instead.
8. If you created a QR code for your product, un-hide the sub-layer labeled 'Optional Product QR' in the 'QR' layer, and replace the 'Heaps SIS Link' QR with your own. We provided the QR to Droidknot's product Heaps as an example for scale and placement. Your product's QR code should match these values, as they are optimized for placement on the label and described in the standard.

Cogratulations, your label is complete! Save it and export copies in whichever format you require.

## Create a System Information Sheet.

Now that you have created a label, to be fully ARTS-compliant, it is mandatory to create a System Information Sheet for your product.

1. Download the SIS Affinity template from /Templates, ARTS_SIS_Template_082726.af.
2. Replace the sample ARTS Label by importing your own: In Affinity, delete the existing label, then select File -> Place and browse to the .SVG file for your own label. Use the placement icon to place the label somewhere on the first page. In the new label's transform, set the X and Y positions to 0.25 in. Click the link button next to the Height and Width fields to lock the aspect ratio. Click at the end of the text in the Height field and type '/2' and hit the enter key. This will cut its size in half so that it fits perfectly in place on your System Information Sheet.
3. Edit the template's pre-defined and labeled fields to match your product and its ARTS Label.

# ARTS Explainer Diagram

![ARTS Explainer Diagram](/Assets/ARTS_Explainer_Diagram_Opaque_090426.png "ARTS Explainer Diagram")
