---
title: Contributors
---

### Ways to contribute:

The simplest way to get up and running is to [join our Mastodon community](https://social.fitopen.org). One look at our [roadmap](https://github.com/fitopen/main/blob/master/roadmap.md), however, and you'll soon see we have many big plans. These will take some time to come to fruition. If you have ideas for website content, please send me a message. Anybody can suggest improvements to our code over at [Github](https://github.com/fitopen). This includes designs, project plans, priorities, core documents (such as the [code of conduct](https://github.com/fitopen/main/blob/master/code-of-conduct.md)), scripts to get the draft codebase implemented - any feedback or assistance is most welcome and absolutely encouraged. Lastly we have setup as a (TBD social enterprise) and can now take donations to cover our running costs of this effort's website, its social network, and testing and development of these [roadmap](https://github.com/fitopen/main/blob/master/roadmap.md) plans.

### Contributors

All assistance, whether donations, code snippets, content, etc. will be listed here via their expressed agreement. For website authored content, please note the following author collections:

<ul>
  {% for author in site.authors %}
    <li>
      <h2><a href="{{ author.url }}">{{ author.name }}</a></h2>
      <h3>{{ author.position }}</h3>
      <p>{{ author.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>
