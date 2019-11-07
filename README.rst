Google Images Download
######################

Python Script for 'searching' and 'downloading' hundreds of Google images to the local hard disk!

Documentation
=============

* `Documentation Homepage <https://google-images-download.readthedocs.io/en/latest/index.html>`__
* `Installation <https://google-images-download.readthedocs.io/en/latest/installation.html>`__
* `Input arguments <https://google-images-download.readthedocs.io/en/latest/arguments.html>`__
* `Examples and Code Samples <https://google-images-download.readthedocs.io/en/latest/examples.html#>`__


Disclaimer
==========

This program lets you download tons of images from Google.
Please do not download or use any image that violates its copyright terms.
Google Images is a search engine that merely indexes images and allows you to find them.
It does NOT produce its own images and, as such, it doesn't own copyright on any of them.
The original creators of the images own the copyrights.

Images published in the United States are automatically copyrighted by their owners,
even if they do not explicitly carry a copyright warning.
You may not reproduce copyright images without their owner's permission,
except in "fair use" cases,
or you could risk running into lawyer's warnings, cease-and-desist letters, and copyright suits.
Please be very careful before its usage! Use this script/code only for educational purposes.

Run code
==========

.. example-code::
.. codeblock:: bash
    virtualenv venv -p python3
    source venv/bin/activate
    pip install -r requirements.txt
    nano config.json

put this config on the config.json and save

.. codeblock:: JSON
    {
        "Records": [
            {
                "keywords": "apple",
                "limit": 100,
                "print_urls": true
            }
        ]
    }

Now again on terminal

.. codeblock:: bash
    python setup.py install
    python setup.py build
    googleimagesdownload -cf config.json

That's it now change the config.json as per your use case using the documentation

