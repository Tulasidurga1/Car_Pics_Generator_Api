# Car_Pics_Generator_Api
# Hosted Link:-https://tulasidurga1.github.io/Car_Pics_Generator_Api/
# HTML (index.html):
- The HTML file sets up the structure of your webpage.
- It includes a meta tag for character encoding, viewport settings, and a title.
- A link tag is used to include an external CSS file named "style.css."
- Inside the <body> section, there's a container <div> that holds the content.
- The <h3> element displays the title of your page.
- A button with the class "btn" and ID "btn" is provided for users to trigger the car image retrieval.
- A <div> with the class "car-container" is used to display the car image and name.
- An initial car image and name are set with placeholder content.
  # CSS (style.css):
- The CSS code is responsible for styling the HTML elements.
- The body rule sets the background color and centers the content both horizontally and vertically.
- The .container class styles the main container for your content.
- The .btn class styles the "Get car" button, including its appearance when it's disabled.
- The .car-img class styles the car image inside the container.
- The .car-name class styles the car name element.
- The .car-container class initially hides the car container.
  # JavaScript (script.js):
- The JavaScript code adds interactivity to your webpage.
- It retrieves references to various HTML elements using document.getElementById and document.querySelector.
- It attaches an event listener to the "Get car" button using btn.addEventListener. The event listener listens for clicks on the button.
- Inside the event listener function:
- It sets the source of the car image to "spinner.svg" to indicate loading.
- It makes an asynchronous fetch request to the Unsplash API to obtain a random car image and name. Make sure to replace "YOUR_UNSPLASH_API_KEY" with your actual API key.
- It updates the button text to "Get Cars" after fetching the data.
- It displays the car container by changing its CSS display property to "block."
- It updates the car image source and car name text with data from the API response.
- In case of an error during the fetch operation, it catches the error, logs it, and provides error feedback to the user.
- Additionally, there's a comment at the end that indicates an initial call to getRandomCar(), which is not defined in the provided code but seems to be a placeholder for fetching a random car image when the page loads.

- This code combines HTML, CSS, and JavaScript to create a webpage that fetches and displays random car images and names from the Unsplash API when the "Get car" button is clicked, and it handles errors gracefully.
