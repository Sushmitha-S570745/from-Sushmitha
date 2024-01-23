# from-Sushmitha
Lab 2
# Sushmitha Vadhireddy
###### Meghana Foods
It's a **multi cuisine restaurant** which serves **Spicy southeren Indian dishes**

---
#### Favourite dishes list
1. Chilly Chicken
2. Chicken Boneless Biryani 
3. Gobi Manchurian
#### Places to visit near restaurant
* Cubbon Park
* Parksquare Mall
* Library

Link to the MyMedia : [MyMedia](MyMedia.md)

---

#### Sadhguru's Inner Engineering 

I often watch Sadhguru's videos in my spare time.If I had to recommend I would suggest them to try listening the below listed videos:

|Title|Reason|Creator|
|---|---|---|
|What is Inner Enginnering|A 7-session online course provides tools and solutions to help manage stress, overcome anxiety and live joyful life|Sadhguru|
|Manifest whatever u want| describes about how to take charge of our destiny by aligning our thought, emotions and energies to manifest what we really want.|Sadhguru|
|How to handle ourselves in hard times|tells about dealing with feelings of loneliness and getting through hard times in life|sadhguru|
|The power of 3:40AM|Sadhguru delves into what makes the time of 3:40 AM or “Brahma Muhurtam” significant, particularly for spiritual seekers, and also explains how one can make the most of it.|sadhguru|

---

#### Favorite Quotes

"I'm selfish, impatient and a little insecure. I make mistakes, I am out of control and at times hard to handle. But if you can't handle me at my worst, then you sure as hell don't deserve me at my best.”
― Marilyn Monroe

"You've gotta dance like there's nobody watching,
Love like you'll never be hurt,
Sing like there's nobody listening,
And live like it's heaven on earth.”
― William W. Purkey

---

#### Code Fencing

This Node.js code-6, given a data object, converts the object to a JSON string and stores it in a file with the specified path.

<https://code.pieces.app/collections/node-js>

```

const fileSystem = require('fs')

const storeData = (data, path) => {
  try {
    fileSystem.writeFileSync(path, JSON.stringify(data))
  } catch (error) {
    console.error(error)
  }
} 

```