Douban
======

Douban supports OAuth 1 and 2.

Douban OAuth 1
--------------

Douban OAuth 1 works similar to Twitter OAuth.

Douban offers per application keys named ``Consumer Key`` and ``Consumer
Secret``. To enable Douban OAuth these two keys are needed. Further
documentation at `Douban Services & API`_:

- Register a new application at `Douban API Key`_, make sure to mark the **web
  application** checkbox.

- Fill **Consumer Key** and **Consumer Secret** values in settings::

      SOCIAL_AUTH_DOUBAN_KEY = ''
      SOCIAL_AUTH_DOUBAN_SECRET = ''

- Add ``'social.backends.douban.DoubanOAuth'`` into your
  ``AUTHENTICATION_BACKENDS``.


Douban OAuth2
-------------

Recently Douban launched their OAuth2 support and the new developer site, you
can find documentation at `Douban Developers`_. To setup OAuth2 follow:

- Register a new application at `Create A Douban App`_, make sure to mark the
  **web application** checkbox.

- Fill **Consumer Key** and **Consumer Secret** values in settings::

      SOCIAL_AUTH_DOUBAN2_KEY = ''
      SOCIAL_AUTH_DOUBAN2_SECRET = ''

- Add ``'social.backends.douban.DoubanOAuth2'`` into your
  ``AUTHENTICATION_BACKENDS``.

.. _Douban Services & API: http://www.douban.com/service/
.. _Douban API Key: http://www.douban.com/service/apikey/apply
.. _Douban Developers: http://developers.douban.com/
.. _Create A Douban App : http://developers.douban.com/apikey/apply
