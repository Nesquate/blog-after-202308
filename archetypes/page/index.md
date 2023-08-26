+++
title = '{{ replace .File.ContentBaseName `-` ` ` | title }}'
layout = ''
slug = '{{ replace .File.ContentBaseName `-` ` ` | title }}'
[menu]
    [menu.main]
        weight = -99
        [menu.main.params]
            icon = 'link'
+++