12/11

I plan on outlining a basic content management system over the next several days.  I'm going to toss out some ideas about what I need.  Then I'll structure it for a React app.  Next, I'll build out a basic architecture in React.  After that, I'll probably add redux...not sure if I'll need it or not, but most likely.  I'll explore that here.  I don't plan on designing a UI until everything is up and running.

What I need the CMS to do:

  First, and most importantly:

    Create and manage content, i.e.:
      blog posts with:
        blog page styles
        headers & header images
        subheaders
        secondary images
        story text
      contributor bios with:
        contributor photos or emojis or whatever
        brief autobiography

    Preview content before it's published.
    Create and manage site styles?

  Once basic functionality is complete:  
    Track site statistics: user engagement, views, likes, and shares.
    Admin tier for moderating user engagement?
    Enable editors to markup blog posts?
    some kind of dynamic stylesheet creator:
      after creating basic prescribed blog post elements, a user should be able to arrange them however they want on the page:
        all items can be dragged, rearranged and resized on the page, but must occupy a given position: top, middle, bottom.
          navbar must be on the very top
          users can manipulate:
            color
            background color
            font-size
            opacity
            image size
            add subheaders
          
