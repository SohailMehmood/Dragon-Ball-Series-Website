# Testing

Return back to the [README.md](README.md) file.

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fsohailmehmood.github.io%2FDragon-Ball-Series-Website%2Findex.html) | ![screenshot](documentation/index-validation.png) | Pass: No Errors |
| Dragonball | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fsohailmehmood.github.io%2FDragon-Ball-Series-Website%2Fdragonball.html) | ![screenshot](documentation/dragonball-validation.png) | Section Lack Heading Warnings |
| Dragonball Z | [W3C](https://validator.w3.org/nu/?doc%253Dhttps%253A%252F%252Fsohailmehmood.github.io%252FDragon-Ball-Series-Website%252Fdragonball-z.html) | ![screenshot](documentation/dragonball-z-validation.png) | Section Lack Heading Warnings |
| Dragonball GT | [W3C](https://validator.w3.org/nu/?doc%253Dhttps%253A%252F%252Fsohailmehmood.github.io%252FDragon-Ball-Series-Website%252Fdragonball-gt.html) | ![screenshot](documentation/dragonball-gt-validation.png) | Section Lack Heading Warnings |
| Dragonball Super | [W3C](https://validator.w3.org/nu/?doc%253Dhttps%253A%252F%252Fsohailmehmood.github.io%252FDragon-Ball-Series-Website%252Fdragonball-super.html) | ![screenshot](documentation/dragonball-super-validation.png) | Section Lack Heading Warnings |
| Contact | [W3C](https://validator.w3.org/nu/?doc%253Dhttps%253A%252F%252Fsohailmehmood.github.io%252FDragon-Ball-Series-Website%252Fcontact.html) | ![screenshot](documentation/contact-validation.png) | Pass: No Errors |
| Confirmation | [W3C](https://validator.w3.org/nu/?doc%253Dhttps%253A%252F%252Fsohailmehmood.github.io%252FDragon-Ball-Series-Website%252Fconfirmation.html%253Fname%253DSohail%2526email%253Dsohail_mehmood%252540hotmail.com%2526message%253Ddsa) | ![screenshot](documentation/confirmation-validation.png) | Pass: No Errors |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri%253Dhttps%253A%252F%252Fsohailmehmood.github.io%252FDragon-Ball-Series-Website%252Findex.html%2526profile%253Dcss3svg%2526usermedium%253Dall%2526warning%253D1%2526vextwarning%253D%2526lang%253Den) | ![screenshot](documentation/index-validation-css.png) | Pass: No Errors |

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | Dragon Ball | Dragon Ball Z | Dragon Ball GT | Dragon Ball Super | Contact | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Chrome | ![screenshot](documentation/chrome-home.png) | ![screenshot](documentation/chrome-dragonball.png) | ![screenshot](documentation/chrome-dragonball-z.png) | ![screenshot](documentation/chrome-dragonball-gt.png) | ![screenshot](documentation/chrome-dragonball-super.png) | ![screenshot](documentation/chrome-contact.png) | Works as expected |
| Firefox | ![screenshot](documentation/firefox-home.png) | ![screenshot](documentation/firefox-dragonball.png) | ![screenshot](documentation/firefox-dragonball-z.png) | ![screenshot](documentation/firefox-dragonball-gt.png) | ![screenshot](documentation/firefox-dragonball-super.png) | ![screenshot](documentation/firefox-contact.png) | Works as expected |
| Edge | ![screenshot](documentation/edge-home.png) | ![screenshot](documentation/edge-dragonball.png) | ![screenshot](documentation/edge-dragonball-z.png) | ![screenshot](documentation/edge-dragonball-gt.png) | ![screenshot](documentation/edge-dragonball-super.png) | ![screenshot](documentation/edge-contact.png) | Works as expected |
| Opera | ![screenshot](documentation/opera-home.png) | ![screenshot](documentation/opera-dragonball.png) | ![screenshot](documentation/opera-dragonball-z.png) | ![screenshot](documentation/opera-dragonball-gt.png) | ![screenshot](documentation/opera-dragonball-super.png) | ![screenshot](documentation/opera-contact.png) | Works as expected |

## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Home | Dragon Ball | Dragon Ball Z | Dragon Ball GT | Dragon Ball Super | Contact | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Mobile (DevTools) | ![screenshot](documentation/responsive-mobile-home.png) | ![screenshot](documentation/responsive-mobile-dragonball.png) | ![screenshot](documentation/responsive-mobile-dragonball-z.png) | ![screenshot](documentation/responsive-mobile-dragonball-gt.png) | ![screenshot](documentation/responsive-mobile-dragonball-super.png) | ![screenshot](documentation/responsive-mobile-contact.png) | Works as expected |
| Desktop | ![screenshot](documentation/responsive-desktop-home.png) | ![screenshot](documentation/responsive-desktop-dragonball.png) | ![screenshot](documentation/responsive-desktop-dragonball-z.png) | ![screenshot](documentation/responsive-desktop-dragonball-gt.png) | ![screenshot](documentation/responsive-desktop-dragonball-super.png) | ![screenshot](documentation/responsive-desktop-contact.png) | Works as expected |
| 4K Monitor | ![screenshot](documentation/responsive-4k-home.png) | ![screenshot](documentation/responsive-4k-dragonball.png) | ![screenshot](documentation/responsive-4k-dragonball-z.png) | ![screenshot](documentation/responsive-4k-dragonball-gt.png) | ![screenshot](documentation/responsive-4k-dragonball-super.png) | ![screenshot](documentation/responsive-4k-contact.png) | Noticeable scaling issues |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse-mobile-home.png) | ![screenshot](documentation/lighthouse-desktop-home.png) | Some minor warnings |
| Dragonball | ![screenshot](documentation/lighthouse-mobile-dragonball.png) | ![screenshot](documentation/lighthouse-desktop-dragonball.png) | Slow response time due to video |
| Dragonball Z | ![screenshot](documentation/lighthouse-mobile-dragonball-z.png) | ![screenshot](documentation/lighthouse-desktop-dragonball-z.png) | Slow response time due to video |
| Dragonball GT | ![screenshot](documentation/lighthouse-mobile-dragonball-gt.png) | ![screenshot](documentation/lighthouse-desktop-dragonball-gt.png) | Slow response time due to video |
| Dragonball Super | ![screenshot](documentation/lighthouse-mobile-dragonball-super.png) | ![screenshot](documentation/lighthouse-desktop-dragonball-super.png) | Slow response time due to video |
| Contact| ![screenshot](documentation/lighthouse-mobile-contact.png) | ![screenshot](documentation/lighthouse-desktop-contact.png) | Some minor warnings |

