+++
title = "Collections"
description = "Page of collections"
template = "prose.html"
insert_anchor_links = "none"

[extra]
lang = 'en'
footer = false

# title = "Tags"

math = false
mermaid = false
copy = false
comment = false
reaction = false
+++

{{ collection(file="books.toml") }}
{{ collection(file="games.toml") }}
{{ collection(file="movies.toml") }}