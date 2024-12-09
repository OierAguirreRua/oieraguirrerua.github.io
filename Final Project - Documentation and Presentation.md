# Oier Aguirre Rua - Official Website 
# [OierAguirreRuaWebsite](https://oieraguirrerua.github.io/index.html)
## What is this project?
- Tis project is a personal and proffesional website, which gathers some of the work of my music portfolio

## Why this project?
- I believe that having a website is essential because it allows you to showcase your work, connect with a global audience, and establish your professional presence in an accessible and reliable way.
- It is also good for me to have everything in the same place gathered, instead of having my work just somewhere in my computer. People can also see that I am multifacetic in some way, and this is a good way to show it and show my work.
- It is a first step towards creating a much better website. I also coded everything myself, which makes me a bit proud.
- If someone asks me what I do, this is a good way to summarize it.

## Inpirations and Resources
### Inspirations
- Singer: Dani Fernández's new album webpage. [Dani_Fernández_LaJauría](https://danifernandezoficial.es)
- Producer: Rafa Sarfina. [Rafa_Sardina_Webpage](https://rafasardina.com)
- Singer: Pablo Alborán. [Pablo_Alborán_Webpage](https://www.pabloalboran.es/?frontpage=true)


### Resources
- This individual called Dani Krossing helped me a lot in understanding how the basics of html work and the process to follow.[HTML_for_Begginers](https://www.youtube.com/watch?v=v8jDnBYc0bs&list=PL0eyrZgxdwhwP0AxnbBiDBCi53LK9uCMZ)

## How does it work? 
- Looks easy but is more difficult than it seams. Everything needs a line of code
- Every section has its own HTML and CSS file (It is possible to combine the css in one, but much better structured this way)

- Divided in folders:
    - HTML files
    - CSS files
    - Images
    - Content for Songwriting
    - Content for Production
    - Content for Film Scoring

## Process:
- Research and understanding everything
- Thinking about outline
- Coding (and debugging)

# Project 
## Navigation Tab and basics
- I implemented the navigation tab in every HTML file, so that it stays the same.
- Let´s look at it![index.html](https://github.com/OierAguirreRua/oieraguirrerua.github.io/blob/main/index.html)

- HTML:
    - Structure:
        - Type: HTML
        - Language: EN

        - 2 main sections:
            - Head
                - Some HTML presets
                - Little logo Icon on Tab. I asked Chat GPT to make me a simple one.
                    - [ChatGPT_TabLogo](https://github.com/OierAguirreRua/oieraguirrerua.github.io/blob/main/Chat%20GPT%20Interaction/Icon%20for%20Tab.png)
                - "Reset Style Sheet".
                    - It resets the presets each browser has. Deletes margins for example.
                    - Grab the idea from YouTube, Dani Krossing
                    - I Took the code from [css-tricks](https://css-tricks.com/an-interview-with-elad-shechter-on-the-new-css-reset/) 
                        - [My_Reset_Stylesheet](https://github.com/OierAguirreRua/oieraguirrerua.github.io/blob/main/CSS/reset.css)
- CSS:(Steps)
    - 1. Cursor to pointer when on any of the navigation tab words
    - 2. Instagram and TikTok logos in
    - 3. Create the bar where the navigation goes (background)
    - 4. Put the logo on the left side of navigation bar. Assign a witdh, height, etc. I asked ChatGPT to create the logo for me
        - [ChatGPT_MainLogo](https://github.com/OierAguirreRua/oieraguirrerua.github.io/blob/main/Chat%20GPT%20Interaction/Logo.png)
    - 5. "Flex" to put all of the menu options in line. Assign a color to them
    - 6. "Hover" when the mouse is on top to change color. Songwriting, Production and Film-Scoring in different colors
    - 7. Put the social media icons to the right side. "Flex-direction: Colum" to have Instagram on top of Tik Tok
    - 8. "Hover" images to color when on top. If not black and white
    - 9. "Hover" social media text in blue

### Problems:
- Not many as I followed the video

## Home Page          
- Coding of Navigation Tab + the following 

- HTML: [index.html](https://github.com/OierAguirreRua/oieraguirrerua.github.io/blob/main/index.html)
    - Body
        - My background image
        - My name
            - "Oier" on one side
            - "Aguirre" and "Rua" on the other
- CSS:[main.css](https://github.com/OierAguirreRua/oieraguirrerua.github.io/blob/main/CSS/main.css)
    - "Oier". Bigger font size, position, font-type, etc.
    - "last-name". "Flex-direction: Column". The rest similar to "Oier" but with different position

### Problems:
- It did not display to cover the entire background

### Solution:
- Width: 100%. Instead of fixed amounts

## About Me
- Coding of Navigation Tab + the following 

- HTML:[aboutme.html](https://github.com/OierAguirreRua/oieraguirrerua.github.io/blob/main/aboutme.html)
    - Replace Home Page Image
    - Text (2 groups):
        - Meet Oier. I separated Meet and Oier with "span" so that I could assign different colors
        - Biography. Separated in paragraphs
- CSS:[aboutme.css](https://github.com/OierAguirreRua/oieraguirrerua.github.io/blob/main/CSS/aboutme.css)
    - Image: Much smaller. Height of 50% and witdh o 40%. Positioned with margin-left and margin-right
    - Header: "Display: flex" to display the header in line
        - "Oier" in another color. It matches the "About Me" navigation color 

## Problems:
- Nothing important. It was preatty easy (long though)

## Songwriting

- Coding of Navigation Tab + the following 

- HTML: [songwriting.html](https://github.com/OierAguirreRua/oieraguirrerua.github.io/blob/main/songwriting.html)
    - Header "Listen to some of my SONGS". Similar to "About Me" sectin
    - In one class all together: 
        - Image:
        - Audios:
            - MP3's. Linked to a folder inside the main folder of the project.
            - Each of them in a different section having:
                - Title
                - Audio file
            

- CSS: [songwriting.css](https://github.com/OierAguirreRua/oieraguirrerua.github.io/blob/main/CSS/songwriting.css)
    - Image and audios class. "Display: flex" So that image to the right and audios to the left
    - Adjusted how big the image is and position
    - Audios "felx-direction: colum" so that they showed in column.
        - A Class for each song title and its audio.    
        - Audio files put in containers, so that I could adjust eh position of them

### Problems
- I coudldn´t have the audios to display, they did not appear. I spent 2 hours trying to fix it, so I have all my code to Chat GPT and ask to find the solution 
- [ChatGPT_Interaction1](https://github.com/OierAguirreRua/oieraguirrerua.github.io/blob/main/Chat%20GPT%20Interaction/Chat%20GPT%20Audio%20Issue%201.png)
- [ChatGPT_Interaction2](https://github.com/OierAguirreRua/oieraguirrerua.github.io/blob/main/Chat%20GPT%20Interaction/Chat%20GPT%20Audio%20Issue%202.png)

### Solution
- The reset Style Sheet was preventing the audios to display! It makes sense.
- Added the following to the "reset.css" to fix it:
```css
    audio {
  display: inline-block; 
  width: 100%; 
  height: auto; 
  max-width: 100%;
}
```
## Production
- It was pretty similar to the Songwriting section, but changing the audios and image of position and giving them other colors (purple). Thus, I will not go in detail in this one. 
- HTML:[production.html](https://github.com/OierAguirreRua/oieraguirrerua.github.io/blob/main/production.html)
- CSS: [production.css](https://github.com/OierAguirreRua/oieraguirrerua.github.io/blob/main/CSS/production.css)

## Film Scoring
- For this one I have a folder with 6 scenes I put the music to. All of them exported to mp4´s to weigh as less as posible and be supported by most of the browsers.

- Code:
 - Coding of Navigation Tab + the following 

- HTML: [filmscoring.html](https://github.com/OierAguirreRua/oieraguirrerua.github.io/blob/main/filmscoring.html)
    - I have a header too. Similar to other sections, but in yellow the word "Film Scenes"
    - I did the same as with the MP3's on the songwriting and production sections, put them in groups to then position them together.
        - Videos Up Row. 3 videos
        - Videos Down Row. 3 Videos
    - Assigned a poster from the "Posters" folder so that they would look good before playing the video.

- CSS:  [filmscoring.css](https://github.com/OierAguirreRua/oieraguirrerua.github.io/blob/main/CSS/filmscoring.css)
    - All the videos. "Justify-content: center". Display evenly throughout the screen
        - Videos Up Row. 
            - "Display: flex". So that they are in line
            - Margins
            - "Justify-content: space between;". Space evenly between them.
        - Videos Down Row
            - Same thing as with the Videos Up Row.

### Problems
- Had some videos in mov first, but had to export them to mp4 as it was too much weight (over 100MB) for github to upload it.

## Contact
- As it is a fixed image, I was going to code the "Contact Info" at first, as I did in the Home Page.
- I decided not to do so, as it is easier for the image to adapt to different screen sizes.
- Also, much less coding. Even less than main page

- HTML: [contact.html](https://github.com/OierAguirreRua/oieraguirrerua.github.io/blob/main/contact.html)
    - I just copied the html code from the main page.
    - Replaced the image
    - Delete my name "Oier Aguirre Rua"
- CSS: [contact.css](https://github.com/OierAguirreRua/oieraguirrerua.github.io/blob/main/CSS/contact.css)

# Sumary
## What works?
- Interactivity of navigation Tab good.
- Pretty look
- Links to social media work correctly
- "Hover" makes the webpage really interactive
- HTML and CSS files linked correctly
- It is the main idea of what I was going for

## What does not work?
- Adaptability of margins and sizes outside of a 14'' screen.
- I used too many fixed margins instead of % or vh, vw, etc.
    - I need to change that in order for everything to stay the same no matter the screen size. 
    - Text boxes and boxes in general are smalles in a bigger screen and viceversa

- Apart from that, everything I tried and coded works correcty!!

## Future Implementation
- Drop-down menu.
- More visuals. Transitions between different sections. 
- Available for phone and other displays. 

# My thoughts
- Although there are things to make better and fix, I am really proud of it!
- I do have a webpage now with some of my work.
- I coded everything myself!! I am really proud of that! Took really long, but I did it!!






