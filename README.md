# UFOs

## Project Overview
In conjunction with Dana, a data journalist writing about UFOs in her hometown of McMinnville, Oregon, here we create a table to organize UFO data that is stored as a JavaScript array and display the data on a local server/browser. To add to the functionality of this data, we add a variety of filters and the logic required to display more fine-tuned results. These filters include date, city, state, country and shape.

#### Resources used
* Data Sources: data.js, bootstrap components
* Software: Visual Studio Code (version 1.63.2)

## Results
How someone might use this new webpage, you ask?

To start, let's take a look at some of the main elements of the page: 


![site1](https://user-images.githubusercontent.com/87148145/159185390-b4e13215-f63c-442f-a387-32684c1e9617.PNG)



- Once we navigate past the site title, we immediately see a introspective description of the data that introduces the importance of documenting and exploring UFO sightings. 

- Next, we see the table data located below this introductory information about the data. **Keep your eyes peeled on this one!** It will change soon enough.

- Now we get to the good stuff: the filter itself! After typing in data here, the user can hit the return button to see an updated list of UFO sightings. In the example below, the user searches by spacecraft shape, typing 'fireball' in the 'Shape' field and seeing all seven results for the odd-shaped UFOs, including dates of the sightings and other relevant data:


![site2](https://user-images.githubusercontent.com/87148145/159185525-a80023a9-5999-4231-b470-b2c2dd79c2d8.PNG)


## Summary
Dana is ecstatic about this website -- it even changes its display dynamically depending on whether the user is on a mobile phone or laptop! 

However, there are a couple draw-backs. 
- One is that there is no 'search' button, so we are relying on the user to intuitively press this on their keyboard. If they are on a mobile device, they may in fact be out-of-luck since most browsers do not include a 'return' key within the keyboard interface. We recommend the data journalists consider adding this if they are looking to host the data long-term. 
- Another drawback of this interface is that there is no way obvious way to store search results and compare across filters, aside from screenshots. Perhaps it would prove useful to add a button with an 'id' field for each sighting object so that users can store these as a list or individual objects for further investigation. 
- Finally, let's get some pictures added to the sighting objects. What's a chevron-shaped UFO look like, anyway?!