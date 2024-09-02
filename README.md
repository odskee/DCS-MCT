# DCS-MCT
MCT (Mission & Commander Toolbox) is a stand-alone tool to design, build and share an aviation based MilSim operation.  MCT attempts to skirt the fine line between the MilSim environment and it's real-world counterparts - great effort is made to use conventional terms, practices and approaches wherever possible while accommodating the many differences and limitations of the MilSim environments we use and the people we interact with.

<br />

It is a (currently Windows only) program installed locally on your system and is capable of operating as it's own experience.  Additionally, an online counterpart - MCT Online - enhances the functionality of MCT and provides additional multiplayer capabilities in the context of planning and building MilSim operations.

<br />

# Features

<br />
MCT has a continually growing list of features; some of which are still being developed but all are at some existing level of integration and / or development.  MCT itself is in a pre-release state and some features while present are still being 'polished'...
<br />
<ul>
  <li>Design & Build tactical operations for solo or multiplayer use</li>
  <li>DCS Miz / Trk agnostic import including customisation of imported elements</li>
  <li>Dynamically and intelligently swap between coordinate formats based on airframe</li>
  <li>Advanced Intel management - declare Threats, Targets, Friends and Assets with additional parameters inc. file & resource attachments</li>
  <ul>
    <li>Add intel individually or import from another operation</li>
    <li>Declare threat types, range and location descriptions of Intel</li>
    <li>Attach external resources (links etc.) and Files to intel items</li>
  </ul>
  <li>Advanced Package management - Build your packages either from scratch or using imported units from an existing MilSim operation</li>
  <ul>
    <li>Add, Assign and Manage Comms between Package Assets</li>
    <li>Pre-Assign targets from attached Intel</li>
    <li>Include, Exclude or limit the airframes available for a Package Asset</li>
    <li>(In development) Post Op' for Squadron, Public, Friends or Invite-Only</li>
  </ul>
  <li>Service Point management - maintain a list of available friendly airfields / re-arm / re-supply locations</li>
  <ui>
    <li>Add from a list of known service points currently within DCS for each map</li>
    <li>Full support for per location MATAR's</li>
    <li>(In development) Assign various attributes describing service point capabilities</li>
    <li>Add NavSet's and Routes - NavSets can be any navigational aid including TACAN, GPS, NDB etc. and routes are a collection of NavSets that make a certain arrival / departure</li>
  </ui>
  <li>Visually build Package Asset routes</li>
  <ul>
    <li>Display Intel and Service Points - Full NATO symbology is currently being implemented</li>
    <li>Add / Modify Intel visually</li>
    <li>Provide route information for each Package Asset including Arrivals, Diverts, Departures, Activities including activity types</li>
    <li>Specify "Time On" and create Time-On-Target points (including previous activity time accounted for)</li>
    <li>Quickly swap between various units for distance, speed and coordinate type</li>
    <li>(In development) User Expandable - uses LeafletJs implementation with full support for user modification</li>
  </ul>
  <li>Kneeboard Generation - Advanced kneeboard creation for custom designs</li>
  <ul>
    <li>FULLY customisable kneeboards - uses HTML as a template for design</li>
    <li>Template System - Browse an extensive list of "Attribute Tags" that MCT will swap with values on kneeboard creation</li>
    <li>Include Intel attachments as kneeboard items</li>
    <li>Export kneeboards as Png, Jpg, HTML and PDF files including compress to Zip option</li>
    <li>Add custom kneeboards from others quickly without restarting MCT</li>
  </ul>
  <li>(In development) Real-Time player contributions - A separate light-weight stream tool to feed your MP server actions in real-time to MCT Online for Intel synchronisation for other players</li>
  <li>(In development) Real-Time server contributions - A set of tools to allow MP server owners to contribute actions in real-time to MCT Online for Intel synchronisation for other players</li>
  <li>Integrated Help available for each section when building TacOps - See Help at the top</li>
  <li>Pin TacOps for easy access on application start</li>
  <li>(In early development) TacRes Manager - Analyse your flight against a TacOp you've created / participated in</li>
</ul>

<br />

In addition, MCT Online is currently being developed to bring the following features initially...
<ul>
  <li>(In development) TacOp Browser - see and organise running and up-coming squadron and / or public operations</li>
  <li>(In development) TacOp Briefing Room - Similar to kneeboards, use template designs to provide a "view-only" mode for participants</li>
  <li>(In development) MCT Squadron Management - Build and organise your own squadron</li>
  <ul>
    <li>(In development) Member management - add, remove and manage members</li>
    <li>(In development) Squadron Structure - create a hierarchy / membership structure</li>
    <li>(In development) </li>
  </ul>
  <li>(In development) Real-Time Op building - collaboratively build Ops with other MCT users seeing changes applied in real-time</li>
  <li>(In development) Multi-Stage building - "Lock" certain parts of the Operation build, allowing other participants to contribute (i.e. Flight Leads)</li>
  
</ul>

<br />

# How to Join
MCT and MCT Online is currently in pre-release and open to willing testers.  To find out more and join the discussion on MCT, head over to the Discord at [https://discord.gg/Cv3rqHY2nK](https://discord.gg/Cv3rqHY2nK).

<br />

# Licensing
MCT is built by a single developer largely as a passion project and the decision to licence MCT was not taken lightly.  A small amount of funds made through licensing will cover the hosting and on-going upkeep and improvements to MCT and MCT Online.  The larger portion will be made directly available to AndCare UK; a not-for-profit startup (by the developer of MCT) whose goal is to provide accessible civilian reintegration training for members of NATO based Armed Forces using modern approaches to mental health and both real-world / virtual technologies and environments.

<br />
The final cost of MCT nor the mechanism of MCT Online integration is not yet decided but very likely to be around £40 GBP.  Currently, MCT is available to anyone eager & willing to test, see How to Join above.

<br />

# More information
See the GitHub Wiki at <a href="https://github.com/odskee/DCS-MCT/wiki">https://github.com/odskee/DCS-MCT/wiki</a> for more information.
<br />


