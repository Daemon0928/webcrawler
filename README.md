# webcrawler
A fájl túl nagy volt, Google Drive link;
https://drive.google.com/drive/folders/1yTdU6OaCyuW7pciOZXNLsbjDhPv6BgZ9?usp=share_link

settings.properties magyarázat:

start_url: kezdő url (Az első arguement felül írja)

depth: meglátogatandó weboldalak száma

max_links_per_page: maximális link amit a program kigyűjt egy adott oldalról

link_max_length: elfogadható link maximális hossza

page_load_strategy: EAGER (Nem tölti be a képeket, videokat, stíluslapokat. Gyorsabb, de néha kevesebb linket tud összegíűjteni az adott oldalról) 
               vagy NOMRAL
               
page_load_timeout_seconds: Próbálkozási idő(másodperc) mielőtt timeout-t dob a weboldal betöltésénél a program

stop_gathering_at_double_the_depth: true vagy false - depth * 2 linknél a program nem fog gyűjteni több linket (Sokkal gyorsabb magas depth-nél)

headless: true vagy false - háttérben futó chromeDriver
