# Songs in Four Farah Khan Films

## Dataset

This dataset contains 37 song records associated with four films directed by Farah Khan: *Main Hoon Na* (2004), *Om Shanti Om* (2007), *Tees Maar Khan* (2010), and *Happy New Year* (2014). One row represents one title or version in the initial collection, including remixes, reprises, medleys, and theme entries.

This is a file created for academic purpose. It is a file which can be used to study the discography of the songs in Farah Khan Movies. Not all the sources lead to the song, however, these songs are easily available on any streaming platforms like apple music, spotify, youtube etc.

## Motivation and possible questions

The dataset was created to organize songs and credits from Farah Khan's four directed films in a small, inspectable table. It could support questions such as how the credited singers, composers, or lyricists vary across the four soundtracks. It cannot by itself explain the musical, cinematic, or cultural meaning of those differences. A similar list can be created for a larger dataset for most bollywood movies, and maybe individual files, if created, can include the lyrics as well.

## Selection criteria and coverage

The four films were selected because Farah Khan is credited as the director of the movies these songs are a part of. Song titles in the initial collection were retained, including alternate versions and remixes as separate records. The dataset represents that initial selection, not every song heard in each film or every track in every soundtrack edition. Streaming editions may differ.

## Data collection and provenance

The data was assembled by the list of songs available in the streaming platforms against each movie albums. 

## Cleaning and preprocessing

No audio or lyrics are included. Song titles and names were entered as metadata. IDs use a film name abbreviation and running number (for example, 'song_mhn1' translates to "song - main hoon na - 1"). Multiple people in a field are separated with semicolons. Unknown values are left empty.

## Structure and codebook

The repository uses one CSV file, 'fk_movie_songs.csv', with one row per record. It uses the assignment's records-in-a-CSV option, so there is no 'data/' folder or 'file' column.

What each column means:
*id* - Unique song identifier (song_filenameabbreviated_number) (string)
*song_title* - Name of the song (string)
*film_title* - Name of the movie the song is a part of (string)
*film_year* - Year of the release of the movie (Integer)
*singer* - Name of the singer, Names separated by semicolons ';' if more than one singer, may say 'Instrumental' or 'Multiple singers', Empty if unknown (string)
*composer* - Composers, Names separated by semicolons ';' if more than one composer, Empty if unknown (string)
*lyricist* - Lyricist, Names separated by semicolons ';' if more than one, Empty if unknown or not applicable (string)
*source* - Album page used as a reference for the record, URL text, Apple Music album URL, Empty if coudnt find the right source (string)
*licence* - ℗ notice shown on the cited commercial soundtrack album page; this is a rights notice, not an open reuse licence, Copyright line as shown on the source page, Empty if source is blank (string)
*source_accessed* - 'YYYY-MM-DD', Empty if source is blank

## Uses and limitations

The table can support a small descriptive comparison of listed song credits across these four films. It is not a representative sample of Hindi cinema, film music, or Farah Khan's choreography career. A reader should not infer musical style, authorship, or cultural influence from the counts alone. It can be expanded into a larger dataset with files including the lyrics of the songs, which can then further be used to study on the discography of the Bollywood music.

## Ethical and legal considerations

The dataset contains descriptive metadata only; it does not include sound recordings, album artwork, or song lyrics. Blank entries are not claims that a track is public domain or freely reusable. However, the song list is available on many streaming platforms and can be accessed from there. 

## Dataset licence and citation

A reuse licence for this metadata dataset is open. Do not treat the dataset licence as applying to the underlying songs or recordings.

Suggested citation format *ruchikamattikop123. Songs in Four Farah Khan Films. Version 1.0. [Repository URL], accessed [date].*

## References

- [Main Hoon Na (Original Motion Picture Soundtrack), Apple Music](https://music.apple.com/us/album/main-hoon-na-original-motion-picture-soundtrack/1120934166) (accessed 2026-11-25).
- [Om Shanti Om (Original Motion Picture Soundtrack), Apple Music](https://music.apple.com/us/album/om-shanti-om-original-motion-picture-soundtrack/1071079468) (accessed 2026-11-25).
- [Tees Maar Khan (Original Motion Picture Soundtrack), Apple Music](https://music.apple.com/us/album/tees-maar-khan-original-motion-picture-soundtrack/1123140178) (accessed 2026-11-25).
- [Happy New Year (Original Motion Picture Soundtrack), Apple Music](https://music.apple.com/us/album/happy-new-year-original-motion-picture-soundtrack/1111791018) (accessed 2026-11-25).
