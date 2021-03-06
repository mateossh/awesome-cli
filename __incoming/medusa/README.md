# medusa

* Homepage: http://foofus.net/goons/jmk/medusa/medusa.html

Medusa is intended to be a speedy, massively parallel, modular, login brute-forcer. The goal is to support as many services which allow remote authentication as possible. The author considers following items as some of the key features of this application:
      * Thread-based parallel testing. Brute-force testing can be
        performed against multiple hosts, users or passwords
        concurrently.
      * Flexible user input. Target information (host/user/password) can
        be specified in a variety of ways. For example, each item can be
        either a single entry or a file containing multiple entries.
        Additionally, a combination file format allows the user to
        refine their target listing.
      * Modular design. Each service module exists as an
        independent .mod file. This means that no modifications are
        necessary to the core application in order to extend the
        supported list of services for brute-forcing.
