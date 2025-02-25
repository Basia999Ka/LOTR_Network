# LOTR_Network
### Lord of The Rings - The Return of The King - Network
![image](https://github.com/user-attachments/assets/18fbcd62-8f02-4210-8e47-c2fc13c00f9b)

### Lord of the rings characters relationships network in python
Library: pandas, selenium , spaCy, networkx, pyvis, community

1. Using Selenium to scrape character data from the page https://lotr.fandom.com/wiki/Category:The_Lord_of_the_Rings_characters
2. Loading spaCy Model and Data
3. Character data is loaded from a CSV file
4. Processing books text to extract characters relationships. Text is processed to find sentences where characters appear. Then characters are identified based on the character data.
5. A graph of relationships between characters is created using the NetworkX library, and then visualized using pyvis.Network. Relationships between characters are built based on the proximity of characters in the text.
6. Identifying Communities in the Graph, using the Louvain algorithm.
