                           *     .--.                                .                +
                                / /  `         *           .                                        *
               +               | |                                    +          *          .
                      '         \ \__,                      +                       +
                  *          +   '--'  *       @@@@       @@@   -     @@@                @@@      *
                      +   /\                    @@@@@     @@           @@                 @@
         +              .'  '.   *              @@@ @@    @@           @@    .       *    @@            +
                *      /======\      +          @@@  @@   @@           @@                 @@
                      ;:.  _   ;                @@@   @@  @@    @@@@   @@@@@@  @@@    @@  @@  @@@ @@@
                      |:. (_)  |                @@@    @@ @@   @@  @@  @@   @@  @@    @@  @@   @@@   @@
                      |:.  _   |                @@@     @@@@   @ @@    @@   @@  @@    @@  @@   @@
            +         |:. (_)  |          *    @@@@@     @@@   @@@@@@@ @@@@@@    @@@@@@@@ @@@ @@@@   +
                      ;:.      ;                             .                                          *
                    .' \:.    / `.                  .                         *             .  *
                   / .-'':._.'`-. \       *                 +                       +
                   |/    /||\    \|                 .                 *     .               +       *
                 _..--"""````"""--.._
           _.-'``                    ``'-._
         -'                                '-
===================================================================================================================

# ScyllaDB - Experimental
### This is the experimental version

I was originally facing some issues with the older scylladb docker file so I made this to be further optimized with
the more up to date scylladb dockerfile.

You can use this version of scylladb by using the following command :

`docker pull yaranai/scylladb`

Then you can run it like so :

`docker run -p $(hostname -i):9042:9042 -i -t scylladb/scylla`
