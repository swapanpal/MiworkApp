# MiworkApp
We want to create an app for someone to learn word in miword language. We have a collection of words that fall into 4 categories Numbers, Colers, Family members and Phrases. We can create image and record sound files for all the words

Miwok App
This app displays lists of vocabulary words for the user to learn the Miwok language. Used in a Udacity course in the Beginning Android Nanodegree.

Work Flow Chart for Miwork App:
1. First design main activity xml file for four Activity name(Number,Family,Colors & Phrases), vertically.
2. Than create another 4 empty activity for Number,Family,Colors & Phrases
3. Than Set  click listener on every View and Create individual new intent to open the view(Number,Family,Colors & Phrases)
4. Than set label at Manifest file to show actual Activity Name in every acrivity action bar(android:label="@string/category_numbers")
5. Than add code at Manifest file for Back button in Action bar,(android:parentActivityName=".MainActivity")


