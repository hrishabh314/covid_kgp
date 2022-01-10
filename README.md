# covid_kgp
## This project was made by me when I was quarantined in my college campus after testing positive. This was an attempt to predict how long would I be locked down in my campus room.

### kar 1: Was sad and wanted to see how our campus' curve looked. Gathered data from medical bulletins and plotted.
![fc4f36d0-3c74-4316-a2bb-1bec8442ad21](https://user-images.githubusercontent.com/74061616/148749434-cd7e47be-0264-4f09-b51f-39a49c7fa3f2.jpg)

### kar 2: Thought the curve had reached its peak. Thought of comparing it with various states (rajyas) of Bhaarata and Bhaarata. Used data from https://www.covid19india.org/
![abe0a9bf-d53c-4b17-b4a1-587243fcce0f](https://user-images.githubusercontent.com/74061616/148749762-c3df25f2-61b6-4aff-8680-1c7f4c3e8db4.jpg)

### kar 3: Not much was visible to the naked eye. Decided to quantify. Found rolling mean (or moving average is a technique to smoothen noisy courves) of the rajya curves.
![ma](https://user-images.githubusercontent.com/74061616/148750107-2d7b1817-fb92-4b2f-a516-ca5aff905355.JPG)

### kar 4: Quantified the closeness of kgp's (my college's) curve with various rajya's curves. (lower the better)
![fitting](https://user-images.githubusercontent.com/74061616/148750249-cafffa3f-3aef-40ca-9e24-80595efcebc1.JPG)

### kar 5: Took the 3 closest curves, and used their die-out period to predict kgp curve's die-out period
![bestfits](https://user-images.githubusercontent.com/74061616/148750554-91e391b0-0848-4ad9-88e4-e5d0e307ca9c.JPG)
![result](https://user-images.githubusercontent.com/74061616/148750684-8dda7110-b385-4120-9ba8-868961700691.JPG)

Only time will tell how my prediction ages. Considering the uptrend for the overall country, I believe my first fundamental assumption that peak had been reached might be proved wrong. :')

