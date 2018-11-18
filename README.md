Step by Step Instructions
  
  1. Select all images we will be woring with by using document.querySelectorAll. Look at style components to find which action to look for. 

  2. Make a function to check for the slide and add an event listener for the 'scroll' so images show up when the criteria is met.

  3. Add a debounce function so the function does not run too many times. This function can be altered to run the function in specific intervals returning much less data. 

  4. Take the slider images and loop over each one adding the math necessary to find out where the image is about 50% visible and when the image is gone by finding out where the bottom of the image is.   