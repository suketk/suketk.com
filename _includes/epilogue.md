--

{% if page.writing_time %}

    {% if page.title == site.posts.first.title %}

This post took {{ page.writing_time }} minutes to write. [Why I'm telling you this.]({{site.url}}/peeling-back-the-curtain)

Join the [email list]({{site.url}}/subscribe) to see the writing times for future posts!

    {% else %}

This post took <span style='background: black; color: black'>redacted</span> minutes to write.

[Here's why I share this data]({{site.url}}/peeling-back-the-curtain) with my email list. [Join us!]({{site.url}}/subscribe)

    {% endif %}

{% endif %}

*P.S: You can find more of my thoughts on Twitter [@{{site.twitter_username}}](https://twitter.com/{{site.twitter_username}}).*

{% if page.tweet %}

{% include tweet.html link=page.tweet %}

{% endif %}