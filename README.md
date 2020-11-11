
# Jane Smith Ceramic Studio

### Milestone Project 1 


**A live version of the page can be viewed here** (link)

*mockup image here*

Jane Smith Ceramic Studio is a website about a fictional ceramist who wants to present her work for a potential new customer or business client. It's important, both when it comes to B2C and B2B, for the user to see the range of products the ceramist offers so they can make a decision on buying. The site therefore presents a collection of her work in form of a gallery. You can also find a page with information about the ceramist, a page with links to her stockists and a contact page where you can leave her a message.

##### The goals for this website is to:
- Give a good first impression to new customers.
- Sell products to customers.
- Show customers where to buy the products.
- Show items to customers who's looking for a unique piece for their home.
- Show items to a retailer who wants to find good handcrafted products for their store.
- Let users now that the ceramist is open to collaborations.
- Make it easy for users to contact the ceramist.

# UX


#### User Stories
- As a retailer I want to find the contact information so that I can get in touch with her for business inquiries.
- As a potential customer I want to visit her shop to find out what products I can buy.
- As a stockist I would like to view her collection of products to see if it's something I would buy for my store.
- As a fan of the ceramist I would like to find where the nearest stockists are located so that I can purchase her products.
- As a follower on social media I want to see the ceramist collection so that I can see if it’s something I want to buy.

#### Strategy 
I wanted to make a user-friendly website for the ceramist where she can offer her products for potential customers. I wanted the site to be easy navigated with a clean and minimalistic design. It’s important both for a customer and a retailer to see what kinds of products the ceramist offers and they should immidiately see where to navigate to do this, the first thing you see is therefore a call to action button that leads straight to her shop on Etsy.

#### Surface
The colors I’ve used for the project is a light grey, #777777, and a warm terracotta, #E2725B. I chose these colors because they are easy to read on screen and also the two most common colors on clay that’s used for pottery which gives the site an earthy tone and a thought through theme.  

#### Wireframes
 - 


# Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.

**Header** - A fixed header that exists on every page. The logo is located to the left and by clicking it the user returns to the home page. The navigation menu is located to the right so that the user easy can navigate through the different pages.

**Navbar** - Each page features a responsive Bootstrap navbar that’s collapsed when viewing on smaller screens. 

The navbar has an hover effect so when the user hovers over the different pages the text changes color to a warm terracotta orange. The same color is used to show wich page the user is currently on.

**Home** - The home page features a hero image that shows some of the items in the collection. This will give the user an idea of what type of items the ceramist offers. 

On top of the image is a call to action button that guides the user to her shop.

**Collection** - The collection page features a masonry gallery with images of all her work. 

**About** - The about page features a photo of the ceramist to give a personal feeling to who’s making the items. The page also provides a short text that gives some information about who she is and her thoughts about her work. You can also read that she’s available for collaborations.

**Stockists** - The stockist page features an unordered list with links to all her stockists so that users easily can access their websites and get information on where to purchase her items.

**Contact** - The contact page features a form where the user can fill in their name, email address and a message. The page also features another photo of the ceramist to make it personal.

**Footer** - A fixed footer that exists on every page. Located in the center of the footer are four social media icons with links to the ceramist social media pages. The links have the same hover effects as the navbar and changes color when hovering over them.

#### Features Left to Implement
- A webshop directly on her page so that customers easily can buy her work without beeing redirect to Etsy.com.

- A lightbox feature to the image galley so that customers can get a better view of the items.

- The forms functionality.

# Technologies Used


- HTML5 and CSS3

- [Bootstrap](https://getbootstrap.com) - The project uses Bootstrap to make the site responsive and to implement features such as the navbar and the buttons.

- [FontAwesome](https://fontawesome.com) - The project uses FontAwesome for social media icons.

- [Google Fonts](https://fonts.google.com) - The project uses Work Sans from Google Fonts.

- [Balsamiq](https://balsamiq.com) - Used in the beginning of the project to create wireframes.

- [DevTools](https://developers.google.com/web/tools/chrome-devtools) - The project has used DevTools to test responsiveness and diagnose problems. The tool **Lighthouse** has been used to improve the website's quality.




# Testing

#### Testing User Stories 
*

#### During Development

 - Mobile responsiveness for about page not worked as intended.
Image appears too small and does not move to underneath the text.
	- changed setting from `col-6` to `col-12 col-lg-6` 

 - Mobile responsiveness for stockists page not worked as intended.
Image appears too small and does not move to underneath the text.
	- changed setting from `col-6` to `col-12 col-lg-6` 

 - Mobile responsiveness for contact page not worked as intended.
Image appears too small and does not move to underneath the text.
	- changed setting from `col-6` to `col-12 col-lg-6` 

 - Header remained transparent when scrolling which made the menu difficult to read.
	- Added `bg-white` to `navbar` class.

 - Unable to customize color on navbar menu when hovering.
	- Added `!important;`  to `.menu a`

 - Unable to customize color on active pages.
	- Added `!important;`  to `.active`

 - Send Button in the form on the contact page was hidden behind the image on small devices.
   - Removed `position:absolute` from `.button-text-form`


 - Collection menu on collection page not responsive on mobile devices.
	 

 - Collection link in navbar is not working

 - Hero image has the wrong size
	
 - Mobile responsiveness for hero image not working. 


 - Mobile responsiveness for hero text not working. Text size does not decrease and is overlapping.


# Deployment

# Credits

#### Content
The content of the website is fictional but to seek information and inspiration about what other ceramist puts on their websites I have visited these talented ceramist and their sites:

https://madokarindal.com

https://www.catherinedixceramics.com

https://www.handandfire.com

https://www.victoriamorrispottery.com

https://www.epocaceramic.com


#### Media
Unsplash - used for ceramic images

Shutterstock - used for hero image and about image

#### Acknowledgements
Stack Overflow was used for solving small issues  












python3 -m http.server
