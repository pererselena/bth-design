---
views:
    main:
        template: anax/v2/article/default
        data:
            class: blog

    byline: false
    block-about: false
    article-toc: false

    blog-list:
        region: main
        template: anax/v2/blog-list/default
        sort: 2
        data:
            dateFormat: j F Y
            meta:
                type: toc
                orderby: publishTime
                orderorder: desc

    blog-toc:
        region: sidebar-right
        template: anax/v2/blog-toc/default
        sort: 2
        data:
            meta:
                type: copy
                view: blog-list

---
Nytt och Noterat
===========================

Här kommer jag berätta om min underbara resa till Schweiz. Jag, min man och våra vänner bestämde oss att resa till Schweiz under en helg i april 2018. Det var en underbar resa som vi kommer minnas länge. Vi har besökt Zürich, Luzern och Alperna.

Schweiz är landet med många kännetecken. Höga bergstoppar, en enorm finanssektor, varumärken som Rolex och en av världens rikaste befolkning. Belägen i Centraleuropa bjuder landet på härligt klimat, vacker natur och kultur i världsklass.

Schweiz omgärdas av Frankrike i väst, Italien i söder, Österrike i öster och Tyskland i norr. Det är ett av Europa minsta länder och en av få nationer som står utanför Europeiska Unionen.
