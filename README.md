# task:
Photo Gallery (Flex/Grid project)

create a public repo on your own github account, name e.g. "Photo Gallery Project"
search for references for photo galleries on google, e.g.: https://supsystic.com/gallery-examples/
read information on best practices at readmes: https://github.com/othneildrew/Best-README-Template
write a readme based on what you have learned
write properly structured code:
create order : "public" = where the index.html is located "public/styles" = where css files are located "public/images" = where you can store images if you don't want to load them online
search for images for the photo gallery, the following google search query helps: "royalty free images" (e.g. https://picsum.photos/)

# idea:

A photo gallery with my own photos of my drawn pictures. The images should rotate 180° and have a white frame on which they can rotate. The reference is "Pictures to Frame" from https://supsystic.com/gallery-examples/.

# proceeding:

The first thing to consider was which grid template would be best for implementing the project. A drawing and the preliminary naming of the images provided a rough overview. Possible expansion options should be based on the number of rows.
A layout of 5 to 3 was created for the start.

## HTML:
The first step was to set up the HTML structure. I integrated the images and did not add a title for the time being, as the plan did not provide for this. 
A figure containing all the images serves as the main div. This was completely sufficient for the distribution on the grid. 

## CSS:

The grid was created and named relatively quickly, and images were removed to create a certain symmetry. Due to the different image sizes
certain ideas could not be realized and were therefore solved with more pragmatic approaches. The plan to have a white background was changed because it didn't match the aesthetics of the pictures. I therefore opted for a light shade of gray and gave the whole thing a frame of 5px.
Then it was time for the rotation and the idea of adding a title and linking them together. The rotation is triggered with a hover on the images. The title is displayed with a 1.5s delay. 
In the end it became a grid of 4 to 10 with 17 images.

# Contributors:
- Frederick Reich https://github.com/FRickReich
- Hadi Nsreeny https://github.com/hnsreeny
- Danny Wild   https://github.com/DTHW 
- Chrissi Eisele https://github.com/zippiskiddy
