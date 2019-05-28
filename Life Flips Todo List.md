# Life Flips To Do List
## Things to do in order
#Projects/Life Flips#
### 0. Generate interest
~~- [ ] Fix email sign up for Interest page~~
~~- [ ] Improve on Interest page. As I develop screenshots and a clearer picture of what this product is, add to my Interest page. Interest page should eventually become my product description for product launch.~~

### 1. Get an idea of what it looks like
- [x] Make wireframe
[image:5D865A40-FC80-4DC2-9502-CCC4ADA0B367-708-0000006CBABC913A/bear_sketch@2x.png]

This is a bit illegible (but thankfully I can still read it...that’s not always the case). I think I can prototype a working version quick enough where I can just move straight towards screenshots or demos to give you a better picture.

I tried looking up a bunch of wire framing / prototyping apps. Many good ones, but mostly subscription based, and lots more features than I need. I just drew a quick mock up above. This is all I need to get a picture in my head.

### 2. Develop first set of basic features
- [x] Build web viewer on iOS for iPad
- [x] Build up UICollectionView architecture
- [x] Cycle through multiple web viewers with slide right transition

### 3. Better loading experience
- [x] Pre-load the webpage before flipping

### 4. Let user add websites to list
- [x] Create an overview page
- [x] Add ‘+’ button to add page
- [x] Let user fill in url to be loaded
- [x] Save list of URLs to local persistent storage
- [x] Let user delete a webpage from list

### 5. Navigating slides
- [x] Slide left on slide to go forward
- [x] Slide right on slide to go to previous slide

#### 5.1 Cleaning up
- [x] Reformat website string entered by user
- [x] Highlight cell with incompatible url string, and add message saying url needs to be edited
- [x] Reset flip counter when tapping left or right
- [x] Add domain name and GLD as string (facebook.com) as title of cell
- [x] Add cross to delete button
- [x] Make sure delete button doesn’t appear when adding a new cell
- [x] Fix transition so that it pops up, not slides right. That way when we dismiss the top layer view, it doesn’t back track
- [x] Add icons for navigation toolbar items
- [x] Clean up cells and formatting

### 6. Get paid
- [ ] Add donation button
In the future, I’d like to include some premium features. But until I get user feedback, I don’t know what they might be yet. For now, I’ll still add an option for users to donate, in case their feeling generous 😉

## Time to market this product
### Prepare App Store materials
Here’s some resources to review when I get to this stage
* [https://medium.com/@the_manifest/how-to-publish-your-app-on-apples-app-store-in-2018-f76f22a5c33a](https://medium.com/@the_manifest/how-to-publish-your-app-on-apples-app-store-in-2018-f76f22a5c33a)
* [App Review - App Store - Apple Developer](https://developer.apple.com/app-store/review/#common-app-rejections)
* [https://developer.apple.com/app-store/submissions/](https://developer.apple.com/app-store/submissions/)
- [x] Sign up for developers license
- [x] Create icon
- [x] Generate photos
	- [x] Screenshots
	- [ ] Real life placement on wooden table
- [x] Generate app metadata
	- [x] Category
	- [x] Product description
	- [x] Additional keywords

### Upload to App Store for approval
Budget in 1 - 3 days for review. Probably need a week overall in case it gets rejected!
- [x] Upload

### Prepare launch materials
- [x] Write up for Product Hunt
- [x] Write up for Reddit
- [ ] betalist
- [x] Create landing page
	- [x] Link to App Store page
	- [x] Include all of the same marketing materials as on the App Store page

## Some features to build in the future
- [x] Let user move order of sites 
- [ ] Let user identify which sites should be shown more frequently (“around once a day”, “around once a month”, etc.)
- [ ] Add sharing button to life flips to add to board
- [ ] Add autofill in safari
- [ ] Add data protection
- [ ] add iCloud
- [ ] add in app purchases
- [ ] Turn off sound of previous flip when flipping to next flip
- [x] Add extension for WKWebView to add url_string variable, so we can identify the web view (Can we extend WKWebView? check docs)
- [x] Add URL bar on top of navigation
- [ ] Hide navigation bar after 5 seconds of inactivity
- [ ] Add invisible UIView on top of WebView to track taps and scrolls
- [x] Allow user to “pin” existing website and replace it’s current one, or add new one
- [x] Add “Add website” cell, and replace add website button
- [ ] Allow user to edit url string
- [ ] Add title of page as subheader of cell
- [ ] Turn delete button red
- [ ] Add transition to delete icon appearing
- [ ] Prevent accidentally going through cell when editing
- [ ] Add Credit for Photo by  [Thijs Slootjes](https://unsplash.com/photos/lVOL-j5XtQY?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)  on  [Unsplash](https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on UICollectionView if possible
- [ ] Two finger swipe left/right to next flip 
- [ ] On resuming flips, flip to next in 7 seconds, then from there, resume the 30 second intervals
- [ ] Let user edit name of link 
- [ ] Better yet, come up with better cosmetic name
- [ ] Turn add button into a play button
- [ ] Pick colors for your block
- [ ] Tag blocks
- [ ] Some websites are not stable - need a second login
- [ ] need some time to learn the right way to put the url into it. I will suggest to have some quick tutorial of guiding people put first website into it 
- [ ] Add goals
- [ ] Don’t allow sound from websites button
- [x] Add photos
- [ ] Add share functionality to quickly add links
- [x] Bug: When deleting cell, after editing, when you tap a cell with index higher than deleted cell, it takes you to wrong site.
- [ ] Move photo permission notification to when you add a photo
- [ ] Make edit timer length keyboard into number keypad
- [ ] Create bundles of suggested sites to add
- [ ] When tapping link to open new tab, should exit out to safari, or do something else(?)
- [ ] Feedback from Gian: Ching one comment on Life Flips, would be good if the first time someone open the app, they’re told that to activate it, they should hit one of the blocks they’ve added.  Wasn’t totally intuitive for me initially, thought that it might replace my screensaver by default for example 

### Improve Marketing
- [ ] Create demo video (in app)
- [ ] Create demo video (real life)

  - [ ] Upload to App Store
- [ ] Reposition the messaging of the app
	- [ ] Use Life Flips to create a digital photo frame. Place it at work or at home
	- [ ] Use Life Flips to stay on top of the news. Get a quick glance at the headlines of the world’s top news sites
	- [ ] Use Life Flips to view your various dashboards, either personal or for business
		- [ ] Have KPIs you need to stay on top of? Put a URL to that dashboard
		- [ ] Like to keep track of your fitness? Log into Fitbit.com to see your dashboard
	- [ ] Add your email account to check periodically for new emails
	- [ ] Add your to do list to periodically remind you of what needs to be done
	- [ ] Add your goals and mission statement to periodically be reminded of what you want to be doing
- [ ] Reach out
	- [ ] Facebook friends
	- [ ] Strangers on the internet
		- [ ] More on ProductHunt
		- [ ] More on Reddit
		- [ ] Betalist?
		- [ ] IndieHackers
- [ ] Update tagline to: “Newsfeed for the internet”

### Premium functionality
- [ ] Let users change background of dashboard
- [ ] Let users add on a photo album or an automatically-generated photo list that shows photos of their friends / families, memories, etc.
- [ ] Build in gmail integration
- [ ] Build in Reminders integration
- [ ] Memorization cards - things you need to review on a regular basis
	- [ ] SAT vocabulary words
	- [ ] New language words
	- [ ] Could be used in a classroom / homework
	- [ ] Stuff you need to be reminded of
- [ ] Hello screen that says good morning / good evening
	- [ ] Beautiful UI to make users feel good when they enter the app
- [ ] Automatically go to first flip
- [ ] Button to reduce frequency or completely delete flip from within flip
- [ ] Fix mobile-oriented websites on iPad
- [ ] Identify quicker ways to add new flips
- [ ] Move add flip button to top of bar

- [ ] Links redirect to Safari