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
6. Need to create custom ArrayAdapter, For that,
    * Need to create a Class to for a blue print of data source (Word)
    * An xml layout for how to show the view (list_item.xml)
    * Create a Class for custom Adapter thats extends ArrayAdapter (WordAdapter)
    * Must override getView method with default constructor in custom adapter class
    * need a xml flie where to show the data(this view will show all 4 activity on setOnContentView)
    * than use the same code for all 4 activity
 7. add all image asset to drawable folder
 8. Modify Word class,WordAdapter and list_item_xml file to show image in every list
   * create new constructor in Word class
   * find, get and set image in wordAdapter class
   * add image visible or gone in for every iteme(because pharases item has no image)
 9. Than visual polist:
      * modify all xml file for acurate view(weight,width, height, padding etc)
      * add code for different background color as per 4 cagegory BG color)
 10. Add audio in Miwok app, To do this:
      * add all audio file in raw folder
      * add audio id at listView as 4th input & modify Word class constructor(add another input in every constructor)
      * add OnItemClickListener to play audio and add MediaPlayer code in 4 activity
      * than add release method in MediaPlayer to release audio when finished play
      * than add onStop method to emidiately stop audio when user clicked home button after release code
      * than add code for AudioFocus
    11. Add play arrow button in list_item.xml file 


