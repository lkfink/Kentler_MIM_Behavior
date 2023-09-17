# Cross-modal correspondence between contemporary music & art
This repository contains data and code for reproducing the analyses reported in: 

Fink & Fiehn (2023). The role of audiovisual congruence in perception and aesthetic appreciation of contemporary music and visual art.

If using anything from this repository, please cite the paper. 

# About the project
While low-level, cross-modal correspondences between vision and hearing are well-documented (e.g., Kiki-Bouba effect), it is unclear whether cross-modal correspondences are perceivable between complex, multi-dimensional stimuli, like contemporary music and art. Further, previous studies show conflicting results regarding whether audiovisual correspondence affects subjective aesthetic experience. Here, in collaboration with the Kentler International Drawing Space (NYC, USA), we use material from the Music as Image and Metaphor exhibition, consisting of music composed for each work of visual art. Our pre-registered online experiment consisted of 4 conditions: Audio, Visual, Audio-Visual-Intended (artist-intended pairing of art/music), and Audio-Visual-Random (random shuffling). Participants (N=201) were presented with 16 pieces and could click to proceed to the next piece whenever they liked. After each piece, they were asked about their subjective experience. Analyzing results by condition, we found that participants spent significantly more time with Audio, followed by Audiovisual, followed by Visual pieces; however, they felt most moved in the Audiovisual (bi-modal) conditions. The Audiovisual-Intended pieces were perceived to have greater correspondence than those in the Audiovisual-Random condition. Interestingly, though, there were no significant differences for these two conditions on any other subjective rating scale or for time spent. Collectively, these results extend our understanding of cross-modal correspondence to complex, professional, real-world abstract art and contemporary music, and call into question the use of time spent as an implicit measure of aesthetic appreciation in multi-modal conditions.

## Relevant Links
This project is a collaboration with the Kentler International Drawing Space. Their online exhibition of *Music as Image and Metaphor* is available here: [https://www.kentlergallery.org/Detail/exhibitions/442](https://www.kentlergallery.org/Detail/exhibitions/442)

View the catalog from the exhibition here: [https://www.flipsnack.com/bobartlettcenter/music-as-image-and-metaphor.html](https://www.flipsnack.com/bobartlettcenter/music-as-image-and-metaphor.html)

In March 2023, during the final weeks of the exhibition at the Kentler, Lauren Fink joined a panel discussion with the curators and composers (David Houston, Florence Neal, Michael Kowalski, Allen Otte). Watch the hour+ discussion about the curation, composition, and scientific process here: [https://www.kentlergallery.org/Detail/events/540](https://www.kentlergallery.org/Detail/events/540)

You can view a demo of the online scientific experiment here: [https://www.labvanced.com/player.html?id=33023](https://www.labvanced.com/player.html?id=33023)

The pre-registration of experimental design and analyses is available here: [https://osf.io/hjgc5/](https://osf.io/hjgc5/)

# About this repository

## Dependencies
The code was developed in the language R and the RStudio environment (R Core Team, version 1.2.5033). 
The `dependencies.R` file contains all required packages to run the analyses. 

## Usage
As long as the required packages are installed and the directory structure of this repository is unchanged, all code should run on your local machine. 

The core analysis script is `Fink_Kentler_analyses.Rmd`.

Data are in the `data.csv`. 

The `figures` folder contains images submitted for publication. 
By default, the Rmd notebook will plot figures in line. If saving to file is preferred, set op = 1 near the top of the notebook. 

## More
Additional analyses, beyond those reported in the manuscript, are included in the code. Enjoy!



