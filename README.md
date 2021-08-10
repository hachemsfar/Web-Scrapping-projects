# Web Scrapping projects

Data extracting from websites by using differents techniques:

1/Beautiful Soap Library:
  - Extracting differents information(English name,Jap name,Ranking,Episodes Number...) about the top 14k animes by using "myanimelist.net/topanime.php" website and arrange them in one dataframe.
  - Extracting Country name &amp; passport power for all countries from "passportindex.org/byRank.php" website. Then, plot this data on map using Plotly library. 
  - Extracting people reviews and their given rating for every animes in animelist website (more than 13000 animes). This dataset is similar to imdb database (a standard dataset for ML learners), but imdb is for movie review and the labels are either positive or negative. And this new created dataset contains anime review and the rating (1..10)

2/Scrapy Libra
  - By inputing the link any manga ep on "mangareader.net". The script will download all images files of the manga. Then, fusionne them together in one pdf by using FPDF library.  
