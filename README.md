# my-music-therapy

Collection of favorite contemporary classical music. By far (2024 CE), it is a selection of tracks from video game soundtracks, which feature orchestral music. It is divided into two directories: ``classical``, which contains more balanced works; and ``soundtracks``, which are more liberal. In particular, the latter are more oriented toward creating a particular setting or climate for the video game (such as Japanese, Nordic, Country…).

The majority of songs were downloaded from YouTube.com on the basis of fair use. For this purpose I used [yt-dlp](https://github.com/yt-dlp/yt-dlp#readme) application from Debian official repositories. The vast majority of the songs are in Ogg Opus format. However, individual files are Ogg Vorbis. Compositions by Paul Anthony Romero and Rob King are in MP3 format. These exceptions are because they were downloaded directly from the authors in the original format (like [Wesnoth Project](https://github.com/wesnoth/wesnoth/tree/master/data/core/music) and [SoundCloud](https://soundcloud.com/paul-anthony-romero/sets/heroes-of-might-magic-music-by)).

All the files have basic metadata: Author + Composer, Title, Album, Date (YEAR). However, since getting all the facts is difficult, I only did a basic search online for this information. Therefore, I cannot guarantee the correctness (or, rather, completeness) of these tags. For example, the album names are chosen arbitrarily by me. Futhermore, all the tracks have ReplayGain 2.0 tags (track gain only). They were generated using [loudgain](https://github.com/Moonbase59/loudgain/): ``loudgain -k -s i FILES``. The ``-k`` flag means clipping was avoided.

If hope you'll enjoy it. Have a good day!
