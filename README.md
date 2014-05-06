virtual-tour
============

## Virtual Tour

README for Virtual Tour.

LEGAL

    For the duration of this copyright statement, 'this software' and
    'Virtual Tour' are taken to mean all original files distributed with
    this product, and the arrangement and other original work related to this
    product.

    License

        This software is copyright 2003-4 by Jonathan Hayward, and licensed
		and licensed to you under the your choice of the original Artistic
        License, which should be present in the file artistic.txt, the
        General Public License version 2.0, which should be present in the
        file gpl.txt, and the Massachusetts Institute of Technology License,
        which should be present in the file mit.txt.

    Warrantee

        Jonathan Hayward makes no warranties, express or implied,
        regarding this software.  In no event shall Jonathan Hayward be
        liable for any consequential, special, incidental, or indirect
        damages of any kind arising out of the license of, use of,
        or inability to use any software or product covered under
        this license, even if Jonathan Hayward has been advised of the
        possibility of such damages.  This limitation of liability and
        risks is reflected in the price of this software.

PURPOSE

    Virtual Tour is published to allow people to create interactive virtual
    tours.

INSTALLATION AND SETUP

    Basics

        * To install, run "./install" and answer the questions provided.  This
          will run a Unix-flavor install-style script and should create a
          working, out-of-the-box installation when supplied appropriate
          values. (The virtual tour will still need to be configured.)

        * To upgrade, run "./upgrade" and answer the questions provided. This
          will run a Unix-flavor install-style script and should upgrade your
          installation when provided appropriate values.

        * See USAGE below if are curions about how to use Virtual Tour.

        * The install script is not meant to fully set up or customize Virtual
          Tour, but only get it running.  See Customization below for
          further information on how to adjust Virtual Tour to meet your needs.

    Customization

    Security

        The present release of Catch the Furball has not been closely
        scrutinized for security, and should be treated as such by
        security-conscious administrators.  If you discover a vulnerability,
        please contact the author at jonathan.hayward@pobox.com with details.

        The default installation sets
        <the private Virtual Tour data directory> and contents
        to a relatively permissive mode.  Administrators are encouraged to
        set directory and contents to mode 700, owned by the effective user ID
        that CGI scripts will be running under. This is usually 'apache' or
        'nobody'.

USAGE

    Virtual Tour is designed to be run as a straightforward web
    application, with much administrative activity performed on-web.
    To use Virtual Tour, go to:

        http://[your hostname]/cgi-bin/virtual_tour

    To edit it, go to:

        http://[your hostname]/cgi-bin/virtual_tour?mode=edit

    (That is the location provided by RPM installation and the default for the
    provided installer. The provided installer allows you to specify another
    location; if you specified another location, substitute that for
    "/cgi-bin/virtual_tour".)

NOTES

    Payment

        Virtual Tour is linkware. It is available to you free of charge.
        If you like it, I would be very happy if you would visit
        http://JonathansCorner.com and consider linking to it.

    Bugs

        For security-related concerns, see Security above.

    Contact

        The author can be contacted at jonathan.hayward@pobox.com, and
        maintains a website at http://JonathansCorner.com. The current version
        of Virtual Tour may be obtained from
        http://JonathansCorner.com/etc/virtual_tour/ .
