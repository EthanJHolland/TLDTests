# TLDTests
Simple front ends for feature testing

Notes for MVP front end design:

The "WHAT IS THIS" button on the home screen is meant to show off a sample letter. I'm thinking about writing a quick intro to Letterdesk as this sample letter. It would also help people understand what this is, and how to use it. Also mentioning that there may be glitches and to contact us if they see any. Also people might be more inspired to write letters if they see one first.

Do not know if it shows up as well on other people's commputer screens because wasn't paying SUPER attention to pxls vs percentages.

Each of the three html pages (home, reading, writing) has its own stylesheet, and even though they share many of the same elements (i.e. "logo"), it doesn't mean that the "logo" element refers to the same thing on all of the html pages, since there are different versions of logos (big logo, small logo, logo before the letter, logo after the letter, etc) 
So...the CSS and HTML is basically a mess (not written super well) and may be easy to get confused if you're looking at it.

Also, certain elements belong to one class but I redefined their styles again later in the CSS page to override a specific previous style -- this means the ORDERING of elements on the CSS page matters

Side note -- functional change** we should think about soon for early releases: right now I don't think it supports numbers (or anything that requires SHIFT key differentiation), and I was thinking there may be a way to  map individual keypresses to the character that comes out (instead of the keycode) so it's 100% accurate -- shouldn't take up much more space than current method (remind to talk about it later)

Happy Valentines! Excited for this whenever it may be