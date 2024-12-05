Potpourri aims to be a social platform for very quick, shareable content. It's a place to share
memes, photos, cartoons videos, quotes, links, etc.

There should be a community and discussion around the content, but the sharing of content is the
main focus.

It's modeled after an old website called soup.io, which died a very slow death up until 2020 when
it shut down. It had a lot of issues, including a lack of moderation, spam, countless technical
issues, and that one time when they lost 2 years worth of all their history data in a database
crash.

I believe that, a lot of these issues can be mitigated by using smaller server instances networked
with the fediverse.

# Posts

Types of posts:

- Image posts
- Video posts
- Audio posts
- Text posts
- Quote posts
- Link posts

# User profiles

User profiles should be highly customizable making it almost your own personal website. They should
be able to choose from a variety of themes with configurable colors, and even allow custom CSS.

Custom CSS can represent a massive security risk, so before adding that we will have to carefully
consider how to sanitize and contain it without making it useless.

Soup even allowed custom JavaScript, but had to take a lot of extra steps encapsulate their website
controls in cross-origin iframes, protect it from cookie stealers, clickjacking, etc.

I don't consider it a worthwhile risk. If custom page functionality is needed, that should be
something you can talk about with your instance administrator, or contributing it to the project
yourself.

# Groups

Groups are feeds that can be filled by multiple users. Users that are part of a group can
post and repost to the group, and react to other people's posts in the name of the group.

Groups can be either open or invite only. Only members of the group can post to or from the group.
But everyone can follow a group.

Groups have administrators. Administrators can add and remove members, edit the groups profile.
Posts to a group can only be deleted by administrators or the post author.

Groups can be used to form communities around specific topics, but they can also be used by single
users to just separate their own content into multiple feeds.
