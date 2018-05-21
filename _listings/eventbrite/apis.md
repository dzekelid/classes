---
name: Eventbrite
x-slug: eventbrite
description: Eventbrite believes that anyone can be an event organizer. That&rsquo;s
  why they offer tools that make it easy to sell tickets to all kinds of events whether
  it&rsquo;s a photography class or a sold-out concert, an inspiring conference or
  an air-guitar competition. With Eventbrite, organizers can create a customizable
  event page; spread the word with social media; collect money; and gain visibility
  into attendees and sales. Eventbrite is for anyone planning or attending an event.
  It empowers event organizers to become more efficient and effective when bringing
  people together. And people everywhere are searching Eventbrite to discover great
  events that matter to them.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
x-kinRank: "9"
x-alexaRank: ""
tags: Classes
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/apis.md
specificationVersion: "0.14"
apis:
- name: Eventbrite Get Events  Ticket Classes
  x-api-slug: eventbrite
  description: |-
    Returns a paginated response with a key of
    ticket_classes, containing a list of ticket_class.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/ticket_classes/
  tags: Events,,Ticket,Classes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/eventsidticket-classes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/eventsidticket-classes-get-openapi.md
- name: Eventbrite Add Events  Ticket Classes
  x-api-slug: eventbrite
  description: |-
    Creates a new ticket class, returning the result as a ticket_class
    under the key ticket_class.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/ticket_classes/
  tags: Events,,Ticket,Classes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/eventsidticket-classes-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/eventsidticket-classes-post-openapi.md
- name: Eventbrite Get Events  Ticket Classes Ticket Class
  x-api-slug: eventbrite
  description: |-
    Gets and returns a single ticket_class by ID, as the key
    ticket_class.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/ticket_classes/:ticket_class_id/
  tags: Events,,Ticket,Classes,Ticket,Class
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/eventsidticket-classesticket-class-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/eventsidticket-classesticket-class-id-get-openapi.md
- name: Eventbrite Add Events  Ticket Classes Ticket Class
  x-api-slug: eventbrite
  description: Updates an existing ticket class, returning the updated result as a
    ticket_class under the key ticket_class.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/ticket_classes/:ticket_class_id/
  tags: Events,,Ticket,Classes,Ticket,Class
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/eventsidticket-classesticket-class-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/eventsidticket-classesticket-class-id-post-openapi.md
- name: Eventbrite Delete Events  Ticket Classes Ticket Class
  x-api-slug: eventbrite
  description: 'Deletes the ticket class. Returns {&quot;deleted&quot;: true}.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/ticket_classes/:ticket_class_id/
  tags: Events,,Ticket,Classes,Ticket,Class
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/eventsidticket-classesticket-class-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/eventsidticket-classesticket-class-id-delete-openapi.md
- name: Eventbrite Add Events Event  Ticket Classes Ticket Class  Ticket Groups Ticket
    Group
  x-api-slug: eventbrite
  description: Add the Ticket Class with the specified :ticket_class_id that belongs
    to the event with :event_id to the Ticket Group identified by :ticket_group_id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/:event_id/ticket_classes/:ticket_class_id/ticket_groups/:ticket_group_id/
  tags: Events,Event,,Ticket,Classes,Ticket,Class,,Ticket,Groups,Ticket,Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/eventsevent-idticket-classesticket-class-idticket-groupsticket-group-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/eventsevent-idticket-classesticket-class-idticket-groupsticket-group-id-post-openapi.md
- name: Eventbrite Delete Events Event  Ticket Classes Ticket Class  Ticket Groups
    Ticket Group
  x-api-slug: eventbrite
  description: Remove the Ticket Class with the specified :ticket_class_id that belongs
    to the event with :event_id from the Ticket Group identified by :ticket_group_id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/:event_id/ticket_classes/:ticket_class_id/ticket_groups/:ticket_group_id/
  tags: Events,Event,,Ticket,Classes,Ticket,Class,,Ticket,Groups,Ticket,Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/eventsevent-idticket-classesticket-class-idticket-groupsticket-group-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/eventsevent-idticket-classesticket-class-idticket-groupsticket-group-id-delete-openapi.md
- name: Eventbrite Get Events Event  Ticket Classes Ticket Class  Ticket Groups
  x-api-slug: eventbrite
  description: |-
    Get the Ticket Groups for Ticket Class with the specified :ticket_class_id that belongs to the event with :event_id.
    By default, only the ticket groups that are live are shown.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/:event_id/ticket_classes/:ticket_class_id/ticket_groups/
  tags: Events,Event,,Ticket,Classes,Ticket,Class,,Ticket,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/eventsevent-idticket-classesticket-class-idticket-groups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/eventsevent-idticket-classesticket-class-idticket-groups-get-openapi.md
- name: Eventbrite Add Users User  Events Event  Ticket Classes Ticket Class  Ticket
    Groups
  x-api-slug: eventbrite
  description: |-
    Add the Ticket Class with the specified :ticket_class_id of the event with :event_id that
    belongs to the user with :user_id to many Ticket Groups specified with ticket_group_ids.
    If the list provided is empty, remove this ticket class from every ticket group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/:user_id/events/:event_id/ticket_classes/:ticket_class_id/ticket_groups/
  tags: Users,User,,Events,Event,,Ticket,Classes,Ticket,Class,,Ticket,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/usersuser-ideventsevent-idticket-classesticket-class-idticket-groups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/usersuser-ideventsevent-idticket-classesticket-class-idticket-groups-post-openapi.md
- name: Eventbrite
  x-api-slug: eventbrite
  description: Eventbrite believes that anyone can be an event organizer. That&rsquo;s
    why they offer tools that make it easy to sell tickets to all kinds of events
    whether it&rsquo;s a photography class or a sold-out concert, an inspiring conference
    or an air-guitar competition. With Eventbrite, organizers can create a customizable
    event page; spread the word with social media; collect money; and gain visibility
    into attendees and sales. Eventbrite is for anyone planning or attending an event.
    It empowers event organizers to become more efficient and effective when bringing
    people together. And people everywhere are searching Eventbrite to discover great
    events that matter to them.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3
  tags: Classes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/classes/master/_listings/eventbrite/openapi.md
x-common:
- type: x-apigee-console
  url: https://api.apigee.com/v1/consoles/eventbrite/apidescription?format=internal&ver=1351170233000
- type: x-authentication
  url: https://developer.eventbrite.com/docs/auth/
- type: x-base
  url: https://www.eventbriteapi.com/
- type: x-blog
  url: http://blog.eventbrite.com/
- type: x-blog-rss
  url: http://blog.eventbrite.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/eventbrite
- type: x-developer
  url: https://developer.eventbrite.com/
- type: x-github
  url: https://github.com/eventbrite
- type: x-pricing
  url: http://help.eventbrite.com/customer/en_us/portal/articles/428604
- type: x-privacy
  url: http://www.eventbrite.com/privacypolicy
- type: x-sdksio
  url: https://sdks.io/SDK/View/eventbrite
- type: x-selfservice-registration
  url: https://www.eventbrite.com/signup/?referrer=%2F%3Fshow_onboarding%3D1&user_type=prebuyer&user_type_sig=AH_ElWGNJ_zHaAxwjzt5jiCRmvPvNBsy6w
- type: x-terms-of-service
  url: http://www.eventbrite.com/tos
- type: x-twitter
  url: https://twitter.com/EventbriteAPI
- type: x-website
  url: http://developer.eventbrite.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---