# Look at all those chickens!
- __Category__: osint
- __Difficulty__: beginner
- __Author__: a_metre
- __Tags__: osint

***

> Dear [user],
> 
> Hmmm, it appears this image was sent last year when one of our brave hackers went out to follow a lead to save some birds from those nasty bugs, but couldn't reach them! We did have it on good word that they were in captivity nearby to the picture that was taken- can you find out the name of the place were these birds were locked up?
>
> The flag format is DUCTF{Captivity_Name} (case insensitive)
> 
> The answer is two words
> 
> Regards,
> a_metre
>
> Attachments #
> [LookAtAllThoseChickens.jpg]()

***

<details>
  <summary> <em>Doshie's Solution</em> </summary>
  Always happy to have an image search quest! We'll start on https://images.google.com/ and click on <em>search by image</em> for a file upload. Under "Visual Matches", a promising result comes from the r/melbourne subreddit:<br>

  <img src="https://github.com/Iozhewa/Bakushin-Meets-DUCTF-2025/blob/main/osint/Look%20at%20all%20those%20chickens!/bin-chicken-island-part-deux-v0-ci2bvyf3khv91.webp" alt="Bin Chicken Island..?"><br>
  <a href="https://www.reddit.com/r/melbourne/comments/yb8e9d/bin_chicken_island_part_deux/">
    <sub>Note this is an archived post.</sub>
  </a>

  But we haven't yet found a captivity name. Running "bin chicken island" on a plain Google search, we can run Google Maps to verify the location -- the blue cone on the left is a direct match to Coburg Lake Reserve Playground.<br>

  <img src="https://github.com/Iozhewa/Bakushin-Meets-DUCTF-2025/blob/main/osint/Look%20at%20all%20those%20chickens!/coburg-lake-reserve-murray-road-coburg.jpg" alt="Image of Lake Playground">

  <br>Based on the webpage results under Bin Chicken Island, here were some candidates for the flag:<br>
  - Coburg_Lake
  - BinChicken_Island
  - Murray_Road
  - Coburg_North
  - Merri_Creek
  - Pentridge_Prison<br>

  <br>As you may have guessed, the last entry was the answer. Where the hell did that come from? Trail Navigator Victoria, of course..!

  <blockquote>
    This pretty man-made lake and leafy parklands contrast starkly with <mark>the backdrop of Pentridge Prison</mark>, its imposing walls built from bluestone excavated from the lake. Stroll around the lake and along a section of Merri Creek, admiring the famous black swans and Ibis. Kids will love the playgrounds.
  </blockquote>
</details>
