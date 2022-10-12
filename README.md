# Mushroom Classification

Problem Statement:

This dataset includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family Mushroom drawn from The Audubon Society Field Guide to North American Mushrooms (1981). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one. The Guide clearly states that there is no simple rule for determining the edibility of a mushroom; no rule like "leaflets three, let it be'' for Poisonous Oak and Ivy.

Breakdown of the Problem Statement:

Supervised machine learning problem.

classification problem

The target value will be class.

Aim of the Notebook:

The objective is to create a model that can predict edibility of the Mushroom based on its features.

About the dataset:

The dataset contains a set of 8,125 records under 23 attributes

|Column Name	|Description|	Values|
|-------------|:-----------|:--------|
|class	|Edible or poisonous|	e = Edible, p = poisonous|
|cap-shape|	The shape of the expanded, upper part of the mushroom	|b= bell, c = conical, x = convex, f = flat, k = knobbed, s = sunken
|cap-surface|	The structure of the upper part of the mushroom	|f = fibrous, g = grooves, y = scaly, s = smooth
|cap-color|	The color of the surface of the upper part of the mushroom	|n = brown, b = buff, c = cinnamon, g = gray, r = green, p = pink, u = purple, e = red, w = white, y = yellow
|bruises|	Indicates of there are bruises on the mushroom	|t = yes, f = no
|odor	|The smell the mushroom omits|	a = almond, l = anise, c = creosote, y = fishy, f=foul, m = musty, n = none, p = pungent, s = spicy
|gill-attachment|	The way the gill is growing on the mushroom|	a= attached, d = descending,f = free, n = notched
|gill-spacing	|The gap of space between each gill|	c = close,w = crowded, d = distant
|gill-size	|The size of the gills|	b = broad, n = narrow
|gill-color|	The color of the gills|	k = black, n = brown, b = buff, h = chocolate, g = gray, r = green, o = orange, p = pink, u = purple, e = red, w = white , y = yellow
|stalk-shape	|The Stalk`s form|	e = enlarging, t = tapering
|stalk-root	|The root of the mushroom	|b = bulbous, c = club, u = cup, e = equal, z = rhizomorphs, r = rooted, ? = missing|
|stalk-surface-above-ring|	The surface of the stalk above the mushrooms ring|	f = fibrous, y = scaly, k = silky, s = smooth|
|stalk-surface-below-ring	|The surface of the stalk below the mushrooms ring	|f = fibrous, y = scaly, k = silky, s = smooth
|stalk-color-above-ring|	The color of the stalk above the mushrooms ring|	n = brown, b = buff, c = cinnamon, g = gray, o = orange, p = pink, e = red, w = white, y = yellow
|stalk-color-below-ring	|The color of the stalk below the mushrooms ring	|n = brown, b = buff, c = cinnamon, g = gray, o = orange, p = pink, e = red, w = white, y = yellow
|veil-type|	The type of the mushroom`s veil|	p = partial, u = universal
|veil-color	|The color of the mushroom`s veil|	n = brown, o = orange, w = white, y = yellow
|ring-number|	The amount fo rings the mushroom has|	n= none, o = one, t = two
|ring-type|	The type of the mushroom`s ring|	c = cobwebby, e = evanescent, f = flaring, l = large ,n = none, p = pendant, s = sheathing, z = zone
|spore-print-color|	The color of the mushromm`s spore|	k = black, n = brown, b = buff, h = chocolate, r = green, o = orange, u = purple, w = white , y = yellow
|population|	The populaotion spread	|a = abundant, c = clustered, n = numerous, s = scattered, v = several, y = solitary
|habitat|	The mushroom`s environment|	g = grasses, l = leaves, m = meadows, p = paths, u = urban, w = waste, d = woods

Used different ML models to predict whether the mushroom is poisonous or edible

