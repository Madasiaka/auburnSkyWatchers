# Auburn Sky Watchers
Auburn Sky Watchers is a site that was created for a local astronomy group. The static site is fully integrated with a NASA API in order to display the official astronomy photo (or, rarely - video) of the day from NASA's database. 

**Link to project:** https://auburnskywatchers.netlify.app/

![A colorful site showing a galaxy and telescope](![image](https://user-images.githubusercontent.com/99517890/191667939-96f66d5e-2c51-4f9b-b783-5d6af7e9c18a.png))

## How It's Made:

**Tech used:** HTML, CSS, JavaScript, REST API

This site was built using html, CSS and vanilla javascript. The site is linked to the public NASA image API and pulls images associated with selectable dates chosen by the user. Both images and videos are supported, and the text discriptions of images is pulled in and displayed on the DOM alongside the images.

## Optimizations

In the future I would shrink image sizes as they are imported in order to speed loading times for the site. Links to further information based on the subject of the daily photo is another feature that I aim to implement in the future.

## Lessons Learned:

This site was a good review on using javascript event listeners in order to attach/remove classes from elements to remove them from the DOM.
