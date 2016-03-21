#Cocoaheads.app Ideas and Thoughts

##Existing apps / Competition

Turns out, there are some existing Cocoaheads specific apps already. Some of which are even open sourced on GitHub. All of them are area specific. Namely:

- https://github.com/CocoaHeadsBrasil/CocoaHeadsApp (Brazil only)
- https://github.com/CocoaHeadsNL/CocoaHeadsNL-iOS (Netherlands only) ([App Store](https://itunes.apple.com/de/app/cocoaheadsnl/id998188273?mt=8))
- Cocoaheads France App (France only) ([App Store](https://itunes.apple.com/de/app/cocoaheads-france/id823553836?mt=8))
- https://github.com/CHAtl/CocoaHeads-iOS (not quite done)


## The New App

This new app is going to try to do the following (better):

- Technical
    - Should use the latest technology available for iOS development
    - Should not consider being multi-platform, since it's targeted for Apple user groups anyway
    - Backend / Data storage:  I suggest using CloudKit, because why not?
    - The language will be Swift, because this app is also an opportunity to learn
    - The project should include unit tests, be well documented, use continous integration
    
- Characteristics
    - Should be very easy to use
    - Should work for all Cocoaheads chapters
    - Should be multilingual
    - Should be a universal app that works and looks great on all device types and sizes
    
- Basic Features (i.e. first release)
    - Should allow organizing the meetings (+ announcing it on Twitter/Facebook as well)
    - Should allow following chapters and being informed about meetings, time shifts, illness of speakers...
    - Should allow chapter members to signal attendance
    - Should display information about each chapter
        - Name
        - Place, if regular (on a map)
        - Chapter icon (if any)
        - Member list (maybe private information, in that case just number of followers?)
        - Contact information (twitter, etc.)
    - Chat about the session beforehand (What to talk about? Change proposals? Suggest another date? ...)

- Advanced Features (i.e. things for updates)
    - Should show videos or links to videos (recordings of sessions)
    - Should show slides for sessions (maybe at the session entry, maybe in a separate section that collects all the material)
    - Should show link to demo code
    - Should allow communication (per chapter, or maybe per session entry)
    - Should allow upload of photos (?)
    
- Very Advanced Features
    - to be discussed
    
    
## How is this supposed to work (well)?

This is the first time I try to start an open source project of this kind. It is also quite ambitious, in that the result should in the best case be used by thousands of Cocoaheads "members" around the world. It should help the original idea of Cocoaheads to bring people together in monthly meetings and allow for visitors in foreign cities and or countries to simply go visit another chapter's meeting while they are there. The app shall help them figure it all out easily.

That said, how are we going to work together?

First of all, I'm going to grant everyone that wants to participate write access to the repository. **But**, I think it would be best that we discuss features, ideas etc. before anything gets pushed to the repo. Even after discussion is done, I'd like for at least the bigger changes to issue pull request that will be reviewed and discussed before going into the main branch.

Basically, standard procedure for any kind of collaborative untertaking — talk to each other and reach an agreement, instead of ignoring each other and becoming annoyed.

## Where to begin?

Well, first we need to discuss what the app should basically look like. Maybe it's as easy as bringing up a few other apps that could serve as an inspiration? It's probably best to start very basic and plain. A few tabs with one basic feature per tab. The solution to the age old problem of starting something new, be it writing a book or something else, is to simply begin.

Let's begin!
