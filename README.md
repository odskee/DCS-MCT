# DCS-MCT
DCS Mission & Commander Toolbox is a standalone tool to design, build and share an aviation based MilSim mission.  MCT attempts to skirt the fine line between the MilSim environment and it's real-world counterparts - great effort is made to use conventional terms, practices and approaches wherever possible while accommodating the many differences and limitations of the MilSim environments we use and the people we interact with.  One of the primary incentives for building MCT is to provide the community with a more suitable and appropriate alternative to the often used messy and chaotic approach of spreadsheet UI's.

<br />

# Beta Phase 1
MCT is currently in Beta phase 1 and is only available on an invite basis.  While final figures are yet to be determined, MCT will be licensed for around £30 GBP per year.  All testers will be granted a lifetime licence.

<br />

# How to Join
To find out more and join the discussion on MCT, head over to our Discord at https://discord.gg/pBqbPpqeTZ

<br />

# Appeal
MCT is built by a single developer largely as a passion project and the decision to licence MCT was not taken lightly.  A small amount of funds made through licensing will cover the hosting and on-going upkeep / improvements to MCT.  The larger portion will be made directly available to AndCare UK; a new not-for-profit startup (by the developer of MCT) whose aim is to provide civilian reintegration training for experienced members of the Armed Forces using modern approaches to both mental health and digital / virtual technologies and environments.


<br /> <br />

# Tactical Operation (Work in Progress)
At the heart of MCT is the 'tactical operation' or TacOp - a way of representing the combined effort of multiple people to achieve a general main goal.  A TacOp contains a number of aspects to give each participant the information they need.

## Intel
When building a TacOp, you can add any amount of additional Intel separated into three categories; Threats, Friends and Resources.  An Intel entry can be a variety of different types such as A/V media (Photo's, Videos's etc.) or even pre-made kneeboards, DTC JSON config etc and are made available to all participants.

## Packages & Assets
A tactical operation will typically contain multiple ground and aerial assets of varying roles, such as JTAC's, E3 & AAR and may be a combination of human and / or AI controlled.  These assets are grouped into packages; with each package sharing a common objective.  Typically, a package would consist of one or more E3's, AAR tankers, strike and fighter assets, search and rescue etc.  MCT allows you to structure your packages how you see fit, such as grouping AI assets like AAR and E3 to their own package.

When adding an aerial package asset you can optionally specify a min and / or max quantity (between 1 and 4 inclusive) that this group must contain - for AI assets, this specifies the number of individual planes in the group as specified by the mission creator.

## Service Points
Service Points are places that friendly assets can land / return to.  When setting the theatre for the operation, all available airfields (and associated info) are automatically made available and you can add each location that's important to your Op.  Furthermore, you can add custom service points; such as FARPS and Roads.

Once one or more service points have been added, the associated information such as frequency and Nav Aids are made more easily available to the relevant package assets.

## Routes
Once you've got some packages (and package assets) to work with, you can start building waypoints (their route).  A dedicated route builder is in development and MCT also supports using the DCS Mission editor to import these.

### Route Builder
WIP

### DCS Mission Editor
To use the Mission Editor approach, MCT will generate a .miz file in your DCS Saved Games\Missions directory with the package assets you've declared.  You can then build the route as you usually would within DCS for each asset - MCT will add all assets, including AI controlled, but you are not required to add any waypoints if they are not known (adding waypoints for an AI flight makes AI route information available to MCT).

<br />

## Participants
Please note this section is heavily work in progress!

If you've created an MCT account (and attached your key), you can post your TacOp to the MCT TacOp's Board.  You can either post your TacOp as public, for other players to join, or just for your squadron - note your squadron admin will need to give you permission to post these.

Once your TacOp has been posted, you will be able to see all participants from the design stage - allowing you to post your Op as a concept and continue building around the availability and quantity of patched players.  Note for public posted TacOp's, players are assigned to package assets by themselves while squadron Op's are handled with permissions.

<br /> <br />

# Profiles and Patching
MCT is primarily designed as a group tool with squadron level features.  When you use MCT, you will first need to create a profile, each profile you create may contain one or more 'patches' which can be seen as identities that belong to your profile.

You can create as many profiles as you wish and for any purpose.  For public use, there are no requirements for multiple profiles or patches and are relatively free to set this up how you wish.  When used as part of a squadron, your squadron administrator will create your profile patches and will provide you with an MCT squadron ID and associated information.  Adding this to a profile allows you to then download your squadron patch(es) that you can then use to patch / create Squadron TacOp's with.

<br />

# TacOp's Board
This is where you can find available TacOp's, both public and squadron.  If you do not have a squadron profile, you will not see the squadron TacOp's section.  You can browse available TacOp's and join any that still have 'doors open'.
