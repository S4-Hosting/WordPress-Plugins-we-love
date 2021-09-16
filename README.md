# S4 - WordPress plugins we love

There are hundreds of thousands of WordPress plugins out there, both in the official WP repository and in various other places. 

We've spent a massive amount of time trying out different ones as solutions to needs or issues with both our own and client sites, and ended up with a very small list that we use repeatedly.

### Plugins we actively use...

#### Fluent Forms

There are a LOT of form plugins out there, and I'm sure many of them are great, we've tried quite a few and our previous favourite was Caldera. The reason that we've moved almost all of the sites that we manage over to Fluent is that it seems to deal with form spam much better than any of the others that we've workded with, literally cutting it from hundreds or thousands of mails a day on some sites down to virtually zero. It's also simple, intuitive, and the free version provides plenty of functionality for most simple form use cases.

WP repository: https://wordpress.org/plugins/fluentform/

#### Easy WP SMTP

The name covers it all really. There are other plugins out there that do the same thing, many of them offer more options, bells and whistles, but this one is easy, stable and updated pretty regularly. It just works. 

WP repository: https://wordpress.org/plugins/easy-wp-smtp/

#### WP Vivid

It's a strange name for a backup plugin but whatever works. The open source free version of this plugin is great and it does exactly what it is supposed to, backing up, restonring and migrating sites, and hardly ever throws up a problem (although it doesn't seem to like some secruity plugins). Irritations are the fact that it doesn't let you back up to S3 compatible storage apart from Amazon, and that you can't schedule the back up time of day. Despite that it is the best and ost consistent of the very many backup plugins we've tried out. 

Over time this plugin is becoming more bloated and complex, we don't want to use it for staging (especially when you can't push back to live without paying for premium), and we don't want it to clean up media. This is all pretty annoying and messy but it's still ann excellent backup plugin.

WP repository: https://wordpress.org/plugins/wpvivid-backuprestore/

#### The SEO Framework

Not every WordPress site needs an SEO plugin but used properly they can be useful. We've tried them all (almost) and this is the one that we consistently come back to. It's light, clean, fast, simple, and unlike some won't try to take over your WP admin with boxes, and messages and whatever else. 

WP repository: https://wordpress.org/plugins/autodescription/

#### MainWP Child

We use MainWP to keep track of outdated plugins and themes on WP sites that we host. It's just the best tool that we have found for the job. 

Actually we maintain our own fork for our clients, which is closely synced with the upstream.

---

### ...and ones we are watching

#### Fluent SMTP

Given how much we love Fluent Forms there is a pretty good chance that we are going to like Fluent SMTP as well. It has a lot more integrations and clever stuff than Easy WP SMTP, which may or may not be a good thing depending on your needs. We just haven't found the time to play with it very much yet. 

WP repository: https://wordpress.org/plugins/fluent-smtp/
