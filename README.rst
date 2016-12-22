Mercury-Parser
==============

This is a simple API Client for the `Mercury Web Parser <https://mercury.postlight.com/web-parser/>`_.

Example Usage
-------------

::

    from mercury_parser import ParserAPI

    mercury = ParserAPI(api_key='YOUR API KEY')
    p = mercury.parse('https://some-url')

    # Available attributes:
    p.title
    p.content
    p.date_published
    p.lead_image_url
    p.dek
    p.url
    p.domain
    p.excerpt
    p.word_count
    p.direction
    p.total_pages
    p.rendered_pages
    p.next_page_url

That's basically it, other than ``p.next()``.


Installation
------------

::

    $ pip install mercury-parser

✨🍰✨