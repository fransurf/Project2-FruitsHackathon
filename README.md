# General Assembly

# Project 2 - ‘Fruity4You’
A React web application providing nutritional information on fruits, plus a user-input fruit-salad maker.  The app queries a public API (FruityVice) using Express.js for nutritional content for the frontend website. My personal contribution consisted of building the fruit info pages and designing and implementing the styling using SASS.


![Landing page image](/readMe2_imgs/landing2.png)

## View ’Fruity4You’?
xxxx

## Brief

48-hr hackathon (3 people): build a React application that consumes a public API. The application must have several components and can have a router; be deployed online and accessible to the public.

## Technologies
Node.js | Express.js | JavaScript | Axios | React.js | React Hooks | SASS

* **Node.js** & **JavaScript** were employed to build-out an organised frontend site, querying a publicly available API using **Express.js**
* **React.js** & **React hooks** were used to provide the basic structure of the frontend, calling data using **axios** GET-, POST-, PUT- & DELETE- requests updating state using useEffect() & useState() hooks
* **SASS** was used for styling throughout

## Personal contribution
* **Site vision:** Searching through a range of publicly available APIs, we decided upon FruityVice nutritional information API for its well-structured data objects. We envisaged providing, not only the nutritional info on each fruit, but a fruit salad (& originally a fruit smoothie) user-input option, which would allow users to select a variety of fruits and calculate the nutritional information for their own fruit salad.

* **FruitShow page:** A simple page presenting nutritional information of an individually selected fruit. The user is directed to this page when selecting from an index of fruits. The code employs the useParams() react-router-dom function, to identify the selected fruit according to the route link and maps through the API data array to find the given fruit and provide relevant nutritional information. The React functions useEffect() and useState() are used to make the axios request awaiting the data before loading the page information. The fruit.name is used to import a correspondingly named image of the identified fruit using a template literal image url structure.

* **Styling:** We wanted the website to be fun, engaging and look fresh. Fresh fruity colours were selected for the fonts and general colouring. I created unique scss variables for consistency across the site. I also selected a range of high-resolution, consistently-styled fruits background images, to give a consistent fun and fresh feeling across the site.

* **Fruit slot machine:** For the styling on the ‘Salad Maker’ page, we opted for making a fruit slot machine alongside the user-selected input, devised as a play on the commonly used ‘fruit machine’ slang. An image of a typical slot machine was embedded on the left half of the page, with the central slot windows blanked out. As the user selects 3 fruits from the salad maker dropdown list, images of the selected fruits appear in the slot windows, so that the user is able to visualise their fruit salad.

## Displays
* **Landing page (above):** A deliciously bright image of a range of fruits was selected for the landing page in order to draw the attention in and make the mouth water. The red navigation bar and buttons complement the colours within the image. White font and a slight border around the text box make the text pop out, whilst retaining the focus of the attention on the fruity background.

* **Fruits index page (below):** Lead coder: Yuanmeng Liu. Scrollable fruits index page with a fixed background image so that individual fruits Cards scroll over the lemons and limes background (which remains static). Clicking anywhere on the card takes the user to the relevant individual NP page.

![Landing page image](/readMe2_imgs/fruitIndex2.png)

* **Individual Fruits pages (below, e.g. apricot):** Unlike other pages, a simple background was selected for this page in order to make the nutritional information easy to read. The yellow background chosen to contrast against the read navigation bars and buttons, is used on the salad maker page for consistency across the site.

![Landing page image](/readMe2_imgs/fruitShow2.png)

* **Fruit salad (see below):** Lead coder: Jack Robinson. The salad maker is presented over another mouth-watering fruit image. To the right, is the user-input fruit salad maker selection and nutritional information form. To the left, is the fruit slot machine, which updates with the selected fruits. 

![Landing page image](/readMe2_imgs/saladMaker1-2.png)
![Landing page image](/readMe2_imgs/saladMaker2-2.png)


## Key Learning
* Embedded learning of Node.js, React.js & JavaScript for backend
* Embedded learning of querying a publicly-available APIs using React hooks and axios requests.
* My major point of learning was in using SCSS, to create a consistent theme across the website using classes & unique variables.
## Challenges
* No major challenges were experienced in this project.
## Future improvements
* We had originally envisaged creating a fruit-smoothie maker option, which I think would be a beneficial addition given the popular trend for smoothies
* Add a mobile-friendly version



