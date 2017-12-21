# EventMobi "Hack Days" Project - Froala / Embed.ly

Organizers want to share decks, videos, twitter feeds, and other rich
content throughout the event app. Froala (the RTE used in Experience
Manager) supports Embed.ly, which promises to allow content from 500+
sources to be embedded simply by clicking a button and pasting a URL.
This would be a proof of concept for using Embed.ly to enable planners
to embed rich content throughout the app (e.g., anywhere they can use
the HTML editor)

Use Case: According to some folks in Sales, it would be a great selling
point to be able to embed in a session description a related video for
the conference. For example, reminders of gala events for all attendees
in the evening, or a video reminding people of next year's conference
(i.e. good for advertising)

![]()

RESEARCH:

- Understand how Embed.ly "works"
- Cards? Decks? What are they in relation to Embed.ly?

- Determine where Froala is being used
- Determine how EventMobi CMS "saves" Froala content


UPDATES:

20/12/17
- Worked on EM Embedding of Froala editor, see the HACKDAYS branch in the CMS Frontend repo.

19/12/17
- Created initial repo
- Perform initial research
- Update README.MD as research is performed


TODOS:

- How to overcome the awkward editing workflow once an Embed.ly link is
  within the content?
- Implement Iris Platform streaming video sample
- Does the Iris Platform use the " [oEmbed](https://oembed.com/) " spec
- Create Presentation based on this README.MD doc using
  [remark.js](https://remarkjs.com)
- **CANCEL TRIALS FOR FROALA, EMBED.LY and IRIS PLATFORM AFTER PROJECT
  IS DONE.**


INFORMAL (SKETCH) NOTES

- Use Embed.ly to embed a physical external player from another source
  that streams live streaming content from irisplatform.io
- How do we overcome cross-domain issues if we are going to embed the
  player in point one? (CORS?)
- How do we overcome https to http related cross-domain issues?
- How do we embed this in the EventMobi Platform?
- In EventMobi platform, explore the files "emRichTextEditor",
  emRichTextEditorDecorator"
- Explore the repo "
  [Angular-Froala](https://github.com/froala/angular-froala) "
- Need to understand how the emRichTextEditor is abstracted in the
  EventMobi Platform
- NOTE: Looks like the EventMobi Plaform is using licence 1.2. . I am
  currently testing for 2.x


COMPLETED:

- Setup Froala Account
- Setup initial Embed.ly account
- Setup initial IrisPlatform.io account
- Download Froala Source Files
- Initial Exploration of Froala API
- Build initial Demo Page implementing Froala Editor


REFERENCES:

[MobiLab Concepts & Sign Up](https://docs.google.com/a/eventmobi.com/document/d/18qFc-Sv2tVkFIDsOwIluN6kiwiwnnIfnIG9ypHX6K0M/edit?usp=sharing)

Froala Home Page
[Froala (API) Embed.ly Integration Example](https://www.froala.com/wysiwyg-editor/examples/embedly)
[Froala (API) Live Content Preview](https://www.froala.com/wysiwyg-editor/examples/live-content-preview)

Embed.ly Home Page
[Embed.ly in Froala project page at Embed.ly](https://app.embed.ly/organization/embed-in-froala)

[Iris Platform Home Page](https://irisplatform.io/)
[Creating a Broadcast App on IrisPlatform.io](https://irisplatform.io/docs/broadcasting/howto/)

[oEmbed Specfication](https://oembed.com/)


- [Angular Froala](https://github.com/froala/angular-froala)
- [Angular Embed.ly](https://github.com/lithiumtech/angular-embedly)
- [Alternate Angular Embed.ly](https://github.com/Urigo/angular-embedly)

