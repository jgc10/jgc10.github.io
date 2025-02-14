---
title: "redirect"
date: "2025-01-01"
draft: true     # set this to false to publish
layout: "post"
tags: ["tag1", "tag2"]
authors: ["author1", "author2"]
---
<!-- This template is for posting external blog posts. Be sure to replace both URLs -->
{{< rawhtml >}}
<html>
    <head>
        <meta http-equiv="refresh" content="2; url=http://example.com"><!-- PUT URL HERE -->
    </head>
    <body>
        <p>If you are not redirected, <a href=http://example.com>click here</a>.</p><!-- PUT URL HERE -->
    </body>
</html>
{{< /rawhtml >}}