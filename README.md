# Gnarly Skate School

The Gnarly Skate School webiste are a website where parents can read about us and sign up, to have their kids learn skateboaring in all its forms. We teach kids from age 8-15 and of all skill levels. We offer a safe environment, progress and a lot of fun!

On this website, you as a user will be able to find information about the school, the type of lessons we provide, a gallery and a sign up form. 


# Bugs & Fixes

I encountered a bug where I can't get the header to blend into the background. I fixed the issue by googling my way to the conclusion found on this link: (https://www.w3schools.com/howto/howto_css_image_text.asp)

I am boring the CI dumplink for the form on this site.
The footer, I got from CI Love running Project.

I encountered a bug where my background images for the header and the signup page, did not show on the deployed link through Github. I fixed it by changing the directory of the background images. instead of having background-image: url ('/assets/images/hero-image.jpg') in css I removed the "/" and added "../" for it to work. So it looked like this:
 url ('../assets/images/hero-image.jpg')

img being too big foor respsonsivness.

# Testing

I tested both the html on (https://validator.w3.org/#validate_by_input) and css on (https://jigsaw.w3.org/css-validator/) and found no errors.
