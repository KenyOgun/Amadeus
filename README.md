# Amadeus
> Amadeus Entertainment is an entertainment retailer specializing in music, films, and audio books. It has eight online stores operating in the United States, Germany, France, the United Kingdom, Spain, Australia, Japan, and India. It has 96 offline stores operating in those
countries as well. Customers can buy individual products such as a song, an audio book, or a film, or they can subscribe to a certain package, which enables them to download a certain quantity of products in a certain period. For example, with the Primer package, you can download 100
songs, 50 books, and 50 films a month for $50. Customers can also listen or watch a song, a book, or a film once for 1⁄10 the cost of purchasing it. So if a film is $5, to watch it once it’s only 50 cents. Customers use online streaming for this, so a good Internet connection is required. Amadeus Entertainment has four main delivery channels: Internet, mobile phone, cable TV, and post. There are several payment models for customer subscriptions, such as annual, in advance, and monthly direct debit. The company purchases the products in bulk, such as any 10,000 songs from a record company, of any title, for a certain cost. For online streaming, the company pays a central provider (Geo Broadcasting Ltd.) based on usage (monthly invoice). The company uses WebTower9, a custom-developed .NET-based system for dynamic web sites, multimedia trading, broadcasting, sales order processing, and subscription management, all running on an Oracle database. The back-end enterprise resource planning (ERP) system is Jupiter, an off-the-shelf AS/400-based business system running on DB2. This is where the inventory, products, and finances are managed. The Jupiter database size is about 800GB with about 250 tables and views. Business activities in the offline stores are managed in Jade, which is a custom Java-based system running on Informix. This includes sales, customer service, and subscriptions. WebTower9 and Jade interface with Jupiter products and finances on a daily basis, but sales and customer data (including subscriptions) are kept on WebTower9 and Jade. The company uses the SupplyNet system for interfacing with suppliers. It is a web services–based industry-standard supplier network in the online entertainment industry including music and film. WebTower9 and Jupiter are hosted in Amadeus Entertainment’s head office. Jade is hosted in an outsourced company in Bangalore, India. The Jupiter overnight batch starts at 11 p.m. Eastern standard time (EST) for three to four hours. An offline backup job kicks off immediately after the overnight batch and runs for one to two hours. The Jade tape backup starts at 3 a.m. EST for two to three hours.
