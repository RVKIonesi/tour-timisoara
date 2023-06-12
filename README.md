# Tour Timisoara

![Tour Timisoara logo](assets/images/logo-timisoara.jpg)

# UX

## Project Goals

The primary goal of Tour Timisoara is to assist travelers to explore and learn about the city of Timisoara by providing tour guides!

1. Clear and concise information shown on multiple devices for tourists.

2. Briefly introduce the city and potential tour guides.

3. Allows questions to be asked using a questionaire form.

4. Provides tour booking service and map of the city on contact page.

## User stories

1. As a potential tourist my goal is to learn about Timisoara before planning a trip or during my stay.

2. As a potential tourist I want to get some insight on how to get a tour guide.

3. As a potential tourist I want to get a brief intro for the tour guides and check out tourist reviews.

## Design Choices

 Colour Scheme - The following colours were selected from the logo image:

 #E5E40D - https://g.co/kgs/QuKb16

 #F8694A - https://g.co/kgs/ybzC2i

 #A2A97F - https://g.co/kgs/yk5VmX

 #D1D3C6 - https://g.co/kgs/NguS4u

 ### Images

The logo image was obtained from:

https://en.wikipedia.org/wiki/Timi%C8%99oara#/media/File:Historical_Timisoara_CoA_1919_version.jpg

 The images were obtained from the following website:

  https://timisoara2023.eu/en/visit-timi%C8%99oara/
 
### Video

THe video was obtained from the following website:

https://www.dw.com/en/timisoara-2023-shine-your-light/video-64610633


## Languages Used

- HTML
- CSS

## Frameworks & Programs Used

- [Balsamiq](https://balsamiq.com/) - To create the wireframes.
- [Git](https://git-scm.com/) - For version control.
- [GitHub](https://www.github.com) - To store code.

## Testing & Bugs

Testing was ongoing throughout the entire build. I utilised Chrome developer tools whilst building to pinpoint and troubleshoot any issues as I went along.

During development I made use of google developer tools to ensure everything was working correctly and to assist with troubleshooting when things weren't working as expected.

1. Tested video using video element but the player didn't work at this point as it is a different format, u3m8 instead of mp4. 
 a. I looked for solutions online, after a few attemps using code from stackoverflow I turned to Youtube.
 b. found the solution for it, please see links:

 c. youtube video explaining solution - https://www.youtube.com/watch?v=eVKm12T0BPg

 d. website link from where the solution came - https://videojs.com/getting-started

2. Tested navigation, all links work. However, couldn't get explore Timisoara text to link to video underneath the image on home page, as such looked for a way to put image as background and video infront on home page. 

 a. As I researched different methods, these include using z-index and moving the div's from within header to section element.
 b. After several hours of messing around, I remembered that I've done this before and I can use an image as a background.
 c. Solution  is to use the following code in the body:
  body {
    background: url('../image.jpg');
    
    background-position: center;
    background-attachment: fixed;
    -webkit-background-size: cover; 
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
  }

3. Tested video several times, figured out how to put video in the section page infront of the image.

## The W3C Validator

[W3C](https://validator.w3.org/) was used to validate the HTML on all pages of the website. 

[W3C](https://validator.w3.org/) was also used to validate the CSS.

- [index.html] (https://validator.w3.org) - needs adding.

- [style.css] - needs adding.




---
 
