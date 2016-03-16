# Background and Use Case

NCSU Libraries is a non-commercial, not-for-profit cultural heritage institution. We worked to engage our campus community, and strengthen our brand, via a variety of channels both online and off. Social media has come to play a crucial role in that effort. As a cultural heritage institution it is our role to distribute information about the campus, provide access to that information and make that information discoverable. One way in which we are doing that is through the NCSU Libraries Lentil application.

The NCSU Libraries Lentil application is an open source Ruby on Rails application that was developed in 2013 by NCSU Libraries. Lentil was built as a platform that allows us to harvest and display images based on tagsets that are created for various events throughout the year. It is not a one-off project, but rather it serves as a centralized hub that allowing us to manage and maintain Instagram consistently when it directly relates to various branding efforts of both the libraries as a whole as well as individual departments within the libraries.

Different versions of this application have been in use for nearly 4 years, and with the recent changes to the Instagram API we are worried that we will no longer be able to engage with our community using Instagram. While we may not be a publisher in the traditional sense, we use Lentil to discover content from our community, get digital rights to the media shared by our community and to share that media both on various NCSU Libraries websites as well as within our university archives. All of which are directly related to the valid use cases outlined in your recent API changes.

The primary purpose of the application is to allow members of our campus community to contribute unique content based on their experience within our libraries at different events throughout the year. It then allows us to discover and present that content in a unique manner. In addition to presenting the content on various websites within the organization, the application is designed to provide a mechanism for archival storage of the images. Social media plays an increasingly important role in telling the unique cultural heritage of our institution. That cultural heritage is preserved in our university archives. The NCSU Libraries Lentil app allows photos that have been tagged and approved as appropriate to be transferred into our archives, preserving the heritage of our institution.

# Functionality

There are two main components to the NCSU Libraries Lentil application the front end, public facing, component and the administrative interface. The public facing component displays images that were identified by a unique hashtag or set of hashtags that were created and disseminated in other marketing materials for events on campus. It then provides the opportunity for members of our community to rate and sort the images in a variety of ways. This creates an interactive experience for users to interact with images taken by their peers.

The administrative interface to the application allows administrators to determine the exact hashtags that will be harvested. The purpose of this is to allow a variety of hashtags for a variety of different events or marketing efforts to be added into the system. Once a tag is created and added to a tagset that tagset can be harvested at regular intervals. In addition to allowing for the management of tagsets the administrative interface provides a tool to moderate which images will appear on the public facing side of the application. This assists us in ensuring that the images posted are appropriate for our audience, and are in fact relevant to our particular hashtags. These images can then be transferred to the university archives for archival preservation.

Again, it is important to stress that the purpose of this app is to collect images related to the unique cultural heritage of our institution and to allow a mechanism to preserve those images for future researchers. It is not, and will never be, a commercial or for-profit application.

# API Requirements

NCSU Libraries Lentil app relies on the 'Tags' API endpoint to find the appropriate tags for the collection of images. As such it requires a scope of public_content. The app is designed to capture images based on tags not on particular user accounts, and works to capture any publicly available image that is posted with the corresponding hashtag.

# Contact Information

I would greatly appreciate the opportunity to speak with someone about the changes made to the API and how they affect our unique use case. As a non-profit, non-commercial institution that is working to preserve our own history, it is very important that we are able to preserve these images. Please feel free to email me at tdstoffe@ncsu.edu with any questions that you may have.
