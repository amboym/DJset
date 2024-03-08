# Introduction 
This project aims to leverage the Spotify Web API to extract track information from selected DJ playlists. By utilizing the Spotify API, the project retrieves track URIs from playlists belonging to various DJs, facilitating the analysis of audio features across different sets and comparison of my own set to theirs.

The art of DJing involves blending different tracks seamlessly, creating a continuous flow of music that captivates listeners and keeps them energized and entertained.
Mixing, the core activity of a DJ, involves transitioning between songs, manipulating sound elements, and blending tracks together harmoniously. DJs utilize equipment such as turntables, CDJs, mixers, and software to manipulate tempo, rhythm, and tone, allowing for smooth transitions and creative expression. Mixing is not just about playing songs in succession; it's about crafting a narrative through music, understanding crowd dynamics, and tailoring the set to suit the atmosphere and preferences of the audience.

## Mixing
![image](https://github.com/amboym/DJset/assets/162647158/e35b0ceb-0991-4064-8547-03c72f45dfb9)

To choose songs, a primary technique DJs use is called beatmatching. This involves adjusting the tempo of one track to match the other track. In the graphic above, the second track "Foundation" is originally created at a tempo of 135 BPM (Beats per minute). A DJ typically presses the cue button (the headphone button) to preview the track in his headphones and adjusts the tempo accordingly. They then have control over the song's lows, mids, and highs, and it is up to them to blend the two tracks together seamlessly, they can also blend tracks together with the use of effects (seen on the top left)

To ensure a seamless and musically pleasing mix, DJs often employ harmonic mixing, a technique rooted in music theory. Harmonic mixing involves selecting and blending tracks that share compatible musical keys or harmonies. When tracks are in the same or complementary keys, they tend to blend together more harmoniously, creating smoother transitions and maintaining the overall coherence of the mix. In harmonic mixing, DJs typically aim to keep their transitions within a range of -3 to +3 semitones, either up or down. This range allows for flexibility in selecting tracks while ensuring that the harmonic relationship between them remains intact. Moving within this range enables DJs to transition smoothly between tracks without causing dissonance or clashing harmonies. In the grahpic the key is shown by '3m' and '2m' under the track. (This could differ from DJ software - I use traktor software)

![image](https://github.com/amboym/DJset/assets/162647158/28f145f6-a8f0-4f9e-99b3-4618bfaf1546)

Although it is good practice to follow these principles, a good DJ typically finds creative ways to break them while still maintaining musical coherence and engaging the audience. This ability to deviate from traditional mixing techniques allows DJs to experiment with unexpected combinations of tracks, explore new musical avenues, and inject their sets with unique flair and personality


## Spotify feautures

__acousticness__: A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.

__instrumentalness__:Predicts whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly "vocal". The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0.

__danceability__: Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable.

__energy__ : Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. For example, death metal has high energy, while a Bach prelude scores low on the scale. Perceptual features contributing to this attribute include dynamic range, perceived loudness, timbre, onset rate, and general entropy.

__key__: The key the track is in. Integers map to pitches using standard Pitch Class notation. E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1.

__loudness__: The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks. Loudness is the quality of a sound that is the primary psychological correlate of physical strength (amplitude). Values typically range between -60 and 0 db.

__spechiness__: Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks.

__tempo__ : The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.

__valence__ : A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).
