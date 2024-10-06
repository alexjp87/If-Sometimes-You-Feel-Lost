# If Sometimes You Feel Lost

## HTML/CSS Project - practice the basics of responsive design

### Project Goals
The primary goal of this project is to build a responsive web page using HTML and CSS.

The secondary goal of this project is to motivate myself and others who may be feeling overwhelmed whilst learning the tools necessary to enter the tech industry as professionals.

I hope to implement an eye-catching aesthetic using HTML and pure CSS techniques to demonstrate a range of effects that can be achieved without knowing any JavaScript whatsoever, and also that the content may motivate anyone who comes across it if they are in a relatable situation.

### User Stories
From the perspective of the user:

- As someone with multiple devices, I want to be able to view the web page on any of my devices
- As someone learning to develop web pages, I want an example of what can be achieved using only HTML and CSS
- As someone trying to enter the tech industry as a professional, I want to relate to others who are tackling the same challenges

From the perspective of the developer:

- As a beginner developer, I want to practice mobile-first, responsive design
- As a beginner developer, I want to practice HTML to develop my skills
- As a beginner developer, I want to practice CSS to develop my skills


### Design Choices
The page is structured as a number of `article` elements nested inside a `section` element.

The `section` element places the nested `article` elements into a grid, specifying that the column will be responsive (min 320px, max 33% vw).

- CSS features common to most `article` elements:
    - flexbox
    - boxsizing
    - transitions
    - border radius
    - :hover
    - padding

- CSS features of individual `article` elements:

    - 1. 'Pink Glow'
        - linear-gradient
        - background-blend-mode
        - animation (@keyframes)

!['pink-glow'](screenshots/01_pink-glow.PNG "pink glow")

    - 2. 'Disappear'
        - opacity
        - text-decoration

!['disappear'](screenshots/02_disappear.PNG "disappear")

    - 3. 'Breathe'
        - transform: translateY()
        - animation (@keyframes)
        - font-weight
        - font-family
    
!['breathe'](screenshots/03_breathe.PNG "breathe")

    - 4. 'Greyscale'
        - background-image
        - background-size
        - filter

!["greyscale"](screenshots/04_greyscale.PNG "greyscale")

    - 5. 'Neon'
        - transition-delay
        - :nth-child()
        - filter

!["neon"](screenshots/05_neon.PNG "neon")

    - 6. 'Portal'
        - box-shadow
        - :nth-child()
        - font-size
    
!["portal"](screenshots/06_portal.PNG "portal")

    - 7. 'Flip-card'
        - perspective
        - transform: rotateY()
        - transform-style
        - position
        - backface-visibility
    
!["flip-card"](screenshots/07_flip-card.PNG "flip-card")

    - 8. 'Explosion'
        - grid-template-areas
        - grid-area
        - transform: translate(x,y)
        - cubic-bezier (transition)
        - overflow

!["explosion"](screenshots/08_explosion.PNG "explosion")

Finally there is a border on the <section> element, designed to draw the eye downwards along with the flow of the <article> elements.

!["border"](screenshots/border.PNG "border")

### Technologies Used
- HTML
- CSS
- Git
- Github

### Challenges
The biggest challenge I faced in this project was catching up the commenting after doing a significant amount of coding.

Going back over the code to add comments required a lot more time getting the code fresh in my mind again, whereas if I had commented as I coded I would have saved myself that extra time.

I've learned a lesson here - comment as I code!

### Credit
'Greyscale':
- background image - https://alphacoders.com/hulk-phone-wallpapers

'Flip-card':
- 'front' background image - https://wallpaper.forfun.com/fetch/e0/e0969d284a6e520bcd659dd968fa28f8.jpeg
- 'back' background image - https://uk.pinterest.com/pin/16-amazing-phone-wallpapers--772648879812732375/

'Explosion':
- explosion effect - https://codepad.co/snippet/pure-css-explosion-effect
