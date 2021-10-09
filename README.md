# DevConf-Theme

DevConf is a free Bootstrap 5 for Jekyll. The idea of the template is to emulate  
an Eventbrite like website, where you can publish and marketing you different events,  
it can be easily customized to publish your events, training and workshops, you just need  
to add a YAML file with the metadata for your event, and the template will do the magic.

## Demo

Check the [demo](https://la-rebelion.github.io/DevConf-Jekyll-Theme) in action.

## Features:

* Featured or sponsored event in the main page.
* Sections that can be customized:
  * Listing of all available events.
  * **About** section, where you can describe what is your event about and why 
people should assist. Includes a countdown for the event date. Optionally, include 
videos from previous events to engage possible visitors even more.
  * **Schedule**, you can define different dates for your event, and a flexible 
plan adding as many events per date as you need.
  * Create your "catalog" of **speakers**, then, include the speaker name in the 
event(s) to associate the speaker with the event(s) he participates in. The template 
correlates speakers with events.
  * Custom **sponsors** per event, each event can define its own sponsors with links 
to their websites.
  * Stats section where you can list the expected people, number of conferences, 
number of days of the event, etc. Add the data you need, fully customizable.
  * Define the pricing schema for your **tickets** with _call to action_ buttons.
  * Venue section to let the people how to get to the event, include pictures of the 
locations or previous events.
* Includes a blog link to allow you create you inbound marketing strategy with content.

## Installation

1. Clone the repository.  
`git clone git@github.com:la-rebelion/DevConf-Jekyll-Theme.git`
2. Create a markdown file with the event `slug` in the `front matter`.
```yaml
---
layout: event
event: we-are-developers-2024
---
```
3. Create the manifest file in the `_data/events` directory, same name as `slug`. You can include the following inline metadata to specify the schema that can help you to validate the manifest correctness.
```yaml
# yaml-language-server: $schema=https://my.url.to/the/schema
name: We Are Developers 2024
slug: we-are-developers-2024
... # this is just the head example, continue
```

## Credits

* images are shown for demonstration [Unsplash](https://unsplash.com), photos for everyone.

---

## Original Theme  
This is based on the nice [DevConf-Theme](https://github.com/xriley/DevConf-Theme)

### Theme Details

**Original Demo:** https://themes.3rdwavemedia.com/bootstrap-templates/startup/devconf-free-bootstrap-5-conference-template-for-tech-conferences-and-events/

### Author & License

The original Bootstrap template is made by UX/UI designer [Xiaoying Riley](https://twitter.com/3rdwave_themes) for developers and is 100% FREE as long as you **keep the footer attribution link**. You do not have the rights to resell, sublicense or redistribute (even for free) the template on its own or as a separate attachment from any of your work.

If you'd like to **use the template without the footer attribution link**, you can [buy the **commercial license** via the theme website](https://themes.3rdwavemedia.com/bootstrap-templates/free/devconf-free-bootstrap-5-conference-template-for-tech-conferences-and-events/)

### Credits
- [Bootstrap](https://getbootstrap.com/)
- [FontAwesome](https://fortawesome.github.io/Font-Awesome/)
- [Google fonts](https://fonts.google.com/)
- Image Credit - [European a Tech Conference](https://www.flickr.com/photos/europeanaimages2/albums/72157669104892268) and [TechCrunch](https://www.flickr.com/photos/techcrunch/) [Creative Commons 2.0 license](https://creativecommons.org/licenses/by/2.0/deed.en) (All images are shown for demonstration purposes only)
